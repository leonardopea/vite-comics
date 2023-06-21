<script>
export default {
    
}
</script>
<template>
    <div class="jumbotron">

        <div class="container">
                <div class="row_flex">
                    <div class="col">
                        <!-- <img src="../assets/img/buy-comics-digital-comics.png" alt=""> -->
                        <p>digital comics</p>
                    </div>
                    <div class="col">
                        <!-- <img src="../assets/img/buy-comics-merchandise.png" alt=""> -->
                        <p>dc merchandise</p>
                    </div>
                    <div class="col">
                        <!-- <img src="../assets/img/buy-comics-subscriptions.png" alt=""> -->
                        <p>subscription</p>
                    </div>
                    <div class="col">
                        <!-- <img src="../assets/img/buy-comics-shop-locator.png" alt=""> -->
                        <p>comic shop locator</p>
                    </div>
                    <div class="col">
                        <!-- <img src="../assets/img/buy-dc-power-visa.svg" alt=""> -->
                        <p>dc power visa</p>
                    </div>
                </div>
            </div>
        
    </div>
</template >

<style lang="scss" scoped>
    .jumbotron{
        background-color: #0C7CEC; 

        .container{

            max-width: 980px;
            margin: 0 auto;
        

            .row_flex{
                display: flex;
                justify-content:center;
                align-items: center;

                .col{
                    display: flex;
                    margin-top: 20px;
                    margin-bottom:20px;
                    width: calc(100% / 5);
                    

                    p{
                        text-transform: uppercase;
                        color: white;
                    }

                    img{
                        width: 20%;
                    }
                }
            }

        }
    }
</style>