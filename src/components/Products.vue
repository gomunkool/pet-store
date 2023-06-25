<template>
  <div>
    <div class="main" v-for="product in products">
      <div>Type:<strong>{{ product.type }}</strong></div>
      <div>Habitat:<strong>{{ product.live }}</strong></div>
      <div>Prise:<strong>{{ product.prise }}</strong></div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped></style>