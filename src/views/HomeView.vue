<template>
  <HomeName />
  <OnSale />
</template>
<script>
// @ is an alias to /src
import HomeName from '@/components/Home.vue'
import OnSale from '@/components/Sale.vue'
export default {
  name: 'HomeView',
  components: {
    HomeName,
    OnSale
  }
}
</script>
