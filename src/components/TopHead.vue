<template>
    <div class="top-head">
        <div class="top-head-banner">
                <p v-show="Major">All  the  stars  lead  me  to  champion,  Congratulations  to  Faze Clan on  winning  EPL  S17. And  G2 is ready for next major.</p>
                <p v-show="major">漫天星河为我引！Faze赢得EPL S17冠军&英特尔大满贯第四赛季</p>
        </div>
        <div class="worldwide">
            <a href="#">
            <span @click="onClick">REST OF THE WORLD <i class="fa fa-globe fa-lg" style=" color: black;"/></span>
            </a>
        </div>
        <div class="help">
            <a href="https://g2esports.com/pages/faq">HELP</a>
        </div>
        
    </div>
</template>

<script>
    export default {
        name:'TopHead',
        data(){
            return{
                Major:true,
                major:false
            }
        },
        methods:{
    onClick(){
        this.Major = !this.Major;
        this.major = !this.major;
    }
  }
        
    }
</script>

<style scoped>
.top-head{
    position: fixed;
    overflow: visible;
    z-index:1;
}
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