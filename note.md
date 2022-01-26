### 初始化过程
```js
// 1. Vue.use(VueRouter) 
/* 
执行 router的install方法
在install中 注册了 router-link+router-view,通过vue.mixin,在每个组件的 beforeCreate中,执行了router的init方法,

*/

// 2. new Vue({router:new VueRouter({routes:[ xxxxxxx ]})})
/* 
 执行VueRouter的构造函数方法
  执行 createMatcher 合并用户传入的routes,构造格式化好的路由映射

*/



```