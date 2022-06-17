<template>
  <section class="container-fluid">
    <div class="row">
        <div class="col-6 d-flex justify-content-end">
            <div class="col-8 about-text">
                <div class="company">
                    <h6 class="about-network-text">ABOUT THE NETWORK</h6>
                    <h2 class="about-bold"><span class="backgrounded-text">The</span> Company</h2>
                    <p class="description">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Illum cupiditate delectus lorem lorem lorem lorem lorem lorem</p>
                </div>
                <div class="row">
                    <div class="col-6 tradition">
                        <h5 class="d-flex about-bold"> <div class="mx-2 icon-circle align-items-center"></div> Tradition</h5>
                        <p class="description">Lorem ipsum dolor sit ametLorem ipsum dolor sit ametLorem ipsum dolor sit amet  </p>
                    </div>
                    <div class="col-6 tradition">
                        <h5 class="d-flex about-bold"> <div class="mx-2 icon-circle align-items-center"></div> Tradition</h5>
                        <p class="description">Lorem ipsum dolor sit ametLorem ipsum dolor sit ametLorem ipsum dolor sit amet  </p>
                    </div>
                    <div class="col-6 tradition">
                        <h5 class="d-flex about-bold"> <div class="mx-2 icon-circle align-items-center"></div> Tradition</h5>
                        <p class="description">Lorem ipsum dolor sit ametLorem ipsum dolor sit ametLorem ipsum dolor sit amet  </p>
                    </div>
                    <div class="col-6 tradition">
                        <h5 class="d-flex about-bold"> <div class="mx-2 icon-circle align-items-center"></div> Tradition</h5>
                        <p class="description">Lorem ipsum dolor sit ametLorem ipsum dolor sit ametLorem ipsum dolor sit amet  </p>
                    </div>
                </div>
            </div>
        </div>
        <div class="col-6">
            <img class="img-fluid about-img" src="src/assets/img/hero-image.png" alt="">
        </div>
    </div>
  </section>
</template>

<script>
export default {
    name: 'AboutCompanySection'
}
</script>

<style lang="scss" scoped>
.about-img{
    width: 100%;
    height: 100%;
}

.about-text{
    margin: 80px 0;
}

.about-network-text {
    font-size: 12px;
    color: var(--secondary-color);
    font-weight: bold;
    margin-bottom: 20px;
}

.backgrounded-text{
    padding: 5px 10px;
    background-color: var(--secondary-color);
    opacity: 0.5;
    font-weight: bold;
    color: #038483;
}

.about-bold {
    font-weight: bold;
}

.description{
    color: var(--font-color);
    font-size: 12px;
    margin-top: 20px;
}

.company {
    line-height: 20px;
    margin-bottom: 50px;
}

.icon-circle {
    width: 20px;
    height: 20px;
    border-radius: 100%;
    background-color: lightgray;
    margin-bottom: 15px;
    opacity: 0.7;
}

</style>