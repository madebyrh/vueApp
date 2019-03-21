<template>
  <div id="app">
    <!-- ここに先ほど作ったヘッダーを配置 -->
    <vue-header></vue-header>
    <time-line></time-line>
  </div>
</template>

<script>
import VueHeader from './components/Header'
import TimeLine from './components/TimeLine'

export default {
  components: {
    VueHeader,
    TimeLine
  }
}
</script>