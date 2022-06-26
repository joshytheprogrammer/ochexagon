<template>
  <footer>
    <div class="address">
      <h3>Address</h3>
      <p>417, Apapa/Oshodi Expressway by Iyana Itire Ilasamaja, Lagos.</p>
      <p>12 Kolawole Shonibare Street, Ajao Estate, Lagos.</p>
    </div>
    <div class="contacts">
      <h3>Contacts</h3>
      <p>+234 802 224 1271</p>
      <p>+234 803 051 2882</p>
      <p><a href="mailto:ochexagon@yahoo.com">ochexagon@yahoo.com</a></p>
    </div>
    <div class="attribution">
      <h3>O.C Hexagon Nigeria Limited</h3>
      <p>This website was created by <a href="https://www.joshytheprogrammer.com">joshytheprogrammer</a></p>
      <p>© 2022 O.C Hexagon Nigeria Limited. All Rights Reserved.</p>
    </div>
  </footer>
</template>

<style lang="scss" scoped>
footer {
  margin: 72px 0;
  padding: 0 1rem;

  text-align: center;

  display: grid;
  grid-template-columns: repeat(3, 1fr);

  div {
    padding: 1rem 0;
  }

  h3 {
    font-size: 24px;
    font-weight: 500;
  }

  p {
    font-size: 14px;
    font-weight: 400;
    padding: 5px 0;
  }

  a {
    color: $dark;
  }

  @media screen and (max-width: $m-large) {
    display: block;
  }
}
</style>