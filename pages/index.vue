<template>
  <section class="container">
    <div class="left">
      <logo/>
    </div>
    <div class="right">
      <dayQuote/>
    </div>
  </section>
</template>

<script>
import Logo from '~/components/Logo.vue'
import DayQuote from '~/components/DayQuote.vue'

export default {
  components: {
    DayQuote,
    Logo
  }
}
</script>

<style>
.container {
  @apply min-h-screen flex justify-center text-center mx-auto;
}
.container {
  border: 5px solid blue;
}
.container > * {
  @apply items-center;
}
.container > * {
  border: 5px solid red;
  position: relative;
}
.container .left {
  flex: 1 1 60%;
}
.container .right {
  flex: 1 1 40%;
}
</style>
