- 快速开发
  选择starter
  .git 删除，
- 全家桶
  vue(mvvm) + vue-router + vuex + axios(负责和后端通信) 

- 先配vue-router 路由接管一切
./router/index.js  index.js 会补齐
- pages/
所有路由级别组件 都叫页面组件
alias 一下 在webpack.config.js 里修改alias   让路径可以自己设置

- less(预编译)  安装一下 yarn add less less-loader
- 更酷
  transition 的 
  v-enter(短) -> v-enter-active(transition时间) -> v-leave(短) -> v-leave-active(opacity:0,transition时间)