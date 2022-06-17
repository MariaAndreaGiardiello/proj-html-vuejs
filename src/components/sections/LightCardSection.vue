<template>
  <section class="section-background d-flex align-items-center">
        <div class="container-sm justify-content-center ">
            <div class="row justify-content-center d-grid gap-3">
                <div class="col-3 mx-2 white-box">
                    <div class="img-circle"><img class="img-fluid" src="src/assets/img/users-icon.png" alt=""></div>
                    <h5 class="card-title">Human Capital</h5>
                    <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Sint saepe quibusdam in similique at doloremque</p>
                </div>
                <div class="col-3 mx-2 white-box">
                    <div class="img-circle"><img class="img-fluid" src="src/assets/img/users-icon.png" alt=""></div>
                    <h5 class="card-title">Core Business</h5>
                    <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Sint saepe quibusdam in similique at doloremque</p>
                </div>
                <div class="col-3 mx-2 white-box">
                    <div class="img-circle"><img class="img-fluid" src="src/assets/img/users-icon.png" alt=""></div>
                    <h5 class="card-title">Performance</h5>
                    <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Sint saepe quibusdam in similique at doloremque</p>
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
    padding: 20px;
}

.section-background {
    background-color: var(--tertiary-color);
    height: 400px;
}

.img-circle{
    width: 40px;
    height: 40px;
    border-radius: 100%;
    background-color: var(--circle-icon);
    margin-bottom: 15px;
    opacity: 0.7;
}

.card-title{
    font-weight: bold;
    font-size: 16px;
}

.card-text{
    font-size: 12px;
    color: var(--font-color);
}
</style>