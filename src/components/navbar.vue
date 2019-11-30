<template>
    <div class="text-center" >
        <hr>
        <b-navbar toggleable="lg" >
            <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
            <b-collapse id="nav-collapse" is-nav>
                <b-navbar-nav class="center">                    
                    <router-link to="/">| INICIO |</router-link> 
                    <router-link to="/aboutUs">| NOSOTROS |</router-link> 
                    <router-link to="/gallery">| GALERIA |</router-link> 
                    <router-link to="/contactUs">| CONTACTENOS |</router-link>                    
                </b-navbar-nav>
            </b-collapse>
        </b-navbar>
        <hr>
    </div>
    




    <!-- <div id="nav" class="text-center" >
        <hr>
        <router-link to="/">INICIO</router-link> |
        <router-link to="/aboutUs">NOSOTROS</router-link> |
        <router-link to="/gallery">GALERIA</router-link> |
        <router-link to="/contactUs">CONTACTENOS</router-link>
        <hr>
    </div> -->
</template>

<script>
    export default {
        
    }
</script>

<style scoped lang="scss" >

    hr {
        margin: 0.1rem;
        color: #1abbb2;
    }
    .center {
        margin: auto;
    }
    #nav-collapse {
        color: #52c6cd;
        font-size: 1.2em;
        letter-spacing: .9em;
        padding: 0px;

        a {
            font-weight: 400;
            letter-spacing: 0.1em;
            color: #1abbb2;
                &.router-link-exact-active {
                    color: #81d742;
                    font-weight: 600;
                }
        }        
    }
</style>