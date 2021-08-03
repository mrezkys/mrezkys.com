<template>
  <div>
    <div class="container-lg">
        <Navbar/>
    </div>
    <div class="container-lg section-1 pt-5 pb-5 mt-1">
      <!-- <div class="stacked-logo">
        <img src="~assets/icons/mylogograd.svg" class="img-fluid" alt="">
      </div> -->
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
        <div class="row align-items-center header ml-md-3">
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
        <div class="row align-items-end header justify-content-between ml-md-3">
          <div class="row align-items-center">            
            <h1 class="achievement-count mr-5">15+</h1>
            <p class="title"><br> total <br> awards & <br> achievements</p>
          </div>
          <NuxtLink to="/" class="see-all">
          <p style="color: white">See all achievement
                    <svg width="11" height="10" viewBox="0 0 11 10" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path d="M8.56274 4.88578H2.31274" stroke="white" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                    <path d="M6.04199 2.37558L8.56283 4.88558L6.04199 7.396" stroke="white" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                    </svg>
          </p>
          </NuxtLink>
        </div>
        <div class="row mt-3">
          <AchievementBox position="1st" title="Intechfest, Web Design Competition."/>
          <AchievementBox position="1st" title="Ramadhan Fair, Poster Design Competition."/>
          <AchievementBox position="1st" title="Intechfest, Web Design Competition."/>
          <AchievementBox position="1st" title="Ramadhan Fair, Poster Design Competition."/>
        </div>
      </div>
    </div>
    <div class="container-lg section-5 pt-5 pb-3 mt-lg-3">
      <div class="featuredproject-box-wrapper">
        <div class="mb-5 row align-items-end header justify-content-between ml-md-4">          
          <div class="row align-items-center">
            <img class="project-count mr-5" src="~assets/icons/20+.png" alt="">
            <p class="title"><br> total <br> portfolio & <br> project</p>
          </div>
          <NuxtLink to="/" class="see-all">
            <p style="color: white">See all Portfolio
                      <svg width="11" height="10" viewBox="0 0 11 10" fill="none" xmlns="http://www.w3.org/2000/svg">
                      <path d="M8.56274 4.88578H2.31274" stroke="white" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                      <path d="M6.04199 2.37558L8.56283 4.88558L6.04199 7.396" stroke="white" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                      </svg>
            </p>
          </NuxtLink>
        </div>
        <div class="row">
          <div class="col-lg-5 box col-md-6 col-12">
            <div class="col-12  featuredproject-box p-0">
              <img src="~assets/images/project/logo-1.jpg" class="featuredproject" alt="">
            </div>
          </div>
          <div class="col-lg-4 box-secondary-left col-md-6 mb-md-5 col-6 mt-md-0 mt-3">
            <div class="col-12  featuredproject-box p-0">
              <img src="~assets/images/project/project-ui-2.jpg" class="featuredproject" alt="">
            </div>
          </div>
          <div class="col-lg-3 box-secondary-right col-md-12 col-6 mt-md-0 mt-3">
              <div class="p-0 m-0 stacked-display d-flex flex-column justify-content-center align-items-center">
                <h4 class="p-0 m-0">20+ Project</h4>
              </div>
              <div class="col-12  featuredproject-box p-0 opacity-5">
                <img src="~assets/images/project/project-ui-3.jpg" class="featuredproject" alt="">
              </div>
          </div>
        </div>
      </div>
    </div>
    <div class="container-lg section-6 mt-5 mb-3 ">
      <h1 class="ml-md-3 title">Tools & Skills</h1>
      <div class="col-12 mt-4">
        <div class="row justify-content-between">
          <div class="tools-skills-box">
            <img src="~assets/images/tools/ps.jpg" class="tools-skills-image" alt="">
          </div>
          <div class="tools-skills-box">
            <img src="~assets/images/tools/ai.jpg" class="tools-skills-image" alt="">
          </div>
          <div class="tools-skills-box">
            <img src="~assets/images/tools/bootstrap.jpg" class="tools-skills-image" alt="">
          </div>
          <div class="tools-skills-box">
            <img src="~assets/images/tools/flutter.jpg" class="tools-skills-image" alt="">
          </div>
          <div class="tools-skills-box">
            <img src="~assets/images/tools/css3.jpg" class="tools-skills-image" alt="">
          </div>
          <div class="tools-skills-box">
            <img src="~assets/images/tools/figma.jpg" class="tools-skills-image" alt="">
          </div>
          <div class="tools-skills-box">
            <img src="~assets/images/tools/html5.jpg" class="tools-skills-image" alt="">
          </div>
          <div class="tools-skills-box">
            <img src="~assets/images/tools/laravel.jpg" class="tools-skills-image" alt="">
          </div>
        </div>
      </div>
    </div>
    <div class="container-lg section-7 pb-3 pt-5">
      <div class="col-12 interest-banner">
        <div class="row justify-content-between align-items-center">
          <h3 class="title">interested <br> working with me?</h3>
          <div class="button"><HolographicButton text="Hire Me"/></div>
        </div>
      </div>
    </div>
    <footer>
      <div class="footer-content">
        <h4 class="title">For business inquiry please send email to <br> mrezkysulihin@gmail.com</h4>
        <p class="copyright">Muhammad Rezky Sulihin - 2021</p>
      </div>
    </footer>
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

  .stacked-logo{
    position: absolute;
    left: 50%;
    transform: translateX(-50%); 
    height: auto;
    width: auto;
    padding: 0 10%;
  }

  /* .stacked-logo img{
  } */

  .section-1{
    width: 100%;
  }

  .section-1 .welcome-box .title{
    font-family: 'Poppins';
    font-weight: 700;
    font-size: 24px;
    margin-bottom: 14px;
  }

  .section-1 .welcome-box .subtitle{
    font-family: 'Poppins';
    font-weight: 700;
    font-size: 22px;
    margin-bottom: 30px;
  }

  .section-1 .welcome-box .description{
    font-family: 'Roboto';
    font-weight: 300;
    color: #ffffff;
    line-height: 150/100;
    font-size: 18px;
    margin-bottom: 35px;
  }

  .section-1 .promo-box .title{
    font-family: 'Poppins';
    font-size: 24px;
    font-weight: 700;
    line-height: 150%;
    margin-bottom: 20px;
  }

  .section-1 .promo-box .secondary-title-box{
    display: none;
  }

  .section-2 .about-box .description{
    font-family: 'Roboto';
    font-weight: 300;
    font-size: 18px;
    line-height: 150%;
  }

  .section-2 .secondary-image-box{
    display: none;
  }

  .section-3 .experience-box-wrapper .header .title{
    font-size: 18px;
    line-height: 120%;
    font-family: 'Roboto';
    font-weight: 300;
  }
  .section-3 .experience-box-wrapper .header .experience-count{
    font-size: 130px !important;    
    font-family: 'Poppins';
    font-weight: 700;
  } 

  .section-4 .achievement-box-wrapper .header .achievement-count{
    font-size: 130px !important;    
    font-family: 'Poppins';
    font-weight: 700;
  }

  .section-4 .achievement-box-wrapper .header .title{
    font-size: 18px;
    line-height: 120%;
    font-family: 'Roboto';
    font-weight: 300;
  }

  .section-4 .achievement-box-wrapper .header .see-all{
    color: white;
  }

  .section-5 .featuredproject-box-wrapper .header .project-count{
    height: 98px;
    width: auto;
  }

  .section-5 .featuredproject-box-wrapper .header .title{
    font-size: 18px;
    line-height: 120%;
    font-family: 'Roboto';
    font-weight: 300;
  }

  .section-5 .featuredproject-box-wrapper .featuredproject-box{
    height: 250px;
    background-color: black;
  }
  
  .section-5 .featuredproject-box-wrapper .featuredproject-box .featuredproject{
    object-fit: cover;
    width: 100%;
    height: 100%;
    
  }

  .section-5 .featuredproject-box-wrapper .box-secondary-right .stacked-display{
    min-width: 100%;
    z-index: 2;
    min-height: 100%;
    position: absolute;
  }

  .opacity-5{
    filter: opacity(0.5);
  }

  .section-6 .title{
    font-family: 'Poppins';
    font-weight: 700;
  }

  .section-6 .tools-skills-box{
    padding: 8px;
    height: 128px;
    background-color: black;
    width: 128px;
  }

  .section-6 .tools-skills-box .tools-skills-image{
    width: 100%;
    height: 100%;
    object-fit: cover;
  }

  .section-7 .interest-banner{
    background-color: #171717;
    padding: 40px 60px;
  }

  .section-7 .interest-banner .title{
    font-family: 'Poppins';
    font-weight: 700;
    line-height: 150%;
  }

  footer{
    margin-top: 90px;
    height: 200px;
    width: 100%;
    background-color: #212121;
    padding-top: 45px;
  }

  footer .footer-content{
    text-align: center;
  }

  footer .footer-content .title{
    font-family: 'Roboto';
    font-size: 24px;
    font-weight: 300;
    line-height: 150%;
  }

  footer .footer-content .copyright{
    margin-top: 32px;
    font-family: 'Poppins';
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

    .section-5 .featuredproject-box-wrapper .header{
      justify-content: center !important;
    }
    
    .section-5 .featuredproject-box-wrapper .header .project-count{
      height: 54px;
    }

    .section-5 .featuredproject-box-wrapper .header .title{
      font-size: 14px;
    }

    .section-5 .featuredproject-box-wrapper .header .see-all{
      display: none;
    }



    .section-5 .featuredproject-box-wrapper .box-secondary-left{
      padding: 0 !important;
      padding-left: 15px !important;
      padding-right: 8px !important;
    }

    .section-5 .featuredproject-box-wrapper .box-secondary-left .featuredproject-box{
      height: 150px !important;
    }

    .section-5 .featuredproject-box-wrapper .box-secondary-right{
      padding: 0 !important;
      padding-right: 15px !important;
      padding-left: 8px !important;
    }

    .section-5 .featuredproject-box-wrapper .box-secondary-right .featuredproject-box{
      height: 150px !important;
    }

    .section-5 .featuredproject-box-wrapper .box-secondary-right .stacked-display h4{
      font-size: 18px;
    }

    .section-6{
      text-align: center;
    }

    .section-6 .row{
      justify-content: center !important;
    }

    .section-6 .row .tools-skills-box{
      width: 80px;
      height: 80px;
    }

    .section-6 .title{
      font-size: 24px !important;
    }


    .section-7 .interest-banner{
      background-color: #171717;
      padding: 16px 32px;
    }

    .section-7 .interest-banner .title{
      font-weight: 700;
      line-height: 150%;
      font-size: 16px;
    }

    .section-7 .interest-banner .button{
      transform: scale(0.8);
    }

    footer .footer-content .title{
      font-size: 16px;
    }

    footer .footer-content .copyright{
      margin-top: 32px;
      font-size: 14px;
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

    .section-5 .featuredproject-box-wrapper{
      padding: 0 10% !important;
    }

    .section-6{
      padding: 0 10% !important;
    }

    .section-6 .row{
      justify-content: center !important;
    }

    .section-6 .row .tools-skills-box{
      width: 120px;
      height: 120px;
    }

    .section-7{
      padding: 0 10%;
    }
  }



</style>

