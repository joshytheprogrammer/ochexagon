<template>
  <section class="testimonials" id="testimonials">
    <h2>Here's what our clients say</h2>
    <div class="content">
      <div class="card">
        <p class="testimony">”I've been working with O.C. Hexagon for several years and I don't have any complaints. Their customer experience is great and they always keep their promises.”</p>
        <h4 class="testifier">-Kingsley Nsofor</h4>
      </div>
      <div class="card">
        <p class="testimony">"OCHEXAGON is one of the best clients I've worked with. Their customer experience was wonderful and I am not even one of their customer. If you can, give them a try."</p>
        <h4 class="testifier">-joshytheprogrammer</h4>
      </div>
      <div class="card">
        <p class="testimony">"When it comes to importation, marketing and processing industrial chemicals, equipment and laboratory items. There is no better name than O. C HEXAGON NIGERIA LIMITED."</p>
        <h4 class="testifier">-Emeka 23.08.13</h4>
      </div>
    </div>
  </section>
</template>

<style lang="scss" scoped>
.testimonials {
  margin: 72px 1rem;

  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;

  h2 {
    font-size: 36px;
    font-weight: 400;
    padding: 2rem 0;
  }

  .content {
    display: grid;
    gap: 1rem;
    grid-template-columns: repeat(3, 1fr);

    .card {
      margin: 2rem 0;

      .testimony {
        font-size: 16px;
        line-height: 1.85;
      }

      .testifier{
        font-size: 14px;
        font-weight: 500;
        padding: 1rem 0;
      }
    }
  }

  @media screen and (max-width: $m-large) {
    .content {
      grid-template-columns: repeat(2, 1fr);
      margin: 1rem 0;
    }
  }

  @media screen and (max-width: $medium) {
    .content {
      display: block;
    } 
  }
}
</style>