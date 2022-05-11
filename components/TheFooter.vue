<template>
    <div class="rodape">
        <div class="info-footer">
            
            <div class="contact-us order-2 order-sm-1">

                <h4>CONTACT US</h4>
                <br>
                <p>
                    <v-icon>
                       mdi-map-marker  
                    </v-icon>
                    <a href="#"> Location</a> 
                </p>

                <p>
                    <v-icon>
                        mdi-email
                    </v-icon>                    
                    <a href="#"> rustic21@gmail.com</a>
                </p>
            </div>

            <div class="about-us order-1 order-sm-2"> 
                <h4>ABOUT US</h4>
                <br>
                <p></p>
                <div class="icon-links">
                    <a class="mx-2" href=""><v-icon>mdi-instagram</v-icon></a>
                    <a class="mx-2" href=""><v-icon>mdi-facebook</v-icon></a>
                    <a class="mx-2" href=""><v-icon>mdi-twitter</v-icon></a>
                </div>
            </div>

            <div class="opening-hours order-3">
                <h4>Opening Hours</h4>
                <br>
                <p>Everyday</p>
                <p>10.00 Am - 10.00 Pm</p>
            </div>

        </div>

        <div class="rights-footer">
            <p>
                <v-icon>
                    mdi-copyright
                </v-icon>
                2022 All Rights Reserved By Rustic21
            </p>
        </div>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>
.rodape {
    width: 100%;
    height: 300px !important;
    background: linear-gradient(90deg, rgba(0,0,0,1) 0%, rgba(11,11,11,1) 59%, rgba(33,33,33,1) 85%);

    color: white;
}

 a, p { 
    color: white;
    text-decoration: none;
    font-size: 0.8rem;         
}

.info-footer { 
    height: 200px;
    display: flex;
    flex-wrap: nowrap ;
    align-content: space-around;
    justify-content: space-evenly;

    .contact-us, .about-us, .opening-hours {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        width: 250px;     
        text-align: center; 

        .icon-links{
            display: flex;
            flex-direction: row;


        }
    }
}

.rights-footer {
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    border: white;
}

@media screen and (max-width: 600px){

    .rodape {
        height: 600px !important;
        color: white;
    }

    .info-footer { 
        height: 500px;
        flex-direction: column;
        align-items: center;
        justify-content: space-evenly;

    }    
}
</style>