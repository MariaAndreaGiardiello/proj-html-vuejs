<template>
  <section class="section-background d-flex align-items-center">
        <div class="container-sm justify-content-center ">
            <div class="row">
                <div class="col-12"><h6 class="green-text">OUR BUSINESS AREAS</h6></div>
                <div class="col-12"><h2 class="section-title">Excellence in <span class="backgrounded-text">Services</span></h2></div>
                <div class="row justify-content-between mb-5 align-items-center">
                    <div class="col-8 description">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Eveniet nobis blanditiis, aliquam fuga quos commodi porro laboriosam nostrum beatae quam laudantium numquam odit. Vel enim adipisci nobis harum numquam suscipit.</div>
                    <div class="col-2"><button type="button" class="green-button">SEE ALL</button></div>
                </div>
            </div>
            <div class="row justify-content-center d-grid gap-3">
                <div class="col-3 mx-2 white-box img-bg-1">
                </div>
                <div class="col-3 mx-2 white-box img-bg-2">
                </div>
                <div class="col-3 mx-2 white-box img-bg-3">
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
.section-background {
    background-color: whitesmoke;
    padding: 50px 0;
}

.white-box{
    padding: 20px;
    border-radius: 15px;
    margin: 10px;
    color: white;
    height: 250px;
    width: 350px;
}

.img-bg-1{
    background-image: url(../../assets/img/news-1.jpg);
    background-position: center;
    background-size: cover;
    background-repeat: no-repeat;
}

.img-bg-2{
    background-image: url(../../assets/img/news-2.jpg);
    background-position: center;
    background-size: cover;
    background-repeat: no-repeat;
}

.img-bg-3{
    background-image: url(../../assets/img/news-3.jpg);
    background-position: center;
    background-size: cover;
    background-repeat: no-repeat;
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
    color: #038483;
}

.section-title{
    color: black;
    font-weight: bold;
}

.description{
    color: var(--font-color);
    font-size: 12px;
    margin-top: 20px;
}

.img-bg-1::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: rgba(0,0,0,0.5);
    border-radius: 10px;
}

.img-bg-2::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: rgba(0,0,0,0.5);
    border-radius: 10px;
}

.img-bg-3::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: rgba(0,0,0,0.5);
    border-radius: 10px;
}
</style>