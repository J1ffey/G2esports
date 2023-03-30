<template>
    <div class="cs">
        <img src="../assets/csgo.webp" alt="cs">
        <div class="player">
        <h1>OUR CHAMPIONS IN </h1>
        <h1 style="color:red">COUNTER-STRIKE : GLOBAL OFFENSIVE</h1>
        </div>
        <div class="playerlist">
            <div class="player-item">
                <img src="../assets/jks.webp" alt="jks">
            </div>
            <div class="player-item">
                <img src="../assets/Hooxi.webp" alt="hooxi">
            </div>
            <div class="player-item">
                <img src="../assets/m0nesy.webp" alt="monesy">
            </div>
            <div class="player-item">
                <img src="../assets/Niko.webp" alt="niko">
            </div>
            <div class="player-item">
                <img src="../assets/Hunter.webp" alt="hunter">
            </div>
            <div class="player-item">
                <img src="../assets/Swani.webp" alt="swani">
            </div>
            <div class="player-item">
                <img src="../assets/Peca.webp" alt="peca">
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name:'CounterPlayer'
    }
</script>

<style scoped>
.cs{
    margin: auto;
    text-align: center;
    margin-top: 450px;
}
.player{
    text-align: center;
}
.playerlist{
    display: flex;
    flex-direction: row;
    justify-content: center;
    flex-wrap: wrap;
    margin-top: 75px;
}
.player-item{
    position: relative;
    margin: 5px 25px 30px;
}
</style>