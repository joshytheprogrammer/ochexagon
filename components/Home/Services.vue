<template>
  <section class="services" id="services">
    <h2>Services we provide</h2>
    <p>O.C Hexagon Nigeria Limited was incorporated in the year 1995 for the purpose of importation, marketing and processing industrial chemicals, equipment and laboratory items. Here are just a few things we do:</p>
    <div class="content">
      <Card v-for="item in data" :key="item.id" :data="item"  />
    </div>
  </section>
</template>

<script>
import Card from "../Helpers/S-Card.vue"
export default {
  components: {
    Card,
  },
  data() {
    return {
      data: [
        {
          id: 0,
          imgLink: 'https://images.unsplash.com/photo-1606206873764-fd15e242df52',
          service: 'Industrial Equipment',
          desc: 'We export minerals to several countries in the west. These minerals include Zinc, Lead, Charcoal. We have an excellent track record and are trusted by many firms.'
        },
        {
          id: 1,
          imgLink: 'https://images.unsplash.com/photo-1614934273801-0da56c52b081',
          service: 'Laboratory Items',
          desc: 'We partner with several web developers to help our clients build apps as quickly and as cost efficiently as possible. We help build all manner of Applications.'
        },
        {
          id: 2,
          imgLink: 'https://images.unsplash.com/photo-1554475901-4538ddfbccc2',
          service: 'Industrial Chemicals',
          desc: 'We assist companies and governments to solve their problems quickly. Our trust worthy name makes us the choice contractor for NPA, MTN and many more.'
        },
      ]
    }
  }
} 
</script>

<style lang="scss" scoped>
.services {
  margin: 72px 1rem;

  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;

  h2 {
    font-size: 36px;
    font-weight: 500;
    padding: 2rem 0;
  }

  p {
    width: 600px;
    font-size: 16px;
    line-height: 1.85;
    padding: 1rem 0;
  }

  .content {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 1rem;
  }

  @media screen and (max-width: $m-large) {
    .content {
      grid-template-columns: repeat(2, 1fr);
      margin: 1rem 0;
    }
  }

  @media screen and (max-width: $medium) {
    padding: 1rem;
    display: block;

    .content {
      display: block;
    }

    h2 {
      font-weight: 400;
      font-size: 36px;
      padding: 1rem 0;
    }

    p {
      width: 100%;
      line-height: 1.85;
      font-size: 18px;
      padding: 1rem 0;
    }
  }
}
</style>