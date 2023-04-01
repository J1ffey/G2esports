<template>
    <div class="RelatedNews">
        <div class="Word">
            <h2 class="headline">
                RELATED
                <strong>NEWS</strong>
            </h2>
        </div>
        <div class="News">
            <div class="Newsborder">
                <div>
                    <div class="New">
                        <img src="../assets/background.webp" alt="cs">
                    </div>
                <div class="Bug">
                    <a href="https://g2esports.com/blogs/news/tagged/type-games">
                    <div class="Games">
                        GAMES
                    </div>
                    </a>
                    <div class="Information">
                        <a href="https://g2esports.com/blogs/news/csgo_update_12_2020">
                            CS:GO Roster Update - December 2020
                        </a>
                    </div>
                </div>
                </div>
            </div>
            <div class="Newsborder">
                <div>
                    <div class="New">
                        <div>
                        <img src="../assets/NNiko.webp" alt="Niko">
                        </div>
                    </div>                      
                 
                <div class="Box">
                    <a href="https://g2esports.com/blogs/news/tagged/type-games">
                    <div>
                        GENRAL
                    </div>
                    </a>
                    <a href="https://g2esports.com/blogs/news/tagged/type-news">
                    <div>
                        NEWS
                    </div>
                    </a>
                </div>
                <div class="Information">
                    <a href="https://g2esports.com/blogs/news/csgo_update_12_2020">
                        Biggest CS:GO Signing in History - Welcome Niko
                    </a>
                </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name:'MyNews'
    }
</script>

<style scoped>
.Newsborder div:hover img{
    transform: scale(1.2);
    filter: blur(4px);
    transition-duration: 1s;
}
.Bug{
    height: 25px;
    margin-left: 0px;
    text-align: center;
    margin-top: 5px;
}
.Word{
    width: 100%;
    height: auto;
    text-align: center;
    font-size: 40px;
    margin-top: 50px;
}
strong{
    color: red;
}
.News{
    margin-top: 40px;
    display: flex;
}
.New img{
    width: 315px;
    height: 177px;
}
.New{
    overflow: hidden;
    position: relative;
}
.Newsborder{
    background-color: black;
    width: auto;
    height: 270px;
    margin: 10px 20px 10px 100px;
    overflow: hidden;
}
.Games{
    width: 70px;
    background-color: red;
    align-items: center;
    height: 25px;
    margin-left: 10px;
    font-size: 14px;
    margin-top: 5px;
}
.Games a{
    width: 70px;
}
a:link{
    color: white; text-decoration:none;
}
.Information{
    width: 305px;
    height: 55px;
    align-items: center;
    display: flex;
    font-size: 16px;
    margin-left: 10px;
}
.Box{
    height: 25px;
    margin-left: 5px;
    display: flex;
    text-align: center;
    margin-top: 5px;
}
.Box div{
    width: 80px;
    background-color: red;
    margin-left: 10px;
    font-size: 14px;
    height: 25px;
}
</style>