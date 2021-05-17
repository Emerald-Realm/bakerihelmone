<template>
<p class="motto">
  Perfection Breeds Perfection
</p>

  <div class="service">
    <BaseServiceCard :serviceList='serviceList' />
  </div>
</template>

<script>
import BaseServiceCard from './BaseServiceCard'
import serviceList from '../../assets/APIs/serviceList'

export default {
  name: 'Service',
  components: {
    BaseServiceCard
  },
  data () {
    return {
      serviceList
    }
  }

}
</script>

<style scoped>
  .service {
    display: flex;
    align-items: center;
    justify-content: space-around;
  }
</style>
