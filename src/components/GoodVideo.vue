<template>
    <div class="Cs">
        <video id="v1" autoplay loop muted>
        <source src="../assets/CS.mp4" type="video/mp4" />
        </video>
    </div>
</template>

<script>
    export default {
        name:'GoodVideo'
    }
</script>

<style scoped>
video {
            position: relative;
            right: 0px;
            bottom: 0px;
            height: auto;
            width: 100%;
            /*加滤镜*/
            filter: blur(50px); /*背景模糊设置 */
            -webkit-filter: grayscale(100%);
            filter:grayscale(70%);/*背景灰度设置  */
            z-index: -11
        }
        .Cs{
            margin: auto;
            width: 100%;
            height: 200px;
        }
</style>