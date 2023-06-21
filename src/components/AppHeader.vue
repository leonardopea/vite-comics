<script>
export default {
    data(){
        return{
            links:[
                {
                    label: 'characters',
                    link: '#',
                    active: false,
                },
                {
                    label: 'comics',
                    link: '#',
                    active: false,
                },
                {
                    label: 'movies',
                    link: '#',
                    active: false,
                },
                {
                    label: 'tv',
                    link: '#',
                    active: false,
                },
                {
                    label: 'games',
                    link: '#',
                    active: false,
                },
                {
                    label: 'collectibles',
                    link: '#',
                    active: false,
                },
                {
                    label: 'videos',
                    link: '#',
                    active: false,
                },
                {
                    label: 'fans',
                    link: '#',
                    active: false,
                },
                {
                    label: 'news',
                    link: '#',
                    active: false,
                },
                {
                    label: 'shop',
                    link: '#',
                    active: false,
                },
            ]
        }
    }
    
}
</script>
<template>
    <div>
        <div class="jumbotron">
            <img src="../../public/dc-logo.png" alt="">
            <ul>
                <li v-for="(link, index) in links" :key="index">
                    <a :class="(link.active ? 'active' : '')" :href="link.link">{{ link.label }}</a>
                </li>
            </ul>
        </div>
    </div>
</template>

<style lang="scss" scoped>


$dc_color:#0C7CEC;   // creo variabile per colore 


    .jumbotron{
        display: flex;
        justify-content: space-between;
        align-items: center;
        max-width: 1180px;
        margin: 0 auto;
        
        
    }

    ul,li{
        display: inline-block;
        li{
            margin-right: 20px;
            

           

        }
    
    }


</style>