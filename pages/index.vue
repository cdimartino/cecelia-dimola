<template>
  <div class="container">
    <div class="section links">
      <Nav />
    </div>
    <div class="section tribute">
      <!-- CONTENT START -->
      <div class="title">Celebrating the Life of</div>
      <div class="title name">{{ $config.name }}</div>
      <img height="600" src="~/assets/frontimage.jpg" alt="Photo of Cecelia Mary DiMola" />
      <div class="title dates">{{ $config.dates }}</div>
    </div>
      <!-- CONTENT END -->
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss">

</style>
