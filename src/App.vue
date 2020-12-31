<!--
 * @Description: It was written by Pony
 * @Version: 2.0
 * @Autor: Pony
 * @Date: 2020-10-19 14:44:09
 * @LastEditors: Pony
 * @LastEditTime: 2020-10-19 16:13:20
-->
<template>
  <div>
    <Banner />
    <h3>bilibli首页banner</h3>
  </div>
</template>

<script>
import Banner from './components/Bannner.vue'

export default {
  name: 'App',
  components: {
    Banner
  }
}
</script>
<style >
* {
  margin: 0;
  padding: 0;
}
</style>