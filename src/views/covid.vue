<template>
<main>
    <div id="topline"></div>
    <div id="topbox"></div>
     <div id="plakat"></div>

     <div id="facts"></div>
     <div id="piechart"></div>
     <div id="infomercial"></div>
     <div id="video">
         <iframe width="860" height="615" src="https://www.youtube.com/embed/QERZQ_L0AqM" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
     </div>
</main>
</template>

<script>
</script>

<style lang="scss" scoped>

main {
    margin-top: -150px;
    height: 4500px;
    width: 100%;
    background-color: #D5EDF7;
}

#topline {
    height: 100px;
    width: 100%;
    background-color: #D5EDF7;
}

#topbox {
    height: 250px;
    width: 100%;
    background-image: url("../assets/NOCO.png");
    background-repeat: no-repeat;
    background-position: 90% 20%;
    background-size: 250px;
}

#plakat {
    height: 1500px;
    width: 100%;
    margin-top: 100px;
    background-image: url("../assets/bakterien.png");
    background-color: #D5EDF7;
    background-size: contain;
    background-repeat: no-repeat;
    background-position: center;
}

#facts {
    height: 500px;
    width: 100%;
    margin-top: 150px;
    background-image: url("../assets/facts.png");
    background-color: #D5EDF7;
    background-size: contain;
    background-repeat: no-repeat;
    background-position: center;
}

#piechart {
    height: 700px;
    width: 100%;
    margin-top: 150px;
    background-image: url("../assets/piechart.png");
    background-color: #D5EDF7;
    background-size: contain;
    background-repeat: no-repeat;
    background-position: center;
}

#infomercial {
    height: 120px;
    width: 100%;
    margin-top: 150px;
    background-image: url("../assets/infomercial.png");
    background-color: #D5EDF7;
    background-size: contain;
    background-repeat: no-repeat;
    background-position: center;
}

#video {
    margin-top: 50px;
}

@media only screen
    and (device-width : 375px)
    and (device-height : 812px)
    and (-webkit-device-pixel-ratio : 3) {

main {
    margin-top: -150px;
    height: 1800px;
    width: 100%;
    background-color: #D5EDF7;
}

#topline {
    height: 100px;
    width: 100%;
    background-color: #D5EDF7;
}

#topbox {
    height: 100px;
    width: 100%;
    background-image: url("../assets/NOCO.png");
    background-repeat: no-repeat;
    background-position: 90% 20%;
    background-size: 100px;
}

#plakat {
    height: 600px;
    width: 100%;
    margin-top: 10px;
    background-image: url("../assets/bakterien.png");
    background-color: #D5EDF7;
    background-size: contain;
    background-repeat: no-repeat;
    background-position: center;
}

#facts {
    height: 250px;
    width: 100%;
    margin-top: -25px;
    background-image: url("../assets/facts.png");
    background-color: #D5EDF7;
    background-size: contain;
    background-repeat: no-repeat;
    background-position: center;
}

#piechart {
    height: 230px;
    width: 100%;
    margin-top: 15px;
    background-image: url("../assets/piechart.png");
    background-color: #D5EDF7;
    background-size: contain;
    background-repeat: no-repeat;
    background-position: center;
}

#infomercial {
    height: 50px;
    width: 100%;
    margin-top: 100px;
    background-image: url("../assets/infomercial.png");
    background-color: #D5EDF7;
    background-size: contain;
    background-repeat: no-repeat;
    background-position: center;
}

#video {
    margin-top: 30px;
}

iframe {
    height: 200px;
    width: 300px;
}

}

</style>
