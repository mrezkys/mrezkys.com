<template>
    <div>
        <div class="container-lg">
            <Navbar/>
        </div>
        <div class="container-lg section-4 pt-1 pb-3 pt-lg-5 pb-lg-3 mt-lg-3">
          <div class="achievement-box-wrapper">
            <div class="row align-items-center header ml-md-3">  
              <h1 class="achievement-count mr-5">20+</h1>
              <p class="title"><br> total <br> awards & <br> achievements</p>
            </div>
            <div class="row mt-3">
              <AchievementCard position="3rd" grade="National" year="2021" by="Puspresnas & Kemdikbud ( Ministry of Education and Culture )" title="LKS Nasional XVIII Graphic Design Technology"/>
              <AchievementCard position="2nd" grade="National" year="2022" by="Kementrian Ketenagakerjaan ( Ministry of Manpower )" title="Seleksi Daerah Asean Skills Competition"/>
              <AchievementCard position="2nd" grade="National" year="2022" by="HMIF Universitas Mataram" title="Lomba Desain Poster - Infornation 2022"/>
              <AchievementCard position="1st" grade="National" year="2021" by="Politeknik Negeri Bali" title="Intechfest, Web Design Competition - College Level."/>
              <AchievementCard position="1st" grade="National" year="2020" by="Politeknik Negeri Bali" title="Intechfest, Web Design Competition Tingkat - Highschool Level"/>
              <AchievementCard position="1st" grade="National" year="2020" by="Kejar Mimpi Makassar" title="Ramadhan Fair, Poster Design Competition."/>
              <AchievementCard position="2nd" grade="National" year="2020" by="Lembaga Perlindungan Anak Indonesia" title="LPAI, Poster Design Competition."/>
              <AchievementCard position="2nd" grade="National" year="2019" by="Informatic Engineering UNISSULA" title="Challenge Your Skills #2, Poster Design Competition."/>
              <AchievementCard position="Fav 3" grade="National" year="2021" by="Aspac Indonesia & Facebook ( AMAN Project ). Im on the Dewan Anak Mataram Team, with Natasha, Bentang, and Dinda" title="Video Competition"/>
              <AchievementCard position="2nd" grade="National" year="2020" by="Virtual Skill Competition" title="VSC #2, Graphic Design Technolgy"/>
              <AchievementCard position="1st" grade="National" year="2021" by="Virtual Skill Competition" title="VSC #5, Graphic Design Technolgy"/>
              
              <AchievementCard position="1st" grade="Province" year="2021" by="LKS SMK" title="LKS Provinsi NTB, Graphic Design Technology"/>
              <AchievementCard position="1st" grade="Province" year="2020" by="Mandalika University" title="Graphic Design Technology Competition"/>
              <AchievementCard position="1st" grade="Province" year="2019" by="Hamzanwadi Festival Science & Tech" title="HESTEG #1, Graphic Design Competition"/>
              <AchievementCard position="2nd" grade="Province" year="2019" by="Asean Skills Competition " title="Selekda Asian Skills Competition, Graphic Design Technology"/>

              <AchievementCard position="1st" grade="City" year="2021" by="LKS SMK" title="LKS Kota Mataram, Graphic Design Technology"/>
              <AchievementCard position="2nd" grade="City" year="2020" by="LKS SMK" title="LKS Kota Mataram, Graphic Design Technology"/>
              <AchievementCard position="3rd" grade="City" year="2019" by="Fastabiqul Khairat SMAN 1 Mataran" title="Poster Design Competition"/>

              
              <AchievementCard position="2nd" grade="City" year="2017" by="IDI. In this competition I teamed up with Athifah Kurnia represent our school SMPN 1 Maluk" title="Lomba Poster"/>
              
              <AchievementCard position="3rd" grade="District" year="2016" by="PT. Newmont Nusa Tenggara" title="Lomba Ranking 1 Kesehatan"/>

              <AwardCard year="2021" by="Vocational Highschool 3 Mataram" title="Best Graduate of Computer and Network Engineering major"/>
              <AwardCard year="2021" by="Vocational Highschool 3 Mataram" title="Graphic Design ambassador"/>
              <AwardCard year="2020" by="Smekti Nircable Community" title="Best Member of Smekti Nircable Community"/>
            </div>
          </div>
        </div>
    </div>
</template>

<style>
  body{
    background-color: black;
    color: white;
    margin: 0px;
    padding: 0px;
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

  @media (max-width: 575.98px) {
    .section-4 .achievement-box-wrapper .header{
      justify-content: center !important;
    }

    .section-4 .achievement-box-wrapper .header .title{
      font-size: 14px;
    }

    .section-4 .achievement-box-wrapper .header .achievement-count{
      font-size: 54px !important;
    }
  }

  @media (min-width: 575.98px ) and (max-width: 991.98px) {
    .section-4 .achievement-box-wrapper{
      padding: 0 10% !important;
    }

  }
</style>
