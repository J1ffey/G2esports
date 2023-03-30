<template>
    <div class="MyHead">
        <header>
            <div class="h1-logo">
                <a href="https://g2esports.com"><img src="../assets/G2esports.png" alt="g2" width="165px" height="60px"></a>
            </div>
            <nav>
              <div class="h2-logo">
                <ul class="h2-logo">
                <li>
                    <a href="https://g2esports.com/collections">
                        <span>G2 Shop</span>
                    </a>
                </li>
                <li>
                    <a href="https://g2esports.com/pages/teams">
                        <span>TEAMS</span>
                    </a>
                </li>
                <li>
                    <a href="https://g2esports.com/pages/fan-arena">
                        <span>FAN ARENA</span>
                    </a>
                </li>
                <li>
                    <a href="https://g2esports.com/blogs/news">
                        <span>NEWS</span>
                    </a>
                </li>
                <li>
                    <a href="https://g2esports.com/pages/about">
                        <span>ABOUT G2</span>
                    </a>
                </li>
                <li>
                    <a href="https://g2esports.com/pages/g2app">
                        <span>G2 APP</span>
                    </a>
                </li>
                </ul>
              </div>
            </nav>
            <nav class="head-img">
                    <ul>
                        <li>
                    <a href="https://g2esports.com/account?view=dashboard">
                        <i class="fa fa-user fa-2x" style="color: black;"></i>
                    </a>
                        </li>
                        <li>
                            <a href="https://g2esports.com/pages/wishlist">
                                <i class="fa fa-heart fa-2x" ></i>
                            </a>
                        </li>
                        <li>
                            <a href="https://g2esports.com/search">
                                <i class="fa fa-search fa-2x "></i>
                            </a>
                        </li>
                        <li>
                            <a href="https://g2esports.com/cart">
                                <i class="fa fa-shopping-cart fa-2x" />
                            </a>
                        </li>
                    </ul>
                </nav>
        </header>
    </div>
</template>

<script>
    export default {
        name:'MyHead'
    }
</script>

<style scoped>
.head-img{
    position: relative;
    display: inline-flex;
    margin: auto;
}
.head-img ul li {
    position: relative;
    display: inline;
    padding: 18px;
}
li{
    list-style-type:none
}
a:link {color: black; text-decoration:none;}
a:hover {color: red;}
.h2-logo li a{
    margin-right: 42px;
    transition: color 0.5s;
}
.h1-logo{
    width: 200px;
    height: 60px;
    margin-right: 10px;
    margin-left: auto;
}
header {
    position: relative;
    display: flex;
    grid-template-columns: 1fr 2fr 1fr;
    align-items: center;
    padding: 5px 15px;
    box-shadow: 0  2px #00000026;
    z-index: 2;
    background-color: #fff;
    height: 60px;
}
.h2-logo{
    display: flex;
    font-size: 18px;
    line-height: 21px;
    font-family: Oswald,sans-serif;
    font-weight: 700;
    color: #000;
    text-transform: uppercase;
    transition: color .25s ease-in-out;
}
.head-img ul li:after {
    content: "";
    background-color: #cfc7c7;
    display: block;
    transform: rotate(20deg);
    position: absolute;
    right: 0;
    top: 0;
    height: 100%;
    width: 1px;
}

</style>