<script>
export default {
    props:{
        image: String,
        subtitle: String,
    }
}
</script>


<template>
    <div class="cards">
        <img :src="image">
        <h1>{{ subtitle }}</h1>
    </div>
</template>



<style lang="scss" scoped >

.cards{
            width: calc(100% / 6 - 20px );
            margin: 10px;
            
        }


    img{
        width: 100%;
        height: 80%;
    }

    h1{
            color: white;
            font-size: 15px;
        }


       
</style>