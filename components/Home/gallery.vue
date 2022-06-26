<template>
  <section class="gallery" id="gallery">
    <figure>
      <img src="https://images.unsplash.com/photo-1513828742140-ccaa28f3eda0" alt="ochexagon image 1">
    </figure>
    <figure>
      <img src="https://images.unsplash.com/photo-1599727277643-b0c9cfb7705d" alt="ochexagon image 2">
    </figure>
    <figure>
      <img src="https://images.unsplash.com/photo-1518152006812-edab29b069ac" alt="ochexagon image 3">
    </figure>
  </section>
</template>

<style lang="scss" scoped>
.gallery {
  margin: 72px 1rem;
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 1rem;

  figure {
    height: 400px;

    img {
      width: 100%;
      height: 100%;
      object-fit: cover;
      display: block; 
    }
  }

  @media screen and (max-width: $m-large) {
    grid-template-columns: repeat(2, 1fr);
  }

  @media screen and (max-width: $medium) {
    display: block;
    
    figure {
      margin: 1rem 0;
    }
  }
}
</style>