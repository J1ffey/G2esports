<template>
    <div class="foot">
        <div class="contain">
            <div class="container">
                <div class="banner">
                    <div class="together">
                    <img src="../assets/G2.png" alt="G2" width="121px" height="138px">
                    <br>
                        <div class="image">
                        <a href="#" >
                            <i class="fa fa-twitter fa-2x"/>
                        </a>
                        <a href="#">
                            <i class="fa fa-facebook fa-2x"/>
                        </a>
                        <a href="#">
                            <i class="fa fa-youtube fa-2x" />
                        </a>
                        <a href="#">
                            <i class="fa fa-twitch fa-2x" />
                        </a>
                        <br>
                        <a href="#">
                            <i class="fa fa-weibo fa-2x"/>
                        </a>
                        <a href="#">
                            <i class="fa fa-linkedin fa-2x" />
                        </a>
                        <a href="#">
                            <i class="fa fa-instagram fa-2x"/>
                        </a>
                        </div>
                        <div class="fortnite">
                    <h3>G2 FORTNITE:</h3>
                    <a href="#">
                        <i class="fa fa-instagram fa-2x"/>
                    </a>
                    <a href="#">
                        <i class="fa fa-youtube fa-2x" />
                    </a>
                    <a href="#">
                        <i class="fa fa-twitter fa-2x"/>
                    </a>
                    
                        </div>
                    </div>
                    <div class="listcontainer">
                            <div class="list">
                                <h2>G2 ESPORTS</h2>
                                <div class="list">
                                <a href="#">News</a><br>
                                <a href="#">About</a><br>
                                <a href="#">Partners</a><br>
                                <a href="#">Careers</a><br>
                                <a href="#">Contact</a><br>
                                <a href="#">Business Contact</a><br>
                                <a href="#">Brand Guidenlines</a><br>
                                <a href="#">Media</a><br>
                                </div>
                            </div>
                            <div class="list">
                                <h2>SHOP</h2>
                                <div class="list">
                                <a href="#">All Products</a><br>
                                <a href="#">Pro Kit</a><br>
                                <a href="#">National Jerseys</a><br>
                                <a href="#">Lifestyle</a><br>
                                <a href="#">Accessories</a><br>
                                <a href="#">Hardware</a><br>
                                <a href="#">In-Game</a><br>
                                <a href="#">Sale</a><br>
                                <a href="#">Help</a>
                                </div>
                            </div>
                            <div class="list">
                                <h2>TEAMS</h2>
                                <div class="list">
                                <a href="#">League of Legends</a><br>
                                <a href="#">CS:GO</a><br>
                                <a href="#">Rocket League</a><br>
                                <a href="#">Rainbow Six</a><br>
                                <a href="#">Valorant</a><br>
                                <a href="#">Fortnite</a><br>
                                <a href="#">All Teams</a><br>
                                <a href="#">All Creators</a><br>
                                </div>
                            </div>
                    </div>
                    <div class="sign">
                                <h3>
                                Sign up to get 
                                <strong style="color:red">10% off</strong>
                                on your first order!
                                </h3>
                                <div class="box">
                                    <input class="box" type="text" placeholder="Enter Your Email">
                                    <button @click="onClick" class="button">Sign Up</button>
                                </div>
                                <p v-show="pain">sucess</p> 
                                <div class="bannerindex">
                                    <h2>Payment methods</h2>
                                    <img src="../assets/2023-04-01.png" alt="payments" width="300px">
                                </div>
                    </div>
                    
                </div>
            </div>
        </div>
        <div class="finnal">
            <footer>
                <div class="shuoming">
                    <p>© 2023, EU - G2 Esports. All Rights Reserved.Products in our EU Store are sold by Bulldog Sports Ltd.</p>
                </div>
                <div class="buzhidaozenmemingming">
                    <a href="#">Privacy</a>
                    <a href="#">Imprint</a>
                    <a href="#">Terms</a>
                </div>
                <div class="zhendebuzhidaozenmemingming">
                    <p>Web Design by Jiff</p>
                </div>
            </footer>
        </div>
        
    </div>
</template>

<script>
    export default {
        name:'MyFooter',
        data(){
            return{
                pain:false
            }
        },
        methods:{
    onClick(){
        this.pain = !this.pain;
    }
  }
    }
</script>

<style scoped>
.zhendebuzhidaozenmemingming{
    width: 200px;
    float: right;
    font-size: 16px;
    margin-top: 20px;
    color: white;
}
.buzhidaozenmemingming{
    width: 200px;
    float: left;
    padding-left: 320px;
    font-size: 16px;
    margin-top: 20px;
}
.buzhidaozenmemingming a{
    margin: 15px;
}
.buzhidaozenmemingming a:visited{
    color: rgb(157, 149, 149);
}
.buzhidaozenmemingming a:hover{
    color: rgb(236, 225, 225);
}
.buzhidaozenmemingming a:link{
    text-decoration-line: none;
}
.shuoming{
    color: #f1f1f1;
    width: 338px;
    font-size: 13px;
    margin-top: 10px;
    margin-left: 20px;
    float: left;
}
.finnal{
    border-top: 2px solid gray;
}
.bannerindex{
    color: #f1f1f1;
    margin-top: 100px;
}
.sign{
    height: 500px;
    float: left;
    width: 300px;
}
.sign h3{
    margin-bottom: 20px;
}
.box{
        position: relative;
        width: 300px;
        background-color: #f1f1f1;
    }
.sign p{
    color: #f1f1f1;
}
.box input{
        width: 100%;
        height: 30px;
        border: 3px solid white;
        background-color: rgb(77, 72, 72);
    }
.box button{
        position: absolute;
        top: 7px;
        right: 0;
        background-color: red;
        border: 2px solid ;
        
     }
button:hover{
            color: white;
            transition: all 1s;
        }
.together{
    float: left;
    width: 200px;
    height: 420px;
    margin-right: 150px;
}
.list{
    width: 180px;
    text-align: left;
    line-height: 40px;
    margin-right: 60px;
    height: auto;
    float: left;
}
.listcontainer h2{
     color: red;
}
.sign h3{
    color: aliceblue;
    font-size: 22px;
}
.image a:visited {color:white;}
.fortnite a:visited{color: gray;}
.fortnite{
    color: gray;
    padding-top: 10%;
    margin: 10px ;
}
.fortnite i{
    margin: 7px;
    margin-right: 15px;
}
.foot{
    background-image: url("../assets/back.png");
    width: 100%;
    height: 800px;
    background-size: 100% 100%;
}
.contain{
    padding-top: 15%;
    height: 480px;
    overflow:hidden
}
.banner{
    width: 100%;
    padding-left: 5%;
    height: 500px;
    position: relative;
}
.image i{
    margin: 10px ;
    margin-top: 30px;
}
.image a:hover{
    color: rgb(115, 6, 249);
}
.fortnite a:hover{color: rgb(255, 0, 144);}
.list a{
    padding-top: 20px;
    transition: color 1s;
}
.listcontainer{
    height: 420px;
    float: left;
    width: 760px;
}
.list a:link{text-decoration:none;}
.list a:visited{color: antiquewhite;}
.list a:hover{color: white;}
</style>