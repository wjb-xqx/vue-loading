<template>
  <div class="hellow">
      <!-- <div class="loading-container" v-show="!discList.length">
        	<loading></loading>
      </div> -->
      <!-- 数据没获取到之前显示竞争者加载。。。 -->
      <div class="loading-container">
        	<loading></loading>
      </div>
  </div>
</template>

<script>
import Loading from '@/base/loading/loading'
export default {
  name: 'HelloWorld',
  data () {
    return {
      discList:[{

      }]
    }
  },
  components: {
    Loading
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
