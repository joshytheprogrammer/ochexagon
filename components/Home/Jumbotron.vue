<template>
  <section class="jumbotron">
    <img src="~/assets/images/logo.png" alt="">
    <h1>We are happy to make you happier.</h1>
    <p>We have put together, a world class range of products to create that unique industrial experience. We invite you to be involved in the various product lines of O. C HEXAGON (NIG) LIMITED.</p>
    <a href="mailto:ochexagon@yahoo.com">Get Quote</a>
  </section>
</template>

<style lang="scss" scoped>
.jumbotron {
  padding: 1rem;
  // background-image: url("https://images.unsplash.com/photo-1588011930968-eadac80e6a5a?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=2069&q=80");
  background-attachment: fixed;
  background-repeat: no-repeat;
  background-color: $dark;
  object-fit: fill;
  height: 700px;
  max-width: 100%;
  color: $light;

  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;
  justify-content: center;

  h1 {
    font-weight: 500;
    font-size: 48px;
    padding: 1rem 0;
  }

  p { 
    width: 900px;
    line-height: 1.875;
    font-size: 18px;
    padding: 1rem 0;
  }

  a {
    display: block;
    width: fit-content;
    background: $light;
    color: $primary;
    padding: 12px 16px;
    text-decoration: none;
    border-radius: 8px;

    &:hover {
      background: $primary;
      color: $light;
    }
  }

  @media screen and (max-width: $medium) {
    // background-image: url('https://images.unsplash.com/photo-1588011930968-eadac80e6a5a?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1200&q=80');
    padding-bottom: 2rem;
    height: 600px;

    h1 {
      font-weight: 400;
      font-size: 36px;
    }

    p {
      width: 100%;
      line-height: 1.85;
      font-size: 18px;
    }
  }
}
</style>