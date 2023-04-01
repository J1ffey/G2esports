<template>
    <div class="Achievements">
        <div class="Word">
            <h1>OUR ACHIEVEMENTS IN </h1>
        <h1 style="color:red">COUNTER-STRIKE : GLOBAL OFFENSIVE</h1>
        </div>
        <div id="Achievements-list" v-for="item in list" 
        v-bind:key="item.PlayerId">
            <div class="csimg">
                <img src="../assets/csgo.webp" />
            </div>
            <div class="trophy">
                <i class="fa fa-trophy fa-2x"  />
                <p>{{ item.rank }}</p>
            </div>
            <div class="time">
                <p>{{ item.time }}</p>
            </div>
            <div class="name">
                <h3>{{ item.name }}</h3>
            </div>
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
                    rank: '1st' ,
                    time: 'February 12,2023' ,
                    name:'Intel Extreme Masters Katowice 2023' ,
                    
                },
                {
                PlayerId: 2 ,
                    rank: '1st' ,
                    time: 'December 18, 2022' ,
                    name:'BLAST World Final 2022' ,
                },
                {
                PlayerId: 3 ,
                    rank: '2nd' ,
                    time: 'August 22, 2021' ,
                    name:'PGL Major Stockholm 2021' ,
                },
                {
                PlayerId: 4 ,
                    rank: '2nd' ,
                    time: 'July 18, 2021' ,
                    name:'IEM Cologne' ,
                },
                {
                PlayerId: 5 ,
                    rank: '3rd' ,
                    time: 'June 20, 2021' ,
                    name:'BLAST Premier: Spring Finals 2021' ,
                },
                {
                PlayerId: 6 ,
                    rank: '3rd-4th' ,
                    time: 'May 08, 2021' ,
                    name:'DreamHack Masters Spring 2021' ,
                },
                {
                PlayerId: 7 ,
                    rank: '3rd-4th' ,
                    time: 'June 12, 2021' ,
                    name:'Intel Extreme Masters XVI - Summer' ,
                },
                {
                PlayerId: 8 ,
                    rank: '1st-3rd' ,
                    time: 'November 04, 2020' ,
                    name:'BLAST Premier: Fall 2020 Regular Season' ,
                },
                {
                PlayerId: 9 ,
                    rank: '11th-12th' ,
                    time: 'October 04, 2020' ,
                    name:'ESL Pro League Season 12 Europe' ,
                },
                {
                PlayerId: 10 ,
                    rank: '9th' ,
                    time: 'July 05, 2020' ,
                    name:'cs_summit 6 Europe' ,
                },
                {
                PlayerId: 11 ,
                    rank: '5th-6th' ,
                    time: 'June 21, 2020' ,
                    name:'BLAST Premier Spring 2020 Europe Finals' ,
                },
                {
                PlayerId: 12 ,
                    rank: '2nd' ,
                    time: 'June 14, 2020' ,
                    name:'DreamHack Masters Spring 2020 Europe' ,
                },
                {
                PlayerId: 13 ,
                    rank: '5th-6th' ,
                    time: 'May 31, 2020' ,
                    name:'Gamers Without Borders 2020' ,
                },
                {
                PlayerId: 14 ,
                    rank: '1st' ,
                    time: 'February 16, 2020' ,
                    name:'BLAST Premier Spring Series 2020 Group C' ,
                },
                {
                PlayerId: 15 ,
                    rank: '2nd' ,
                    time: 'February 15, 2020' ,
                    name:'Intel Extreme Masters XIV' ,
                },
                {
                PlayerId: 16 ,
                    rank: '1st' ,
                    time: 'December 22, 2019' ,
                    name:'Champions Cup Finals' ,
                },
                {
                PlayerId: 17 ,
                    rank: '3rd' ,
                    time: 'September 29, 2019' ,
                    name:'ESL One New York' ,
                },
                {
                PlayerId: 18 ,
                    rank: '1st' ,
                    time: 'July 15, 2019' ,
                    name:'Good Game League 2019 Finals Champions' ,
                },
                {
                PlayerId: 19 ,
                    rank: '1st' ,
                    time: 'July 14, 2019' ,
                    name:'Good Game League' ,
                },
                {
                PlayerId: 20 ,
                    rank: '2nd' ,
                    time: 'June 22, 2019' ,
                    name:'ESL Pro League Season 9 Finals' ,
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
    margin-bottom: 50px;
}
#Achievements-list{
    display: flex;
    margin-top: 20px;
    border-bottom: 1px solid rgb(159, 154, 154);
    width: 85%;
    margin: auto;
    position: grid;
}
.csimg{
    margin: 10px 50px 10px 50px;
    position: grid;
}
.trophy{
    margin: 10px 0px 10px 50px;
    width: 200px;
    height: 34px;
    text-align: center;
}
.time{
    margin: 25px 150px 10px 100px;
    position: relative;
    width: 175px;
}
.name{
    margin: auto;
    text-align: center;
}
#Achievements-list img{
    width: 50px;
}
</style>