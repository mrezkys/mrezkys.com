<template>
    <div class="featured-text-wrapper">
        <p class="featured-text">{{text}}</p>
        <div class="stacked-bg" :style="getStyle"></div>
    </div>
</template>

<style scoped>
    .featured-text-wrapper{
        margin-bottom: 25px;
    }
    .featured-text{
        font-family: 'Poppins';
        font-weight: 500;
        font-size: 18px;
    }
    .stacked-bg{
        margin-top: -60px;
        z-index: -1;
        width: 100%;
        height: 50px;
    }

  @media (max-width: 575.98px) {
    .featured-text{
        text-align: center;
        font-size: 14px;
        font-weight: 400;
    }
    

  }

  @media (min-width: 575.98px ) and (max-width: 991.98px) {
    .featured-text-wrapper{
        padding: 0 10%;
    }
    .featured-text{
        padding: 0 20%;
        text-align: center;
    }
  }
</style>

<script>
    export default {
        props:{
            text: String,
            styling: Object,
        },
        computed:{
            getStyle(){
                return this.styling;
            }
        }
    }
</script>