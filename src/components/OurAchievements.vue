<template>
    <div class="Achievements">
        <div class="Word">
            <h1>OUR ACHIEVEMENTS IN </h1>
        <h1 style="color:red">COUNTER-STRIKE : GLOBAL OFFENSIVE</h1>
        </div>
        <div id="Achievements-list" v-for="item in list" 
        v-bind:key="item.PlayerId">
            <img src="../assets/csgo.webp" />
            <i class="fa fa-trophy fa-3x"  />
            <h2>{{ item.rank }}</h2>
            <h2>{{ item.time }}</h2>
            <h2>{{ item.name }}</h2>
        </div>
    </div>
</template>

<script>
    export default {
        name:'OurAchievements',
        data(){
            return{
            list:[
                {
                    PlayerId: 1 ,
                    rank: '1nd' ,
                    time: 'February 12,2023' ,
                    name:'Intel Extreme Masters Katowice 2023' ,
                },
            ]
            }
        }

    }
        
        
</script>

<style scoped>
.Word{
    text-align: center;
    font-size: 25px;
}
#Achievements-list{
    display: flex;
    margin-top: 50px;

}
#Achievements-list h2,img,i{
    margin: auto;
}
</style>