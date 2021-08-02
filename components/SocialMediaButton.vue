<template>
    <div class="social-media-button-wrapper">
        <div class="row">
            <div class="social-media-button">
                <a href="https://github.com/mrezkys">
                    <img src="~/assets/icons/logo-github.svg" alt="">
                </a>
            </div>
            <div class="social-media-button">
                <a href="https://github.com/mrezkys">
                    <img src="~/assets/icons/logo-facebook.svg" alt="">
                </a>
            </div>
            <div class="social-media-button">
                <a href="https://github.com/mrezkys">
                    <img src="~/assets/icons/logo-medium.svg" alt="">
                </a>
            </div>
            <div class="social-media-button">
                <a href="https://github.com/mrezkys">
                    <img src="~/assets/icons/logo-linkedin.svg" alt="">
                </a>
            </div>
            <div class="social-media-button">
                <a href="https://github.com/mrezkys">
                    <img src="~/assets/icons/logo-instagram.svg" alt="">
                </a>
            </div>
            <div class="social-media-button">
                <a href="https://github.com/mrezkys">
                    <img src="~/assets/icons/logo-whatsapp.svg" alt="">
                </a>
            </div>
        </div>
    </div>
</template>

<style scoped>
    .social-media-button-wrapper .social-media-button{
        margin-top: 10px;
        margin-right: 25px;
    }

  @media (max-width: 575.98px) {
    .social-media-button-wrapper .row{
        justify-content: center;
    }

    .social-media-button-wrapper .row .social-media-button{
        margin-top: 10px;
        margin-right: 13px !important;
        margin-left: 13px !important;
    }

    .social-media-button-wrapper .row .social-media-button img{
        height: 32px;
    }

  }

  @media (min-width: 575.98px ) and (max-width: 991.98px) {
    .social-media-button-wrapper .social-media-button{
        margin-top: 10px;
        margin-right: 13px;
        margin-left: 13px;
    }
    .social-media-button-wrapper .row{
        justify-content: center;
    }
  }
</style>