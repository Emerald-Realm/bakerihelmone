<template>
  <div class="contact-us">
    <ul class="contact-one">
      <li class="contact-one-item">Address</li>
      <li class="contact-one-item">Email</li>
      <li class="contact-one-item">Phone number</li>
    </ul>
    <ul class="contact-two">
      <li class="contact-two-item">BakerExample address</li>
      <li class="contact-one-item">Bakerabc@example.com</li>
      <li class="contact-one-item">0123456789</li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'Contact'
}
</script>

<style scoped>
  .contact-us {
    display: flex;
    align-items: center;
    justify-content: space-around;
  }
</style>
