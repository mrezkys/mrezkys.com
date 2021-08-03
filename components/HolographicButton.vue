<template>
    <div class="holographic-button-wrapper">
        <button class="holographic-button">
            <button >{{ text }}</button>
        </button>
    </div>
</template>


<style scoped>
    @media (max-width: 575.98px) {
        .holographic-button-wrapper{
            text-align: center !important;
        }
    }

    @media (max-width: 991.98px) {
        .holographic-button-wrapper{
            text-align: center !important;
        }
    }

    .holographic-button-wrapper{
        text-align: left;
    }
    .holographic-button{
        font-family: 'Poppins';
        animation: 1s appears;
        padding: 3px 3px;
        background: conic-gradient(from 176.21deg at 50% 50%, #000000 -24.66deg, #FFFFFF 0.25deg, #000000 50.63deg, #000000 51.97deg, #FFFFFF 88.12deg, #000000 142.5deg, #FFFFFF 196.87deg, #000000 256.87deg, #FFFFFF 300deg, #000000 335.2deg, #000000 335.34deg, #FFFFFF 360.25deg), conic-gradient(from 176.21deg at 50% 50%, #000000 -24.66deg, #FFFFFF 0.25deg, #000000 50.63deg, #000000 51.97deg, #FFFFFF 88.12deg, #000000 142.5deg, #FFFFFF 196.87deg, #000000 256.87deg, #FFFFFF 300deg, #000000 335.2deg, #000000 335.34deg, #FFFFFF 360.25deg), radial-gradient(95.11% 95.11% at 36.64% 4.89%, #2AD0CA 0%, #E1F664 22.92%, #FEB0FE 46.88%, #ABB3FC 68.23%, #5DF7A4 87.5%, #58C4F6 100%);
        background-blend-mode: screen, difference, normal;
        border: none;
    }
    .holographic-button button{
        margin: 0;
        padding: 15px 30px;
        border: none;
        background: black;
        color: white;
        font-size: 16px;
        font-weight: 500;
    }
</style>

<script>
    export default {
        props:{
            text: String,
        }
    }
</script>