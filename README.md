# 贪吃蛇游戏 🐍

一个使用HTML5 Canvas和JavaScript开发的简单贪吃蛇游戏，可以在Vercel上轻松部署。

## 游戏特性

- 🎮 经典贪吃蛇游戏玩法
- 🎨 现代化的UI设计，支持响应式布局
- 📱 移动端友好
- 💾 本地存储最高分记录
- ⏸️ 暂停/继续功能
- 🔄 重新开始功能

## 游戏控制

- **方向键** - 控制蛇的移动方向
- **开始游戏** - 开始新游戏
- **暂停** - 暂停/继续游戏
- **重新开始** - 重置游戏

## 游戏规则

1. 使用方向键控制蛇的移动
2. 吃到红色食物可以增长身体并获得10分
3. 避免撞到墙壁或自己的身体
4. 游戏结束后可以查看最终得分和最高分

## 本地运行

1. 克隆或下载项目文件
2. 在项目目录中运行：
   ```bash
   npm install
   npm start
   ```
3. 在浏览器中打开 `http://localhost:3000`

## Vercel部署

### 方法一：通过Vercel CLI

1. 安装Vercel CLI：
   ```bash
   npm i -g vercel
   ```

2. 在项目目录中运行：
   ```bash
   vercel
   ```

3. 按照提示完成部署

### 方法二：通过GitHub

1. 将代码推送到GitHub仓库
2. 在[Vercel](https://vercel.com)上连接GitHub账户
3. 导入项目并部署

### 方法三：拖拽部署

1. 访问[Vercel](https://vercel.com)
2. 将项目文件夹拖拽到部署区域
3. 等待部署完成

## 项目结构

```
snake-game/
├── index.html          # 主HTML文件
├── style.css           # 样式文件
├── script.js           # 游戏逻辑
├── package.json        # 项目配置
├── vercel.json         # Vercel部署配置
└── README.md           # 说明文档
```

## 技术栈

- **HTML5** - 页面结构
- **CSS3** - 样式和动画
- **JavaScript (ES6+)** - 游戏逻辑
- **Canvas API** - 游戏渲染
- **LocalStorage** - 数据持久化

## 浏览器支持

- Chrome (推荐)
- Firefox
- Safari
- Edge

## 许可证

MIT License

## 贡献

欢迎提交Issue和Pull Request来改进这个项目！

---

享受游戏吧！🎮
