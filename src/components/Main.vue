<template>
    <main>
        <div class="col-lg-7 testo_sx">
            <h3>Every moments counts</h3>
            <div class="separatore"></div>
            <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Blanditiis voluptate ipsa veniam deleniti magnam tempore laborum, itaque architecto, officia veritatis exercitationem dignissimos.</p>
            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Quaerat aliquid cumque dolore quidem impedit architecto reprehenderit, necessitatibus ipsa.</p>
            <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Cumque consequuntur ipsum accusamus!</p>
            <a href="#" class="mission_link">Our mission</a>
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
        <div class="value">
            <div class="value_text">
                <h2>Our values</h2>
                <!-- <div id="separatore_value"></div> -->
                <p>Think Big. Act Bigger.</p>
            </div>  
            <div class="cards">
                <div>
                    <i class="fas fa-tint"></i>
                    <h4>Clean Water</h4>
                    <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Est eligendi sint adipisci molestiae assumenda.</p>
                    <a href="#" class="mission_link">Learn more</a>
                </div>

                <div>
                    <i class="fas fa-stethoscope"></i>
                    <h4>Vaccinations</h4>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Rem omnis dolore dolores hic quas.</p>
                    <a href="#" class="mission_link">Learn more</a>
                </div>

                <div>
                    <i class="fas fa-graduation-cap"></i>
                    <h4>Education</h4>
                    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Est reprehenderit facilis architecto</p>
                    <a href="#" class="mission_link">Learn more</a>
                </div>

                <div>
                    <i class="fas fa-tractor"></i>
                    <h4>Farming</h4>
                    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Assumenda perferendis quas dolores dicta fugiat.</p>
                    <a href="#" class="mission_link">Learn more</a>
                </div>
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
    .main{
        position: relative;
    }
    .testo_sx{
        float: left;
        background-color: white;
        height: 384px;
    }

    .testo_sx::after,
    .testo_dx::after{
        content: "";
        display: table;
        clear: both;
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

    .mission_link{
        text-decoration: none;
        border: 2px solid #FCD66C;
        padding: 6px 16px;
        color: white;
        background-color: #FCD66C;
        margin-left: 17px;
        text-transform: uppercase;
        font-size: 13px;
    }

    .mission_link:hover{
        color: #FCD66C;
        background-color: white;
    }

    .value{
        background-image: url(../assets/home-content-bg-2.jpg);
        height: 620px;
        width: 100%;
        background-size: cover;
        background-repeat: no-repeat;
        position: absolute;
        top: 1065px;
        text-align: center;
    }

    .value_text{
        margin-top: 150px;
        color: white;
    }

    .value_text h2{
        text-transform: uppercase;
        font-weight: 200;
    }

    #separatore_value{
        height: 1px;
        width: 150px;
        color: #FCD66C;
        border: 4px solid #FCD66C;
    }

    .cards{
        margin-top: 80px;
        display: flex;
        justify-content: space-evenly;
        /* width: calc(90% / 4); */
    }

    .cards i{
        color: #FCD66C;
        font-size: 50px;
    }

    .cards h4,
    .cards p{
        color: white;
        width: 290px;
        font-weight: 400;
        padding-top: 5px;
    }

    .cards a{

    }
</style>