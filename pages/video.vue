<script setup lang="ts">
import { VideoPlayer } from '@videojs-player/vue'
import 'video.js/dist/video-js.css'
</script>

<template>
  <div>
    <VideoPlayer src="https://cdn.plyr.io/static/demo/View_From_A_Blue_Moon_Trailer-576p.mp4" controls plays-inline
      :height="500" :width="500" />
  </div>
</template>
