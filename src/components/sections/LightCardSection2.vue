<template>
  <section class="section-background d-flex align-items-center">
        <div class="container-sm justify-content-center ">
            <div class="row justify-content-center">
                <div class="col-6 justify-content-center align-self-center">
                    <div class="green-text text-center">MONTHLY PLANS</div>
                    <h2 class="text-center"><span class="backgrounded-text text-centre">Pricing</span>Table</h2>
                    <p class="text-center text-color mb-5">Successful strategies require data analysis, creativity and customer focus, taking advantage of the latest technologies to offer excellent services.</p>
                </div>
            </div>
            <div class="row justify-content-center d-grid gap-3">
                <div class="col-3 mx-2 white-box justify-content-center">
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

.green-text{
    font-size: 12px;
    color: var(--secondary-color);
    font-weight: bold;
    margin-bottom: 20px;
}

.backgrounded-text{
    padding: 5px 10px;
    background-color: var(--secondary-color);
    opacity: 0.3;
}
</style>