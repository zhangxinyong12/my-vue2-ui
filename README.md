# my-vue-ui
## 创建自己的vue npm 组件仓库
1. yarn    
2. 修改package.json name '你自己的仓库名字'       
如果名字重复会提示错误信息。     
## 发布流程
1. npm run lib
2. package.json version 递增
3. npm login （只有第一次需要）
4. npm publish
## 使用

```
npm i my-vue2-ui -S


import MyUI from "my-vue2-ui";
import 'my-vue2-ui/lib/my-vue-ui.css';

Vue.use(MyUI);

```