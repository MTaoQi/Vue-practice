<template>
    <!-- 组件的结构 -->
    <div class = "demo">
      <h2>学校名称：{{name}}</h2>
      <h2>学校地址：{{address}}</h2>
      <button @click="showName">点我提示学校名字</button>
    </div>
</template>
<script>
// 组件交互相关的代码（数据、方法等等）
// ES6三种暴露方法详解https://blog.csdn.net/goutinga/article/details/109250386
//分别暴露  
//统一暴露
//默认暴露
export default {
    name:'School',
    data() {
      return {
        name: '尚硅谷',
         address: '北京昌平'
      }
   },
   methods: {
      showName() {
         alert(this.name)
      }
   },
}

</script>

<style>
/* 组件的样式 */
   .demo{
    background-color: orange;
   }
</style>



