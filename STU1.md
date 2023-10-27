### 案例代码
```js
// React 语法核心
import React from 'react';
// 构建HTML（WebAPP）的核心
import ReactDOM from 'react-dom/client';

// 获取页面中 id 为 #root 的容器最为"根"容器
const root = ReactDOM.createRoot(document.getElementById('root'));

// 基于 Render 方法渲染我们编写的视图，把渲染后的内容全部插入到 #root 进行渲染
root.render(
    <div>
        React 学习
    </div>
);
```