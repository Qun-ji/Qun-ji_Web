# Qun-ji_Web
# 宠物健康管理Web端项目

## 项目说明
本项目是一个宠物健康管理Web端应用，旨在为宠物主人提供一站式的宠物健康管理解决方案。它集成了宠物健康数据监测、行为分析、环境监控以及位置追踪等功能，帮助主人更好地了解宠物的健康状况和生活环境。同时，还提供了系统设置和通知管理功能，方便用户个性化定制和接收重要提醒。

### 主要功能模块
1. **总览仪表盘**：展示宠物的健康状态速览、当日行为评分和环境监控数据，同时提供时间筛选器，可切换不同时间段的数据视图。
2. **健康数据中心**：呈现宠物的体温、心率、呼吸频率和活动量等健康数据，通过折线图直观展示数据变化趋势，并提供正常范围参考。
3. **行为监测中心**：利用雷达图展示宠物的睡眠时长、异常吠叫次数和活动强度等行为指标，同时提供相关视频记录，方便主人观察宠物行为。
4. **环境监控面板**：实时监测宠物生活环境的温度、湿度、空气质量和噪音水平等参数，显示环境监测设备的状态，并支持对在线设备进行操作。
5. **位置追踪系统**：通过地图展示宠物的当前位置和历史轨迹，设置电子围栏，当宠物超出安全区域时及时预警。

## 环境配置
### 前端依赖
本项目前端主要使用了 HTML、CSS 和 JavaScript 进行开发，并借助了以下第三方库和工具：
- **Chart.js**：用于生成健康数据折线图和行为监测雷达图，提供直观的数据可视化效果。
- **Tailwind CSS**：用于快速构建响应式和美观的用户界面，提供丰富的 CSS 类名。
- **Font Awesome**：用于引入图标，增强界面的视觉效果。

### 环境要求
- **浏览器**：建议使用 Chrome、Firefox、Safari 等现代浏览器，以确保最佳的用户体验。
- **网络**：需要稳定的网络连接，以加载第三方库和可能的地图数据。

## 运行方式
### 本地运行
1. **下载项目代码**：将本项目的代码克隆到本地，或者下载 ZIP 文件并解压。
```bash
https://github.com/Qun-ji/Qun-ji_Web/blob/main/PetCare_Web.html
```
2. **打开项目**：使用任意文本编辑器（如 Visual Studio Code）打开项目文件夹。
3. **运行项目**：在浏览器中直接打开 `index.html` 文件，即可看到宠物健康管理Web端的界面。

### 注意事项
- 由于项目中使用了外部链接的第三方库（如 Chart.js、Tailwind CSS 和 Font Awesome），请确保网络连接正常，否则可能会导致界面样式或图表显示异常。
- 项目中的部分图片（如 `grab.jpg`、`bark.jpg`、`quite.jpg` 和 `PetArk_loc2.jpg`）为占位图片，你可以根据实际情况替换为真实的图片。
- 项目中的地图部分使用了高德地图的链接，你可以根据需要修改为其他地图服务或集成地图 API 以实现更丰富的功能。

通过以上步骤，你就可以在本地运行宠物健康管理Web端项目，体验其各项功能。如果在运行过程中遇到任何问题，请随时在项目的 GitHub 仓库中提交 issue。

