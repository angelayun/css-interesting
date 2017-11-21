# vuex
* vuex中action不同于mutation的点
  1. Action提交的是mutation，而不是直接变更状态
  2. Action可以饮食任意异步操作
* store 实例会注入到根组件下的所有子组件中，且子组件可以通过 this.$store访问到状态对象
* vuex使用中的一些规则
  1. 提交mutation是更改状态的唯一方法，并且这个过程是同步的
  2. 异步逻辑都应该封装到action里面