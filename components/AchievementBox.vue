<template><!-- this is mandatory when using row -->
    <div class="col-lg-6 col-12 achievement-box mb-4">
        <div class="col-12 content  d-flex flex-column justify-content-center">
            <div class="row">
                <img class="trophy-icon align-self-center" src="~assets/icons/trophy.svg" alt="">
                <div class="col">
                    <p class="position">{{ position }} Position | {{ grade }}</p>
                    <h4 class="title">{{ title }}</h4>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
    .achievement-box .content{
        height: 204px;
        background-color: #2C2C2C;
        padding: 0 24px;
    }

    .achievement-box .content .trophy-icon{
        width: 110px;
        height: auto;
        margin: 0 32px;
    }

    .achievement-box .content .position{
        font-family: 'Roboto';
        font-size: 20px;
        margin: 0;
        margin-bottom: 8px;
    }

    .achievement-box .content .title{
        font-family: 'Poppins';
        font-weight: 600;
        line-height: 150%;
    }

    @media (max-width: 575.98px) {
        .achievement-box .content{
            height: 110px;
            background-color: #2C2C2C;
        }


        .achievement-box .content .trophy-icon{
            width: 55px;
            height: 55px;
            margin: 0 10px;
        }

        .achievement-box .content .position{
            font-size: 12px;
            margin: 0;
            margin-bottom: 8px;
        }

        .achievement-box .content .title{
            line-height: 150%;
            font-size: 16px;
        }
    }
    
</style>

<script>
    export default {
        props:{
            position: String,
            title: String,
            grade: String
        }
    }
</script>