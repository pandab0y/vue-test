<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <ul>
      <li>
        <video-player-box url="http://vjs.zencdn.net/v/oceans.mp4"
                          imgUrl="https://surmon-china.github.io/vue-quill-editor/static/images/surmon-1.jpg"/>
      </li>
      <br/>
      <li>
        <video-player-box url="https://f.us.sinaimg.cn/001DUIeGlx07tjpom09G010412037Spj0E020.mp4?label=mp4_720p&template=1280x720.23.0&Expires=1556097921&ssig=JqjKSmr3Oa&KID=unistore,video"
                          imgUrl=""/>
      </li>
      <br/>
      <li>
        <video-player-box url="https://f.us.sinaimg.cn/000PuCXwlx07tktgw4Qo01041202eZPG0E010.mp4?label=mp4_720p&template=1280x720.23.0&Expires=1556096912&ssig=d9w56dqsit&KID=unistore,video"
                          imgUrl=""/>
      </li>
      <br/>
      <li>
        <video-player-box url="https://f.us.sinaimg.cn/003qGFBclx07tjrG1o3u01041200rMBz0E010.mp4?label=mp4_hd&template=852x480.28.0&Expires=1556097776&ssig=sE64uJ0bFf&KID=unistore,video"
                          imgUrl=""/>
      </li>
      <br/>
    </ul>
  </div>
</template>

<script>
import VideoPlayerBox from '@/components/VideoPlayerBox'
export default {
  name: 'HelloWorld',
  components: {
    VideoPlayerBox
  },
  data () {
    return {
      msg: 'Welcome to My VideoPlayer'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
