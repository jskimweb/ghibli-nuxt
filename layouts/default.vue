<template>
  <div>
    <Header />
    <Nuxt />
  </div>
</template>

<script>
  import Header from '~/components/Header.vue'
  export default {
    components: {
      Header
    }
  }
</script>

<style>
  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    outline: none;
  }

  a {
    color: black;
    text-decoration: none;
  }

  button {
    background: none;
    border: none;
  }

  img {
    border: 0;
    vertical-align: middle;
  }

  li,
  ul {
    list-style: none;
  }

  html {
    font-size: 10px;
  }

  body {
    font-family: 'Noto Sans KR', sans-serif;
    font-size: 2rem;
    font-weight: 400;
    -ms-overflow-style: none;
    scrollbar-width: none;
  }

  ::-webkit-scrollbar {
    display: none;
  }

  .container {
    margin: 5rem auto;
  }

  .fade-enter-from {
    opacity: .5;
  }

  .fade-enter-active {
    transition: .5s;
  }
</style>