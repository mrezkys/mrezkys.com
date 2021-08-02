<template>
  <div>
    <Navbar/>
    <div class="container-lg section-1 pt-5 pb-5 mt-3">
      <div class="row">
        <div class="col-lg-7 col-12 welcome-box">
          <h1 class="title">Hello, I’m mrezkys.</h1>
          <h3 class="subtitle">Graphic Designer & Web Developer</h3>
          <p class="description">Hello , my name is Muhammad Rezky Sulihin. But, in the internet, i usually using “ mrezkys “ for my nickname. I’m 17 y.o . aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure .</p>
          <HolographicButton text="More About Me"/>
          <SocialMediaButton style="margin-top: 40px"/>
        </div>
        <div class="offset-lg-1 col-lg-4 col-12 promo-box">
          <h1 class="title">I believe in Dreams,<br> and I’ll make your<br> Dreams comes true.</h1>
          <div class="secondary-title-box">
            <div class="row align-items-center">
              <div class="col-1 p-0"><hr style="background-color: white; height: 1px;"></div>
              <div class="col-10 p-0">
                <h1 class="header">I believe in Dreams,<br> and I’ll make your Dreams <br>comes true.</h1>
              </div>
              <div class="col-1 p-0"><hr style="background-color: white; height: 1px;"></div>
            </div>
          </div>
          <FeaturedText text="I will help you to make your dream Website for your personal website or your company website." :styling="{ backgroundColor: '#464646' }"/>
          <FeaturedText text="I will help you to make Design or Illustration for your Bussiness." :styling="{ backgroundColor: '#363636' }" />
          <HireButton style="margin-top: 45px"/>
        </div>
      </div>
    </div>
    <div class="container-lg section-2 pt-3 pb-3 pt-lg-5 pb-lg-5 mt-lg-3">
      <div class="row">
        <div class="offset-lg-1 col-lg-4 col-12 secondary-image-box">
          <img src="~assets/images/me.jpg" class="img-fluid" alt="">
        </div>
        <div class="col-lg-7 col-12 align-self-center about-box mt-sm-3">
          <p class="description">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.</p>
          <br>
          <p class="description">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.</p>
        </div>
        <div class="offset-lg-1 col-lg-4 col-12 primary-image-box">
          <img src="~assets/images/me.jpg" class="img-fluid" alt="">
        </div>
      </div>
    </div>
    <div class="container-lg section-3 pt-1 pb-3 pt-lg-5 pb-lg-3 mt-lg-2">
      <div class="experience-box-wrapper">
        <div class="row align-items-center header">
          <h1 class="experience-count mr-5">3+</h1>
          <p class="title"><br> total <br> years of <br> experience</p>
        </div>
        <div class="row mt-3">
          <HolographicExperienceBox role="Graphic Designer" yearCount="3 Years" :iconPath="require('~/assets/icons/3.svg')"/>
          <ExperienceBox role="Web Developer" yearCount="1 year" :iconPath="require('~/assets/icons/1.svg')"/>
          <ExperienceBox role="Flutter Developer" yearCount="2 Month" :iconPath="require('~/assets/icons/2.svg')"/>
          <ExperienceBox role="UI/UX Designer" yearCount="3 Month" :iconPath="require('~/assets/icons/3.svg')"/>
        </div>
      </div>
    </div>
    <div class="container-lg section-4 pt-1 pb-3 pt-lg-5 pb-lg-3 mt-lg-3">
      <div class="achievement-box-wrapper">
        <div class="row align-items-end header justify-content-between">
          <div class="row align-items-center">            
            <h1 class="achievement-count mr-5">15+</h1>
            <p class="title"><br> total <br> awards & <br> achievements</p>
          </div>
          <NuxtLink to="/" class="see-all">
          <p style="color: white">Discover more
                    <svg width="11" height="10" viewBox="0 0 11 10" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path d="M8.56274 4.88578H2.31274" stroke="white" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                    <path d="M6.04199 2.37558L8.56283 4.88558L6.04199 7.396" stroke="white" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                    </svg>
          </p>
          </NuxtLink>
        </div>
        <div class="row mt-3">
          <div class="col-lg-6">
            <div class="col-12" style="height: 100px; background: grey"></div>
          </div>
          <div class="col-lg-6">
            <div class="col-12" style="height: 100px; background: grey"></div>
          </div>
          <div class="col-lg-6">
            <div class="col-12" style="height: 100px; background: grey"></div>
          </div>
          <div class="col-lg-6">
            <div class="col-12" style="height: 100px; background: grey"></div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  head(){
    return {
      title: 'mrezkys',
      meta: [{
        hid: 'description',
        name: 'description',
        content: 'best place'
      }]
    }
  }
}
</script>
<style>
  body{
    background-color: black;
    color: white;
    margin: 0px;
    padding: 0px;
  }

  .section-1{
    width: 100%;
  }

  .section-1 .welcome-box .title{
    font-weight: 700;
    font-size: 24px;
    margin-bottom: 14px;
  }

  .section-1 .welcome-box .subtitle{
    font-weight: 700;
    font-size: 22px;
    margin-bottom: 30px;
  }

  .section-1 .welcome-box .description{
    color: #ffffff;
    line-height: 150/100;
    font-weight: 400;
    font-size: 18px;
    margin-bottom: 35px;
  }

  .section-1 .promo-box .title{
    font-size: 24px;
    font-weight: 700;
    line-height: 150%;
    margin-bottom: 20px;
  }

  .section-1 .promo-box .secondary-title-box{
    display: none;
  }

  .section-2 .about-box .description{
    font-size: 18px;
    line-height: 150%;
  }

  .section-2 .secondary-image-box{
    display: none;
  }

  .section-3 .experience-box-wrapper .header .title{
    font-size: 18px;
    line-height: 120%;
  }
  .section-3 .experience-box-wrapper .header .experience-count{
    font-size: 130px !important;
    font-weight: 700;
  } 

  .section-4 .achievement-box-wrapper .header .achievement-count{
    font-size: 130px !important;
    font-weight: 700;
  }

  .section-4 .achievement-box-wrapper .header .title{
    font-size: 18px;
    line-height: 120%;
  }

  .section-4 .achievement-box-wrapper .header .see-all{
    color: white;
  }
    


  @media (max-width: 575.98px) {
    .section-1 .welcome-box{
      padding: 0 20px !important;
    }
    .section-1 .welcome-box .title{
      font-size: 22px !important;
      text-align: center;
    }

    .section-1 .welcome-box .subtitle{
      text-align: center;
      font-size: 18px !important;
    }

    .section-1 .welcome-box .description{
      text-align: center;
      text-overflow: ellipsis;
      display: -webkit-box;
      -webkit-line-clamp: 3;
      -webkit-box-orient: vertical;  
      overflow: hidden;
      font-size: 14px !important;
    }

    .section-1 .promo-box .title{
      display: none;
    }

    .section-1 .promo-box .secondary-title-box{
      margin-top: 35px;
      display: block !important;
    }

    .section-1 .promo-box .secondary-title-box .header{
      text-align: center;
      font-size: 18px !important;
      font-weight: 700;
      line-height: 150%;
      margin-bottom: 20px;
    }

    .section-2 .about-box .description{
      font-size: 14px !important;
    }

    .section-2 .secondary-image-box{
      display: flex !important;
      justify-content: center;
      margin-bottom: 20px;
    }

    .section-2 .primary-image-box{
      display: none;
    }

    .section-3 .experience-box-wrapper{
      padding: 0 12px;
    }

    .section-3 .experience-box-wrapper .header{
      
      justify-content: center;
    }

    .section-3 .experience-box-wrapper .header .experience-count{
      font-size: 54px !important;
    }

    .section-3 .experience-box-wrapper .header .title{
      font-size: 14px !important;
      line-height: 20px;
      margin-left: 0;
    }

    .section-4 .achievement-box-wrapper .header{
      justify-content: center !important;
    }

    .section-4 .achievement-box-wrapper .header .title{
      font-size: 14px;
    }

    .section-4 .achievement-box-wrapper .header .achievement-count{
      font-size: 54px !important;
    }

    .section-4 .achievement-box-wrapper .header .see-all{
      display: none !important;
    }
    

  
  }


  /* Tablet */
  @media (min-width: 575.98px ) and (max-width: 991.98px) {
  
    .section-1 .welcome-box{
      padding: 0 10% !important;
    }
    .section-1 .welcome-box .title{
      font-size: 28px !important;
      text-align: center;
    }

    .section-1 .welcome-box .subtitle{
      text-align: center;
      font-size: 24px !important;
    }

    .section-1 .welcome-box .description{
      text-align: center;
    }

    .section-1 .promo-box .title{
      display: none;
    }

    .section-1 .promo-box .secondary-title-box{
      margin-top: 60px;
      display: block !important;
    }

    .section-1 .promo-box .secondary-title-box .header{
      text-align: center;
      font-size: 28px !important;
      font-weight: 700;
      line-height: 150%;
      margin-bottom: 20px;
    }

    
    .section-2 .about-box{
      padding: 0 10%;
    }

    .section-2 .about-box .description{
      font-size: 18px !important;
    }

    .section-2 .secondary-image-box{
      display: flex !important;
      
      justify-content: center;
      margin-bottom: 20px;
    }

    .section-2 .primary-image-box{
      display: none;
    }
    
    .section-3 .experience-box-wrapper{
      padding: 0 10% !important;
    }

    .section-4 .achievement-box-wrapper{
      padding: 0 10% !important;
    }

    .section-4 .achievement-box-wrapper .header .see-all{
      display: none !important;
    }
  }



</style>

