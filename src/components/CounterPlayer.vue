<template>
    <div class="cs">
        <img src="../assets/csgo.webp" alt="cs">
        <div class="player">
        <h1>OUR CHAMPIONS IN </h1>
        <h1 style="color:red">COUNTER-STRIKE : GLOBAL OFFENSIVE</h1>
        </div>
        <div class="playerlist">
            <div class="outbox">
                <div class="player-item">
                    <img src="../assets/jks.webp" alt="jks">
                </div>
            </div>
            <div class="outbox">
                <div class="player-item">
                    <img src="../assets/Hooxi.webp" alt="hooxi">
                </div>
            </div>
            <div class="outbox">
                <div class="player-item">
                    <img src="../assets/Niko.webp" alt="Niko">
                </div>
            </div>
            <div class="outbox">
                <div class="player-item">
                    <img src="../assets/m0nesy.webp" alt="Monesy">
                </div>
            </div>
            <div class="outbox">
                <div class="player-item">
                    <img src="../assets/Hunter.webp" alt="Hunter">
                </div>
            </div>
            <div class="outbox">
                <div class="player-item">
                    <img src="../assets/Swani.webp" alt="Swani">
                </div>
            </div>
            <div class="outbox">
                <div class="player-item">
                    <img src="../assets/Peca.webp" alt="Peca">
                </div>
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
.outbox div:hover img{
    filter: blur(4px);
    transition-duration: 1s;
}
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