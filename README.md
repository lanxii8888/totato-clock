# 番茄时钟 & 白噪音

一个简洁的番茄时钟和白噪音播放器，帮助你提高专注力和工作效率。

## 功能特性

### 🍅 极简番茄
- 番茄工作法计时器
- 自定义专注、短休息、长休息时间
- 完成番茄统计
- 任务输入功能
- 页面标题动态显示任务和时间
- 倒计时呼吸闪烁favicon

### 🌊 泡泡白噪音
- 7种自然白噪音：雨声、海浪、谈话声、鸟声、雷雨声、风声、电视机
- 独立音量控制
- 5种预设组合
- 优雅的渐变背景
- 响应式设计

## 在线体验

- **Vercel部署**：https://your-app.vercel.app/
- **GitHub Pages**：https://your-username.github.io/tomato-clock/

## 本地运行

```bash
# 克隆仓库
git clone https://github.com/your-username/tomato-clock.git
cd tomato-clock

# 使用任意静态服务器
npx serve public
# 或
python -m http.server 8000
```

## 构建Android APK

### 使用GitHub Actions（推荐）

1. Fork或克隆此仓库
2. 推送代码到GitHub
3. 进入Actions标签页
4. 点击"Build Android APK"工作流
5. 等待构建完成
6. 在Artifacts中下载APK

**触发方式**：
- 推送代码到main分支
- 在Actions页面手动触发

### 本地构建

```bash
# 安装依赖
npm install

# 同步到Android
npm run sync

# 构建APK
npm run build:android
```

## 项目结构

```
tomato-clock/
├── public/              # Web资源
│   ├── index.html       # 入口页面
│   ├── clock.html       # 番茄时钟
│   ├── noise.html       # 白噪音
│   ├── audio/          # 音频文件
│   └── svg/            # 图标资源
├── .github/
│   └── workflows/
│       └── build.yml    # GitHub Actions配置
├── capacitor.config.json # Capacitor配置
└── package.json         # 依赖管理
```

## 技术栈

- **HTML5** - 纯静态页面
- **CSS3** - 现代样式和动画
- **JavaScript** - 原生JS，无框架
- **Capacitor** - 跨平台打包
- **GitHub Actions** - 自动化构建

## 浏览器支持

- Chrome/Edge (推荐)
- Firefox
- Safari
- 移动端浏览器

## Android要求

- Android 5.0 (API 21) 或更高版本
- 互联网权限（访问在线资源）

## 快捷键

### 番茄时钟
- `Space` - 开始/暂停
- `R` - 重置
- `1-4` - 切换模式

### 白噪音
- `Space` - 全部播放/暂停
- `↑/↓` - 主音量调节
- `1-7` - 切换对应声音
- `Esc` - 全部停止

## 开源协议

MIT License - 自由使用、修改和分发

## 贡献

欢迎提交Issue和Pull Request！

## 链接

- [在线演示](https://your-app.vercel.app/)
- [问题反馈](https://github.com/your-username/tomato-clock/issues)
- [功能建议](https://github.com/your-username/tomato-clock/issues)

## 更新日志

### v1.0.0 (2024-02-20)
- 初始版本发布
- 番茄时钟功能
- 白噪音播放器
- 响应式设计
- GitHub Actions自动构建