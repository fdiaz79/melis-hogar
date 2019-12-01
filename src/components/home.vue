<template>
    <div id="home">
        <div class="row">
            <div class="col-12 col-md-2"></div>
            <div class="col-12 col-md-8">
                <b-carousel id="carousel-inicio center" v-model="slide" :interval="3000" controls indicators img-width="512" img-height="240">
                    <b-carousel-slide>
                        <template v-slot:img>
                            <img class="d-block img-fluid w-100 center" width="512" height="240" src="/images/inicio1.jpg" alt="hogar1">
                        </template>
                    </b-carousel-slide>
                    <b-carousel-slide>
                        <template v-slot:img>
                            <img class="d-block img-fluid w-100 center" width="512" height="240" src="/images/inicio2.jpg" alt="hogar1">
                        </template>
                    </b-carousel-slide>
                    <b-carousel-slide>
                        <template v-slot:img>
                            <img class="d-block img-fluid w-100 center" width="512" height="240" src="/images/inicio3.jpg" alt="hogar1">
                        </template>
                    </b-carousel-slide>
                    <b-carousel-slide>
                        <template v-slot:img>
                            <img class="d-block img-fluid w-100 center" width="512" height="240" src="/images/inicio4.jpg" alt="hogar1">
                        </template>
                    </b-carousel-slide>
                </b-carousel>
            </div>
            <div class="col-12 col-md-2"></div>

        </div>
        <div class="row">
            <div class="col-12 col-md-1"></div>
            <div class="col-12 col-md-10 home-container">
                <h1 class="text-center">Algun titulo que resalte la vision del hogar</h1>
                <p class="text-justify">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Explicabo rerum enim adipisci maxime quia iusto, facere quaerat deleniti id, dolorem nemo, repellendus hic harum dolores. Doloribus repellendus totam adipisci nihil.</p>
            </div>
            <div class="col-12 col-md-1"></div>
            
        </div>
        
        
    </div>
    
</template>

<script>
    export default {
        data() {
            return {
                slide: 0,
                sliding: null
            }
        },
        // methods: {
        //     onSlideStart(slide) {
        //         this.sliding = true
        //     },
        //     onSlideEnd(slide) {
        //         this.sliding = false
        //     }
        // }
        
    }
</script>

<style scoped>
    #home {
        margin: 2%;
        padding: 1%;
    }

    #carousel-inicio {
        width: 512px;
        height: 240px;
    }
    .center {
        margin: auto;
        max-height: 473px;
        border: 2px solid #dd4c39;
    }
    .home-container {
        margin-top: 2%;
    }
    
</style>