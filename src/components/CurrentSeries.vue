<template>
  <div>
        <div class="container">
            <div class="container-item">
                <ul>
                    <li v-for= "(item, index) in film" :key="index" >
                        <img :src="item.thumb" alt="">
                        <p> {{ item.series}}</p>
                    </li>
                </ul>
          </div>
        </div>
    </div>
</template>

<script>
export default {
    name:"CurrentSeries",
    props:{
        film: Array //tipologia di dato che passiamo
    },
    
} 
</script> 

<style scoped lang="scss">
@import "../style/common.scss";
@import "../style/variable.scss";

.container{
    background-color: black;
    height: 400px;

    .container-item{
        border:1px solid red;
        width: 80%;
        margin: 0 auto;
        
        ul{
            display:flex;
            flex-wrap:wrap;
        
            li{
                width:20%;
                color:white;
                padding:1rem 0;

                img{
                  width: calc(100% / 4);
                }
        }
        }
    }

}

</style>