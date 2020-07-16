<template>
  <div class="">
    <div class="p-4 md:p-16 bg-grey">
      <Header />
      <Contact />
      <Body />
      <Footer />
    </div>
  </div>
</template>

<script>
  export default {
    data () {
      return {
        title: 'Vivo Life CV: ckhatton'
      }
    },
    head () {
      return {
        title: this.title
      }
    }
  };
</script>

<style>
/* Sample `apply` at-rules with Tailwind CSS
.container {
@apply min-h-screen flex justify-center items-center text-center mx-auto;
}
*/
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
</style>
