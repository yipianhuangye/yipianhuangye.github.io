# 快速开始

### 安装组件库
```bash
npm i laikang-ui;
```

### 引用组件库
> 在 main.js 中引用组件库

```javascript
// 全部引入
import 'laikang-ui/dist/css/index.css';
import LKUI from 'laikang-ui';
Vue.use(LKUI);

// 按需引入
import 'laikang-ui/dist/css/demo.css';
import { Demo } from 'laikang-ui';
Vue.use(Demo);
```

