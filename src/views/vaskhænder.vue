<template>
<main>
<div id="topline"></div>
    <div id="topbox"></div>
    <div id="plakat">
    </div>
</main>
</template>

<script>
</script>

<style lang="scss" scoped>

main {
    margin-top: -150px;
    height: 1000px;
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
    background-image: url("../assets/no1.1.svg");
    background-repeat: no-repeat;
    background-position: 90% 20%;
    background-size: 250px;
}

#plakat {
    height: 2000px;
    width: 100%;
    background-image: url("../assets/vaskhænder.png");
    background-color: #D5EDF7;
    background-size: contain;
    background-repeat: no-repeat;
    background-position: center;
}

</style>