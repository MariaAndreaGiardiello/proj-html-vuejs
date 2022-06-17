<template>
  <section class="section-background d-flex align-items-center">
    <div class="container-sm justify-content-center ">
        <div class="row justify-content-center d-grid gap-3">
            <div class="col-3 mx-2 white-box">
                <h4>Human Capital</h4>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sint saepe quibusdam in similique at doloremque</p>
            </div>
            <div class="col-3 mx-2 white-box">
                <h4>Human Capital</h4>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sint saepe quibusdam in similique at doloremque</p>
            </div>
            <div class="col-3 mx-2 white-box">
                <h4>Human Capital</h4>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sint saepe quibusdam in similique at doloremque</p>
            </div>
        </div>
    </div>

  </section>
</template>

<script>
export default {
    name: 'ProfitSection',
}
</script>

<style lang="scss" scoped>
.white-box{
    background-color: white;
    border-radius: 10px;
}

.section-background {
    background-color: var(--tertiary-color);
    height: 400px;
}
</style>