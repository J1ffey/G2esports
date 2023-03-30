<template>
    <div class="top-head">
        <div class="top-head-banner">
                <p>All  the  stars  lead  me  to  champion,  Congratulations  to  Faze Clan on  winning  EPL  S17. And  G2 is ready for next major.</p>
        </div>
        <div class="worldwide">
            <a href="#">
            <span>REST OF THE WORLD <i class="fa fa-globe fa-lg" style=" color: black;"/></span>
            </a>
        </div>
        <div class="help">
            <a href="https://g2esports.com/pages/faq">HELP</a>
        </div>
        
    </div>
</template>

<script>
    export default {
        name:'TopHead'
    }
</script>

<style scoped>
a:link {color: white; text-decoration:none;}
.help{
    display: flex;
    align-items: center;
    padding: 20px;
    margin-right:50px ;
}
.worldwide{
    font-size: 16px;
    align-items: center;
    display: flex;
    padding: 20px;
    margin-left: 30px;
}
.worldwide span{
    color: white;
}
.top-head-banner{
    width: 800px;
    flex-grow: 1;
    position: relative;
    display: flex;
    overflow: hidden;
    margin-left: 50px;
}
.top-head-banner p{
    font-size: 16px;
    align-items: center;
    height: 40px;
    color: white;
    font-weight: 1000;
    display: flex;
    animation-name: faze;
    animation-duration: 30s ;
    animation-iteration-count: infinite;
    animation-timing-function: linear;
    width: 1000px;
    position: relative;
}
.top-head{
    background-color:#dd1c21;
    height: 40px;
    width: 100%;
    display: flex;
}
@keyframes faze{
    from {transform:translateX(100%) ;}
    to {transform: translateX(-100%);}
}
</style>