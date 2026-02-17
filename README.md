# 🔋 电池监控 Battery Monitor

一个轻量级的手机电池监控应用，可安装为 PWA 使用。

## 功能特性

- ⚡ **实时功率显示** - 计算并显示当前电池功率
- 📊 **电量变化曲线** - 可视化电池消耗趋势
- 📋 **历史记录** - 本地存储电池使用历史
- 🎨 **精美 UI** - 深色主题，现代化设计

## 安装使用

### 方法一：网页访问
直接访问部署后的 URL，将网页添加到主屏幕即可使用。

### 方法二：本地运行
```bash
# 使用任意静态服务器
npx serve .

# 或 Python
python -m http.server 8080
```

## 技术说明

- **PWA** - 可安装的 Web 应用
- **Battery Status API** - 获取电池信息
- **LocalStorage** - 本地数据存储
- **Canvas** - 绘制电量变化曲线

## 部署

可部署到任意静态托管服务：
- Vercel
- Netlify
- Cloudflare Pages
- GitHub Pages

## 兼容性

- Chrome / Edge (桌面 + 移动)
- 移动端浏览器 (Android / iOS Safari)
- 需要 HTTPS 或 localhost

## 截图

深色主题界面，实时显示：
- 电池电量 (百分比 + 可视化)
- 充电状态
- 当前功率 (瓦特)
- 温度 / 电压
- 电量变化曲线图
- 历史记录列表
