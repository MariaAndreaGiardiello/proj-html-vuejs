<template>
  <header class="header-background">
    <div class="container">
      <div class="row justify-content-between">
        <div class="col-3 header-text">
          <i class="fa-solid fa-clock"></i> Open Hours: Mon - Sat - 9:00 - 18:00
        </div>
        <div class="col-6 header-text d-flex">
          <div class="px-3"><i class="fa-solid fa-clock"></i> +1 (305) 1234-5678</div>
          <div class="px-3"><i class="fa-solid fa-clock"></i> hello@examplel.com</div>
          <div class="px-3">
            <i class="fa-solid fa-clock"></i>
            <i class="fa-solid fa-clock"></i>
            <i class="fa-solid fa-clock"></i>
          </div>
        </div>
      </div>
    </div>
  </header>
</template>

<script>
export default {
    name: 'HeaderComponents'
}
</script>

<style lang="scss" scoped>
.header-background{
  background-color: var(--primary-color);
  height: 40px;
}
</style>