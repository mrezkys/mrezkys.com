<template>
    <div class="col-lg-3 col-6 experience-box mb-4 mb-lg-0">
        <div class="col-12 box-1 d-flex flex-column justify-content-end" >
            <div class="content">
                <p class="year-count">{{yearCount}}</p>
                <h5 class="role">{{ role }}</h5>
                <p class="discover">Discover more
                    <svg width="11" height="10" viewBox="0 0 11 10" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path d="M8.56274 4.88578H2.31274" stroke="white" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                    <path d="M6.04199 2.37558L8.56283 4.88558L6.04199 7.396" stroke="white" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                    </svg>
                </p>
            </div>
            <div class="stacked-bg">
                <img :src="iconPath" alt="">
            </div>
        </div>
    </div>
    
</template>

<style scoped>
    .experience-box{
        background-color: transparent;
        cursor: pointer;
    }
    .experience-box .box-1{
        padding: 25px 25px;
        color: white !important;
        height: 240px !important;
        background: #2C2C2C;
    }

    .experience-box .box-1 .content{
        z-index: 2;
    }

    .experience-box .box-1 .content .year-count{
        font-family: 'Roboto';
        font-size: 16px;
        font-weight: 500;
        padding: 0;
        margin: 0;
        margin-bottom: 6px;
    }

    .experience-box .box-1 .content .role{
        font-family: 'Poppins';
        font-size: 22px;
        font-weight: 700;
        padding: 0;
        margin: 0;
        margin-bottom: 10px;
    }

    .experience-box .box-1 .content .discover{
        font-family: 'Roboto';
        font-size: 16px;
        font-weight: 300;
        padding: 0;
        margin: 0;
    }

    
    .stacked-bg{
        z-index: 0;
        position: absolute;
        bottom: 0;
        right: 0;
    }

    .stacked-bg img{
        height: 200px;
        opacity: 0.15;
    }

    @media (max-width: 575.98px) {
        .experience-box{
            padding: 0 6px;
        }

        .experience-box .box-1{
            padding: 10px 15px;
            height: 150px !important;
        }

        .stacked-bg img{
            height: 120px;
            opacity: 0.15;
        }
        .experience-box .box-1 .content .year-count{
            font-size: 12px !important;
            font-weight: 400;
        }

        .experience-box .box-1 .content .role{
            font-size: 16px !important;
            font-weight: 600;
            margin-bottom: 8px;
        }

        .experience-box .box-1 .content .discover{
            font-size: 12px !important;
            font-weight: 400;
        }
    }

    @media (min-width: 575.98px ) and (max-width: 991.98px) {

    }
</style>

<script>
export default {
    props:{
        yearCount: String,
        role: String,
        iconPath: {
            type: String,
            default: ''
        }
    }
}
</script>