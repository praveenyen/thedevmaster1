<template>
  <div class="layout">
    <nuxt class="nuxt-content"/>
    <Footer/>
  </div>
</template>
<script data-ad-client="ca-pub-7755399896554210" async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script>
<script>
  import Footer from '~/components/Sections/Footer'

  export default {
    components: {
      Footer
    }
  }
</script>
<style lang="scss">
.layout {
  display: flex;
  flex-direction: column;
  min-height: 100vh;
}

.nuxt-content {
  flex-grow: 1;
}
</style>
