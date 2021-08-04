<template><!-- this is mandatory when using row -->
    <div class="col-lg-6 col-12 achievement-box mb-4">
        <div class="col-12 content  d-flex flex-column justify-content-center">
            <div class="row">
                <img class="trophy-icon align-self-center" src="~assets/icons/medal-icon.svg" alt="">
                <div class="col">
                    <p class="position">{{ year }}</p>
                    <h4 class="title">{{ title }}</h4>
                    <p class="by">by {{ by }}</p>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
    .achievement-box .content{
        height: 230px;
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
        font-size: 18px;
        margin: 0;
        margin-bottom: 8px;
    }

    .achievement-box .content .by{
        font-family: 'Roboto';
        font-size: 14px;
        margin: 0;
        margin-top: 14px;
    }

    .achievement-box .content .title{
        font-family: 'Poppins';
        font-weight: 600;
        line-height: 150%;
    }

    @media (max-width: 575.98px) {
        .achievement-box .content{
            height: 150px !important;
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
        }

        .achievement-box .content .title{
            line-height: 150%;
            font-size: 16px;
            margin: 0;
        }

        .achievement-box .content .by{
            
            font-size: 12px;
            margin: 0;
        }
    }
    
</style>

<script>
    export default {
        props:{
            year: String,
            by: String,
            title: String,
        }
    }
</script>