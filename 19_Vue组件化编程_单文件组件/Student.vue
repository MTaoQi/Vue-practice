<template>
    <!-- 组件的结构 -->
    <div >
      <h2>学生姓名：{{name}}</h2>
      <h2>学生年龄：{{age}}</h2>
  
    </div>
</template>
<script>
// 组件交互相关的代码（数据、方法等等）
// ES6三种暴露方法详解https://blog.csdn.net/goutinga/article/details/109250386
//分别暴露  
//统一暴露
//默认暴露
export default {
    name:'Student',
    data() {
      return {
         name: '张三',
         age: 18
      }
   },

}

</script>



