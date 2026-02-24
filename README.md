# Freedom Is Coming

基于 [freedom.gov](https://freedom.gov/) 内容主题的创意重新设计，采用 HTML + Three.js 构建的沉浸式单页体验。

![Three.js](https://img.shields.io/badge/Three.js-r170-black?logo=threedotjs)
![HTML](https://img.shields.io/badge/HTML5-single%20file-E34F26?logo=html5&logoColor=white)

## 预览

打开 `index.html` 即可运行，无需构建工具或本地服务器。

## 设计概念

**"Emergence"** — 琥珀色光芒从黑暗虚空中浮现，象征信息与自由的觉醒。

- 完全原创的视觉设计，仅保留原站的文案主题
- 温暖的琥珀/金色调（`#d4a060`）替代传统冷色科技风
- 电影级开场 + 交互式 3D 场景

## 技术特性

| 特性 | 实现方式 |
|------|----------|
| 3D 渲染 | Three.js + 自定义 GLSL 着色器 |
| 后处理 | UnrealBloomPass 辉光效果 |
| 粒子系统 | 4000 个螺旋上升的火焰粒子（GPU 动画） |
| 地面 | 着色器驱动的反射网格 + 脉冲涟漪波 |
| 轨道碎片 | 60 个环绕浮动的金属方块 |
| 文字精灵 | Canvas 纹理生成的漂浮关键词 |
| 开场动画 | CSS 幕帘分裂揭幕 |
| 交互 | 鼠标控制摄影机环绕，按钮触发冲击波 |

## 交互方式

- **移动鼠标** — 摄影机跟随环绕场景
- **点击 "Get Ready"** — 触发地面脉冲冲击波

## 字体

- **Syne** (800) — 标题展示字体
- **DM Sans** (300/400) — 正文/UI 字体

## 依赖

通过 CDN 加载，无需本地安装：

- [Three.js r170](https://threejs.org/)
- [Google Fonts](https://fonts.google.com/)

## 许可

仅供学习和创意展示用途。
