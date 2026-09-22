# NEON SNAKE // 赛博贪吃蛇

一个赛博朋克风格的网页贪吃蛇小游戏，纯 HTML + CSS + JavaScript 单文件实现，零依赖、零构建。

## 在线试玩

部署后访问：`https://<你的项目名>.vercel.app`

## 玩法

- **移动**：方向键 / WASD（手机可滑动屏幕或用虚拟方向键）
- **暂停**：空格键
- **重开**：Enter 或点击按钮
- 吃掉粉色能量核 +10 分，每满 50 分速度提升一级
- 撞墙或咬到自己则游戏结束，最高分自动保存在本地

## 特性

- 霓虹发光蛇身 + 青紫渐变
- 脉动能量核食物 + 粒子爆炸特效
- CRT 扫描线 / 故障风（Glitch）标题 / 屏幕震动
- WebAudio 合成音效（吃食、死亡、开始）
- 响应式布局，支持手机触屏

## 本地运行

直接用浏览器打开 `index.html` 即可，无需任何安装。

## 部署（GitHub + Vercel）

```bash
git init
git add .
git commit -m "feat: 赛博贪吃蛇初版"
git remote add origin https://github.com/<你的用户名>/cyber-snake.git
git push -u origin main
```

然后到 [vercel.com](https://vercel.com) 用 GitHub 登录 → Add New Project → Import 本仓库 → Framework Preset 选 **Other** → Deploy。
