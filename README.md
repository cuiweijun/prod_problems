# 常见web问题
- vue中的App.vue组件中 ‘<img src="./assets/logo.png"/>’在前台页面中的路径下显示 src=[esmodule object]?
  - 原因是配置 file-loader 的时候，options 中的esModule:false 就可以了。