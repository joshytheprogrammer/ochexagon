<template>
  <div class="about">
    <div class="content">
      <figure>
        <img src="https://images.unsplash.com/photo-1462206092226-f46025ffe607?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1080&q=80" alt="">
      </figure>
      <h1>CORPORATE PROFILE OF O. C HEXAGON NIGERIA LIMITED.</h1>
      <p>
        O. C HEXAGON NIGERIA LIMITED was incorporated in the year 1995 for the purpose of importation, marketing and processing industrial chemicals, equipment and laboratory items. Is an offshoot of the parent company, HEXAGON MARKING COMPANY which was registered in 1989.

        Our office is located at 417, Apapa/Oshodi Expressway by Iyana Itire Ilasamaja Lagos comprising of an office apartment and a warehouse. We have been into chemical and allied products since 1993.

        We equally have our production and blending site at No. 12 Kolawole Shonibare Street, Ajao Estate, Lagos, comprising a factory and warehouses.

        The Directors of the company are MR. CLIFFORD ONYEJE who doubles as the Chairman and Chief Executive Officer with a Bachelor of Science (B.Sc) degree in Marketing from the University of Nigeria Nsukka, 1989.

        The other Director is ENGR. IGNATIUS ONYEJE who holads a B.Sc in Electrical Electronics Engineering from the University of Nigeria Nsukka, 1981, an MSC degree in Computer and Electronics Engineering and currently a senior lecturer at the Federal Polytechnic Nekede, Owerri.

        We equally have Mrs. Stella Onyeje as a Director. She holds a B.Sc in Microbiology from the University of Nigeria Nsukka and a Masters Degree in Environmental Management (MEM) from the University of Lagos.
        We have permanent staff of eleven (11) workers, spanning through Secretarial, Technical, HSE, Analysts, Sales, Delivery, Administrative Staff and numerous casual workers.

        However, we have a plant here in Lagos for the exclusive production\blending of the following chemicals:
        (1) SODIUM HYPOCHLORITE SOLUTION HEC-15 brand in 200 litres reinforced plastic drums which is already in use in NLNG since 1999, Nigeria breweries plants all over Nigeria, SPDC. It is used as a biocide, in water treatment, sludge removers etc. Ours is of a high concentration with up to 14% chlorine content at the time of production.
        (2) SODIUM HYDROXIDE SOLUTION HEX-30, HEX-40, HEX-50 brand in 200 litres reinforced plastic drums, already in use in all the plants of Nigeria Breweries.
        (3) MULTIPURPOSE DEGREASER HEC-WASH brand packaged in 20 litres and 200 litres plastic drums already in use in SPDC for washing off greases and oils.
        (4) OIL ABSORBENT GRANULES/PILLOWS for clearing of oil spillages on water and grounds.

        Our current turnover is about nine hundred and fifty million naira (₦950,000,000) per annum. Presently we supply chemicals to SPDC, SNEPCO, Nigeria Breweries plants in Lagos, Kaduna, Ibadan, Ama-Enugu, aba, Intafact Beverages Ltd (a subsidiary of SABMiller) Onitsha, Seven-up Bottling Company Plc., Kam Industries Ltd. Ilorin, Nigeria Liquefied Natural Gas (NLNG) Bonny and many oil servicing companies.

        Our Bankers are Diamond Bank Nig. Plc., 58, Lawanson Road, Lagos, Zenith Bank Plc, 133 Ladipo Street Matori, Lagos, FCMB Plc., 117, Okota road, Okota, Lagos and Keystone Bank Plc., Ajose Adegun branch, Lagos.

        Currently we are going through a lot of training and retraining of our staff to meet with the challenges of the new millennium. We invite you to be involved in the various product lines of O. C HEXAGON (NIG) LIMITED.
      </p>
    </div>
  </div>
</template>

<script>
export default {
  head: {
    title: 'About - O.C.Hexagon Nigeria Limited'
  },
}
</script>


<style lang="scss" scoped>
.about {
  width: 90%;
  margin: 72px auto;
  padding: 1rem;

  .content {
    display: inline-block;

    figure {
      float: left;
      width: 600px;
      padding: 0 1rem 0 0;

      img {
        width: 100%;
        height: 100%;
        object-fit: cover;
      }
    }

    h1 {
      font-size: 36px;
      font-weight: 500;
      padding: 2rem 0;
    }

    p {
      font-size: 16px;
      line-height: 1.85;
      padding: 1rem 0;
    }
  }

  @media screen and (max-width: $medium) {
    width: 100%;

    .content {
      display: block;

      figure {
        width: 100%;
      }

      p {
        line-height: 2;
      }
    }
  }
}
</style>