<template>
    <div id="app-footer">
        <div class="row" id="footer-content">
            <div class="col-12 col-sm-6 col-md-4">
                
                    <div class="text-center" id="logo-div">INSERT LOGO HERE</div>
                    <div class="text-center" id="social-media">
                        <font-awesome-icon class="social-icon" icon="user" />
                        <font-awesome-icon class="social-icon" icon="envelope" />
                        <font-awesome-icon class="social-icon" :icon="{ prefix: 'fab', iconName: 'twitter' }"/>
                        <font-awesome-icon class="social-icon" :icon="{ prefix: 'fab', iconName: 'facebook' }"/>
                        <font-awesome-icon class="social-icon" :icon="{ prefix: 'fab', iconName: 'instagram' }"/>
                    </div>
                

            </div>
            <div class="col-12 col-sm-6 col-md-4 offset-md-2 col-lg-3 offset-lg-3 contactenos-div">
                <h3>Contactenos</h3>
                <p>Direccion: Cra 38A #61-09 </p>
                <p>Telefono: 57-1-6310678 </p>
                <p>Email: hogarm&m@email.com</p>
                <p>Bogota, Colombia</p>                
            </div>
        </div>
        <div class="row">
            <div class="text-center" id="footer-text">
                <p> ©2019 Hogar Geriátrico Melis y Mao. </p>
                <p id="copyright"> <i>By Fabian Diaz</i> </p>
            </div>
        </div>
    </div>
    
</template>

<script>
    export default {
        
    }
</script>

<style scoped>
    #app-footer {
        background-color:#1abbb2;
        color: white;
        font-size: 1.2em;
    }
    #footer-content {
        padding: 2%;
    }
    #footer-text {
        margin: auto;
        padding: 2%;
        font-weight: 600;
    }
    #copyright {
        font-size: 0.8em;
        font-weight: 400;
    }
    #logo-div {
        margin-top: 4%;
        display: block;
        padding: 2%;
    }
    #social-media {
        margin-top: 3%;
        font-size: 1.5em;
    }
    .social-icon {
        margin-left: 1em;
        color: #dd4c39
    }
    .contactenos-div {        
        padding: 2% 4%;
    }
  
    

</style>