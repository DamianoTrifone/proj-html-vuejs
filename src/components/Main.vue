<template>
    <main>
        <div class="col-lg-7 testo_sx">
            <h3>Every moments counts</h3>
            <div class="separatore"></div>
            <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Blanditiis voluptate ipsa veniam deleniti magnam tempore laborum, itaque architecto, officia veritatis exercitationem dignissimos.</p>
            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Quaerat aliquid cumque dolore quidem impedit architecto reprehenderit, necessitatibus ipsa.</p>
            <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Cumque consequuntur ipsum accusamus!</p>
            <a href="#" id="mission_link">Our mission</a>
        </div>
        <div class="col-lg-5 testo_dx">
            <div class="dati">
                <i class="far fa-heart">   2032</i>
                <h4>Volunteers worldwide</h4>
            </div>

            <div class="dati">
                <i class="fas fa-globe">   132</i>
                <h4>Active projects</h4>
            </div>

            <div class="dati">
                <i class="fas fa-dollar-sign">   3.8 M</i>
                <h4>Donated</h4>
            </div>
        </div>
    </main>
</template>

<script>
export default {
    name:"main"
}
</script>

<style>
    .testo_sx{
        float: left;
    }
    .testo_sx h3{
        margin-left: 30px;
        margin-top: 35px;
        font-weight: 300;
        text-transform: uppercase;
    }

    .separatore{
        height: 1px;
        width: 150px;
        color: #FCD66C;
        border: 4px solid #FCD66C;
        margin-left: 30px;
    }

    .testo_sx p{
        margin-left: 18px;
        margin-top: 18px;
        font-weight: 200;
    }

    .testo_dx{
        background-image: url(../assets/home-content-bg-1.jpg);
        float: right;
        text-align: center;
        padding: 10px;
        color: white;
    }

    .testo_dx i{
        font-size: 45px;
        margin-right: 15px;
    }

    .testo_dx h4{
        font-weight: 200;
    }

    .dati{
        padding: 20px;
    }

    #mission_link{
        text-decoration: none;
        border: 2px solid #FCD66C;
        padding: 6px 12px;
        color: white;
        background-color: #FCD66C;
        margin-left: 17px;
        text-transform: uppercase;
        font-size: 13px;
    }

    #mission_link:hover{
        color: #FCD66C;
        background-color: white;
    }
</style>