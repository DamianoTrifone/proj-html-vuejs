<template>
  <header>
      <img class="logo_header" src="../assets/avada-charity-logo-retina.png" alt="Logo Avada Charity">
      <div class="links_header">
          <a href="#">Home</a>
          <a href="#">Missions</a>
          <a href="#">Causes</a>
          <a href="#">Journal</a>
          <a class="special_link" href="#">Donate</a>
      </div>
  </header>
</template>

<script>
export default {
    name:"header"
}
</script>

<style lang="scss">
    header{
        background-image: url(../assets/home-page-slider.jpg);
        background-size: cover;
        background-repeat: no-repeat;
        height: 600px;
        width: 100%;
    }

    .logo_header{
        width: 265px;
        margin-top: 18px;
        margin-left: 35px;
    }

    .links_header{
        float: right;
        margin-top: 30px;
        margin-right: 35px;
    }

    .links_header a{
        color: white;
        margin-right: 50px;
        text-decoration: none;
        text-transform: uppercase;
    }

    .links_header a:hover{
        color: #FCD66C;
    }

    .special_link{
        border: 2px solid #FCD66C;
        padding: 4px 8px;
        background-color: #FCD66C;
    }

    .special_link:hover{
        color: white;
        background-color: white;
    }
</style>