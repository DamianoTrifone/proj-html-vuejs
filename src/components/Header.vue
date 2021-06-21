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
      <div class="header_centrale">
          <h2>Make a difference</h2>
          <p>As long as poverty, injustice & inequality persist, none of us can truly rest</p>
          <a href="#">Our mission</a>
          <a href="#">Donate now</a>
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
        height: 680px;
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

    .header_centrale{
        text-align: center;
        margin-top: 14%;
    }

    .header_centrale h2{
        text-transform: uppercase;
        color: white;
        font-weight: 300;
        font-size: 60px;
    }

    .header_centrale p{
        color: white;
        font-weight: 200;
        font-size: 20px;
    }

    .header_centrale a{
        text-decoration: none;
        text-transform: uppercase;
        margin-left: 15px;
        color: white;
        border: 1px solid white;
        padding: 4px 8px;
        font-weight: 200;
    }

    .header_centrale a:hover{
        color: #FCD66C;
    }

    .header_centrale a:last-child{
        color: #FCD66C;
        border: 1px solid #FCD66C;
    }

    .header_centrale a:last-child:hover{
        color: white;
    }
</style>