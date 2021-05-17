<template>
  <div class='service-card' v-for='service in serviceList' :key='service.id'>
    <img src='#' alt='#' class='service-logo' />
    <div class='service-context'>
      <p>
        {{ service.topic }}
      </p>
      <p>
        {{ service.context }}
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'BaseServiceCard',
  props: {
    serviceList: Array
  }
}
</script>
