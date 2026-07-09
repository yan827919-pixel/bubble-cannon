# 泡泡大炮 — 抖音小游戏

## 项目文件说明

| 文件 | 用途 |
|------|------|
| `game.js` | 小游戏入口脚本，创建 WebView 加载游戏 |
| `game.json` | 小游戏配置（AppID 等） |
| `game.html` | 游戏本体（HTML5 页面） |
| `project.config.json` | IDE 项目配置 |
| `app.js` | 应用生命周期 |

## 上传步骤

### 1. 注册开发者账号
打开 https://developer.open-douyin.com 注册，创建小游戏应用，获取 **AppID**

### 2. 下载开发者工具
下载地址：https://developer.open-douyin.com/docs/resource/zh-CN/mini-game/develop/dev-tools/developer-instrument-update-and-download

### 3. 配置 AppID
打开以下文件，把 `请替换为你的AppID` 换成你的真实 AppID：
- `project.config.json`
- `game.json`

### 4. 导入项目
打开抖音开发者工具 → 导入项目 → 选择 `bubble_cannon_抖音小游戏` 目录

### 5. 预览调试
在工具中点击编译预览，扫码在手机上测试

### 6. 上传
工具栏点击「上传」→ 填写版本号 → 上传成功后到控制台提审

### 7. 提审
打开 https://microapp.bytedance.com 进入小游戏控制台 → 版本管理 → 提审

## 注意事项

- 首次使用需要先注册开发者账号
- WebView 模式在 iOS 和 Android 上表现一致
- 游戏使用 localStorage 自动存档，已桥接到小游戏缓存
- 如需修改游戏内容，编辑 `game.html` 文件即可
- 上传前请确认游戏已适配手机竖屏尺寸
