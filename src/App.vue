<template>
  <div>
     <TopHead/>
     <MyHead/>
     <GoodVideo/>
     <DownVideo/>
     <CounterPlayer/>
     <OurAchievements/>
  </div>
</template>

<script>
import MyHead from './components/MyHead.vue'
import TopHead from './components/TopHead.vue';
import GoodVideo from './components/GoodVideo.vue'
import DownVideo from './components/DownVideo.vue'
import CounterPlayer from './components/CounterPlayer.vue'
import OurAchievements from './components/OurAchievements.vue';
export default {
  name: 'App',
  components: { MyHead, TopHead, GoodVideo, DownVideo, CounterPlayer,OurAchievements}
}
</script>

<style>
* {
  margin: 0;
}
</style>
