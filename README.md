## [vuex-save](https://github.com/BiYuqi/vuex-save)

> 自动本地化存储vuex数据, 解决刷新页面vuex数据丢失

## 安装 (Installation)
```js
npm install vuex-save -S
```
## 使用 (Usage)
```js
import vuexSave from 'vuex-save'

// store.js
const store = new Vuex.Store({
  state,
  mutations,
  plugins: [vuexSave({
    // set save mode
    // 默认为localStorage mode可不传
    mode: 'localStorage'
  })]
  // or
  // plugins: [vuexSave({
    // set save mode as sessionStorage
    // mode: 'sessionStorage'
  // })]
  // or 
  // plugins: [vuexSave()]
})
```
## TODO

```js
// 支持module定向存储
```
