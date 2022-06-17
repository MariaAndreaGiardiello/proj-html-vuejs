<template>
    <section class="section-background d-flex align-items-center">
        <div class="container-sm justify-content-center ">
            <div class="row justify-content-center d-grid gap-3">
                <div class="col-12"><h6 class="green-text">OUR BUSINESS AREAS</h6></div>
                <div class="col-12"><h2 class="section-title">Excellence in <span class="backgrounded-text">Services</span></h2></div>
                <div class="row justify-content-between mb-5 align-items-center">
                    <div class="col-8 description">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Eveniet nobis blanditiis, aliquam fuga quos commodi porro laboriosam nostrum beatae quam laudantium numquam odit. Vel enim adipisci nobis harum numquam suscipit.</div>
                    <div class="col-2"><button type="button" class="transparent-button">SEE ALL</button></div>
                </div>
                <div class="col-3 mx-2 gray-box">
                    <div class="img-circle"><img class="img-fluid" src="src/assets/img/users-icon.png" alt=""></div>
                    <h5 class="card-title">Human Capital</h5>
                    <p class="description">Lorem ipsum dolor sit amet consectetur adipisicing elit. Sint saepe quibusdam in similique at doloremque</p>
                    <div class="col-12"><button type="button" class="transparent-button">READ MORE</button></div>
                </div>
                <div class="col-3 mx-2 gray-box">
                    <div class="img-circle"><img class="img-fluid" src="src/assets/img/users-icon.png" alt=""></div>
                    <h5 class="card-title">Human Capital</h5>
                    <p class="description">Lorem ipsum dolor sit amet consectetur adipisicing elit. Sint saepe quibusdam in similique at doloremque</p>
                    <div class="col-12"><button type="button" class="transparent-button">READ MORE</button></div>
                </div><div class="col-3 mx-2 gray-box">
                    <div class="img-circle"><img class="img-fluid" src="src/assets/img/users-icon.png" alt=""></div>
                    <h5 class="card-title">Human Capital</h5>
                    <p class="description">Lorem ipsum dolor sit amet consectetur adipisicing elit. Sint saepe quibusdam in similique at doloremque</p>
                    <div class="col-12"><button type="button" class="transparent-button">READ MORE</button></div>
                </div><div class="col-3 mx-2 gray-box">
                    <div class="img-circle"><img class="img-fluid" src="src/assets/img/users-icon.png" alt=""></div>
                    <h5 class="card-title">Human Capital</h5>
                    <p class="description">Lorem ipsum dolor sit amet consectetur adipisicing elit. Sint saepe quibusdam in similique at doloremque</p>
                    <div class="col-12"><button type="button" class="transparent-button">READ MORE</button></div>
                </div><div class="col-3 mx-2 gray-box">
                    <div class="img-circle"><img class="img-fluid" src="src/assets/img/users-icon.png" alt=""></div>
                    <h5 class="card-title">Human Capital</h5>
                    <p class="description">Lorem ipsum dolor sit amet consectetur adipisicing elit. Sint saepe quibusdam in similique at doloremque</p>
                    <div class="col-12"><button type="button" class="transparent-button">READ MORE</button></div>
                </div><div class="col-3 mx-2 gray-box">
                    <div class="img-circle"><img class="img-fluid" src="src/assets/img/users-icon.png" alt=""></div>
                    <h5 class="card-title">Human Capital</h5>
                    <p class="description">Lorem ipsum dolor sit amet consectetur adipisicing elit. Sint saepe quibusdam in similique at doloremque</p>
                    <div class="col-12"><button type="button" class="transparent-button">READ MORE</button></div>
                </div>
               
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'DarkCardSection'
}
</script>

<style lang="scss" scoped>
.section-background {
    background-color: black;
    padding: 50px 0;
}

.gray-box{
    padding: 20px;
    background-color: rgb(25, 25, 30);
    border-radius: 15px;
    margin: 10px;
    color: white;
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

.section-title{
    color: white;
    font-weight: bold;
}

.description{
    color: var(--font-color);
    font-size: 12px;
    margin-top: 20px;
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
    color: white;
}
</style>