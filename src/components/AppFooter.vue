<script>
export default {
    
}
</script>
<template>
    <div class="jumbotron">

        <!-- inizio sezione 1 del footer -->
        <div class="container">
                <div class="row_flex">
                    <div class="col_tools">
                        <img src="../assets/img/buy-comics-digital-comics.png" alt=""> 
                        <p>digital comics</p>
                    </div>
                    <div class="col_tools">
                        <img src="../assets/img/buy-comics-merchandise.png" alt="">
                        <p>dc merchandise</p>
                    </div>
                    <div class="col_tools">
                        <img src="../assets/img/buy-comics-subscriptions.png" alt=""> 
                        <p>subscription</p>
                    </div>
                    <div class="col_tools">
                        <img src="../assets/img/buy-comics-shop-locator.png" alt="">
                        <p>comic shop locator</p>
                    </div>
                    <div class="col_tools">
                        <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                        <p>dc power visa</p>
                    </div>
                </div>
        </div>
    
    </div>
    



    <!-- inizio sezione 2 del footer: links footer -->
            
    <div class="jumbotron_links">
        <div class="container_links">
            <div class="row_links_footer">
                <div class="col_links">
                    <h3>DC COMICS</h3>
                    <ul>
                        <li><a href="#">Characters</a></li>
                        <li><a href="#">Comics</a></li>
                        <li><a href="#">Movies</a></li>
                        <li><a href="#">TV</a></li>
                        <li><a href="#">Games</a></li>
                        <li><a href="#">Videos</a></li>
                        <li><a href="#">News</a></li>
                                
                        
                    </ul>
                    <h3>SHOP</h3>
                    <ul>
                    <li><a href="#">Shop DC</a></li>
                    <li><a href="#">Shop DC Collectibles</a></li>
                    </ul>            
                            
                            
                </div>
                <div class="col_links">
                    <h3>DC </h3>
                    <ul>
                        <li><a href="#">Terms of Use</a></li>
                        <li><a href="#">Privacy policy(New)</a></li>
                        <li><a href="#">Ad Choises</a></li>
                        <li><a href="#">Advertising</a></li>
                        <li><a href="#">Jobs</a></li>
                        <li><a href="#">Subsciptions</a></li>
                        <li><a href="#">Talent Workshop</a></li>
                        <li><a href="#">CPSC Certificates</a></li>
                        <li><a href="#">Ratings</a></li>
                        <li><a href="#">Shop Help</a></li>
                        <li><a href="#">Contact Us</a></li>           
                        
                    </ul>

                </div>
                <div class="col_links">
                    <h3>SITES </h3>
                    <ul>
                        <li><a href="#">DC</a></li>
                        <li><a href="#">MAD Magazine</a></li>
                        <li><a href="#">DC Kids</a></li>
                        <li><a href="#">DC Univers</a></li>
                        <li><a href="#">DC Power Vis</a>a</li>
                    </ul>

                </div>
                <div class="col_links">
                    
                </div>
            </div>
        </div>
    </div>

    <div class="jumbotron_button">
        <div class="container_button">
            <div class="row_button">
                <div class="col">
                    <button> 
                        <h2>SIGN-UP NOW!</h2>
                    </button>
                </div>
                <div class="col_logos">
                    <h2 class="follow_us">FOLLOW US</h2>
                    <a href="#"><img src="../assets/img/footer-facebook.png" alt=""></a>
                    <a href="#"><img src="../assets/img/footer-twitter.png" alt=""></a>
                    <a href="#"><img src="../assets/img/footer-youtube.png" alt=""></a>
                    <a href="#"><img src="../assets/img/footer-pinterest.png" alt=""></a>
                    <a href="#"><img src="../assets/img/footer-periscope.png" alt="">></a>
                    

                </div>
            </div>
        </div>

    </div>
    
            
            
               


    
</template >

<style lang="scss" scoped>
    .jumbotron{
        background-color: #0C7CEC;
    

        .container{

            max-width: 1050px;
            margin: 0 auto;
            padding: 20px 0;
        

            .row_flex{
                display: flex;
                justify-content:center;
                align-items: center;

                .col_tools{
                    display: flex;
                    margin-top: 20px;
                    margin-bottom:20px;
                    width: calc(100% / 5);
                    justify-content: center;
                    align-items: center;
                    
                    

                    p{
                        text-transform: uppercase;
                        color: white;
                        padding-left: 15px;
                        font-size: 12px;
                    }

                    img{
                        width: 20%;
                    }

            
                }
            }

        }
    }

    .jumbotron_links{
        background-image: url('../assets/img/footer-bg.jpg');
        background-repeat: no-repeat;
        background-size:cover;

        .container_links{
            max-width: 1180px;
            margin: 0 auto;
            background-image: url('../assets/img/dc-logo-bg.png');
            background-repeat: no-repeat;
            background-position: right center;
            
        
            .row_links_footer{
            display: flex;
            justify-content: start;

                .col_links{
                    margin-right: 30px;
                    margin-top:50px;
                    margin-bottom: 50px;
                }
        
                h3{
                    color: white;
                    margin: 15px 0px;
                
                }
                li{
                    list-style-type: none;
                    margin-bottom: 5px;
                    


                    a{
                        text-decoration: none;
                        color: grey;
                    }

                    &:hover a{
                        color: #0C7CEC;  
                    }
                }
            }
        }

    }

    .jumbotron_button{
        background-color: rgb(67, 61, 61);
        
        .container_button{
            max-width: 1180px;
            margin: 0 auto;


            .row_button{
                display: flex;
                justify-content: space-between;
                align-items: baseline;


                .col_logos{
                    display: flex;
                    align-items: center;
                    gap: 20px;
                }



                button{
                    margin: 50px 0;
                    padding: 20px;
                    background-color: rgb(67, 61, 61) ;
                    color: white;
                    border: 2px solid #0C7CEC;
                    cursor: pointer;


                    &:active{
                    background-color: rgb(44, 40, 40);
                    border: 2px solid #073b70;
                    color: rgb(192, 189, 189);
                    }
                }

                

                .follow_us{
                    color: #0C7CEC;
                    
                }
            }


            
        }
    }
    
    
</style>