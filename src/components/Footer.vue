<template>
  <footer>
      <div class="change">
      <h1>Change a life today</h1>
      <div id="change_separatore"></div>
      <p>As long as poverty, injustice & inequality persist, none of us can truly rest. It doesn't take much to change a life, Get in touch today and start making the difference.</p>
      <a href="#">Volunteer</a>
      <a href="#">Donate now</a>
      </div>
      <div class="logo_footer">
          <img src="../assets/avada-charity-mobile-logo-retina.png" alt="Logo azienda">
      </div>
      <div class="diritti">
          <p id="copyright">&copy; Copyright 2012 - 2020 AVADA THEME BY THEME FUSION | ALL RIGHTS RESERVED | POWERED BY WORDPRESS</p>
          <i class="fab fa-facebook-f"></i>
          <i class="fab fa-instagram"></i>
          <i class="fab fa-twitter"></i>
          <i class="fab fa-youtube"></i>
      </div>
  </footer>
</template>

<script>
export default {
    name:"footer"
}
</script>

<style>
    footer{
        margin-top: 2580px;
        height: 500px;
        background-image: url('../assets/home-footer.jpg');
        background-position: center;
        background-size: cover;
        background-repeat: no-repeat;
        text-align: center;
    }

    footer h1{
        color: white;
        padding: 10px;
        padding-top: 60px;
        text-transform: uppercase;
        font-weight: 200;
    }

    footer p{
        color: white;
        margin-top: 50px;
        font-weight: 200;
        font-size: 18px;
        width: 640px;
        margin-left: 415px;
        padding-bottom: 25px;
    }

    footer a{
        text-decoration: none;
        color: white;
        border: 1px solid white;
        padding: 5px 16px;
        font-weight: 200;
        font-size: 18px;
        margin-top: 20px;
        margin-right: 50px;
    }

    footer a:hover{
        color: #FCD66C;
        background-color: white;
    }

    #change_separatore{
        height: 1px;
        width: 150px;
        color: #FCD66C;
        border: 4px solid #FCD66C;
        margin-left: 685px;
    }

    .logo_footer{
        width: 100%;
        margin-top: 225px;
    }

    .logo_footer img{
        width: 300px;
    }

    .diritti{
        background-color: lightgray;
    }

    #copyright{
        color: darkgray;
        padding-top: 20px;
        font-weight: 200;
        font-size: 14px;
        width: 840px;
        margin-left: 415px;
        padding-bottom: 25px;
    }

    .diritti i{
        font-size: 20px;
        color: #E9C899;
        margin: 12px;
        background-color: white;
        border-radius: 50%;
        padding: 12px;
    }
</style>