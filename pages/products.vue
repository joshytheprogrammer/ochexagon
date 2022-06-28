<template>
  <div class="services">
    <div class="service" v-for="item in data" :key="item.id">
      <div class="_image">
        <img :src="item.imgLink" :alt="item.service">
      </div>
      <div class="_details">
        <h2>{{item.service}}</h2>
        <p>{{item.desc}}</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  head: {
    title: 'Products - O.C.Hexagon Nigeria Limited'
  },
  data(){
    return {
      data: [
        {
          id: 0,
          imgLink: 'https://res.cloudinary.com/dsgvwxygr/image/upload/v1656421878/blog/s_h_s_NaOCL_ord06x.webp',
          service: 'Sodium Hypochlorite Solution Hec-15',
          desc: 'Sodium Hypochlorite Solution Hec-15 brand in 200 litres reinforced plastic drums which is already in use in NLNG since 1999, Nigeria breweries plants all over Nigeria, SPDC. It is used as a biocide, in water treatment, sludge removers etc. Ours is of a high concentration with up to 14% chlorine content at the time of production.'
        },
        {
          id: 1,
          imgLink: 'https://res.cloudinary.com/dsgvwxygr/image/upload/v1656422013/blog/sod1_metkzz.webp',
          service: 'Sodium Hydroxide Solution Hex-30, Hex-40',
          desc: 'Sodium Hydroxide Solution Hex-30, Hex-40, Hex-50 brand in 200 litres reinforced plastic drums, already in use in all the plants of Nigeria Breweries.'
        },
        {
          id: 2,
          imgLink: 'https://res.cloudinary.com/dsgvwxygr/image/upload/v1656422293/blog/Multipurpose_Degreaser_Hec-Wash_cmrvub.webp',
          service: 'Multipurpose Degreaser Hec-Wash',
          desc: 'Multipurpose Degreaser Hec-Wash brand packaged in 20 litres and 200 litres plastic drums already in use in SPDC for washing off greases and oils.'
        },
        {
          id: 3,
          imgLink: 'https://res.cloudinary.com/dsgvwxygr/image/upload/v1656422407/blog/Oil_Absorbent_w6tk1a.webp',
          service: 'Oil Absorbent Granules',
          desc: 'Oil Absorbent Granules/Pillows for clearing of oil spillages on water and grounds.'
        },
      ]
    }
  }
}
</script>
<style lang="scss" scoped>
.service {
  padding: 1rem;

  display: grid;
  gap: 1rem;
  grid-template-columns: 1fr 1fr;

  ._image {
    max-width: 100%;
    height: 600px;

    img {
      width: 100%;
      height: 100%;
      object-fit: contain;
    }
  }

  ._details {
    padding: 1rem;
    width: 100%;
    display: flex;
    text-align: center;
    flex-direction: column;
    justify-content: center;

    h2 {
      font-size: 36px;
      font-weight: 400;
      padding-bottom: 1rem;
      text-transform: capitalize;
    }

    p {
      font-size: 16px;
      line-height: 1.85;
      padding: 1rem 0;
    }
  }

  @media screen and (max-width: $medium) {
    display: block;

    ._image {
      max-width: 90%;
      height: 400px;
      margin: auto;
    }
  }
}
</style>