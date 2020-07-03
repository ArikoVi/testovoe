<template>
  <div>
    <Navbar />
    <main>
      <div class="conteiner">
        <Nuxt />
      </div>
    </main>
  </div>
</template>

<script>
import Navbar from '@/components/Navbar'
export default {
  components:{
    Navbar
  }
}
</script>

// <script>
// import TopHeader from '~/components/TopHeader.vue'
// import BottomFooter from '~/components/BottomFooter.vue'
 
// export default {
//   components: {
//     TopHeader,
//     BottomFooter
//   }
// }
// </script>
 
<style lang="scss">
@import '../assets/scss/styles.scss';
</style>
