<template>
  <div id="app">
    <video id="my_video_1" class="video-js vjs-default-skin" controls preload="auto" width="1920" height="1080" data-setup='{}'>
      <source :src="url" type="application/x-mpegURL">
    </video>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'app',
  // components: {
  //   HelloWorld
  // }
  data() {
    url: "https://ngestreaming.sit.kmutt.ac.th/INT101/2018-08-24_13-30_INT101-Meeting4-2_,SD,HD,.mp4.urlset/master.m3u8?ngetoken=4tuXvFiEE0oOe4ry07zb2Q&ngetime=1539774225"
  }
}
</script>

