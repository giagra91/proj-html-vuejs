<template>
    <footer>
        <div class="top-footer my-dark-bg mt-5 py-5">
            
            <div class="central-container">
                <div class="row">
                    <div class="col-3 py-2 my-text-color">
                        <img class="w-50" :src="require(`../assets/img/logo.svg`)" alt="">
                        <p class="my-text my-text-color my-3">
                            Lorem ipsum dolor sit amet consectetur adipisicing elit. 
                        </p>
                        <p class="my-text my-text-color">
                            <span><font-awesome-icon icon="fa-solid fa-phone" /></span>
                            Lorem ipsum dolor sit 
                        </p>
                        <p class="my-text my-text-color">
                            <font-awesome-icon icon="fa-solid fa-envelope" />
                            Lorem ipsum dolor sit 
                        </p>
                        <p class="my-text my-text-color">
                            <font-awesome-icon icon="fa-solid fa-location-dot" />
                            Lorem ipsum dolor sit 
                        </p>
                        <a class="text-uppercase my-text text-white my-border-green px-3 py-2 text-decoration-none rounded-3" href="#">Get in touch</a>
                    </div>
                    <div class="col-3">
                        <div class="my-text-color p-4 my-light-dark-bg rounded-card">
                            <h5 class="text-white fw-bold">About</h5>
                            <ul class="list-unstyled">
                                <li class="my-text">
                                    <span class="me-1">
                                        <font-awesome-icon icon="fa-solid fa-chevron-right" />
                                    </span>
                                    Prova
                                </li>
                            </ul>
                        </div>
                    </div>
                    <div class="col-3">
                        <div class="my-text-color p-4 my-light-dark-bg rounded-card">
                            <h5 class="text-white fw-bold">About</h5>
                            <ul class="list-unstyled">
                                <li class="my-text">
                                    <span class="me-1">
                                        <font-awesome-icon icon="fa-solid fa-chevron-right" />
                                    </span>
                                    Prova
                                </li>
                            </ul>
                        </div>
                    </div>
                    <div class="col-3">
                        <div class="my-text-color p-4 my-light-dark-bg rounded-card">
                            <h5 class="text-white fw-bold">About</h5>
                            <ul class="list-unstyled">
                                <li class="my-text">
                                    <span class="me-1">
                                        <font-awesome-icon icon="fa-solid fa-chevron-right" />
                                    </span>
                                    Prova
                                </li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <BottomFooter />
    </footer>
</template>

<script>
import BottomFooter from "./BottomFooter.vue"

export default {
    name: "HomeFooter",
    components:{
        BottomFooter,
    },

}
</script>

<style lang="scss" scoped>
div.top-footer{
    height: 60vh;
}
</style>