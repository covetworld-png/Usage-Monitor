# 用电量监控工具 (Usage Monitor)

一个用于记录、分析和对比历史用电情况的现代化Web应用，支持智能OCR识别账单和双视图数据分析。

## ✨ 主要功能

### 📊 数据管理
- **手动录入**: 支持按月录入用电量和电费数据
- **智能OCR**: 批量上传电费账单图片，自动识别并提取数据
- **数据导入**: 支持从文本文件导入历史数据
- **数据导出**: 导出所有数据为JSON格式

### 📈 双视图分析
- **月度对比分析**: 多年度用电量和电费对比，支持按年份筛选
- **阶梯累计分析**: 年度累计用电量与阶梯电价的突破点分析

### ⚙️ 阶梯电价设置
- 可自定义三阶梯电价标准
- 实时显示当前阶梯状态
- 阶梯突破点可视化

### 🎨 现代化界面
- 响应式设计，支持桌面和移动端
- 深色/浅色主题适配
- 平滑动画和交互效果

## 🚀 快速开始

### 在线使用
直接在浏览器中打开 `用电量.html` 文件即可使用，无需安装任何依赖。

### 本地部署
1. 克隆项目
```bash
git clone https://gitee.com/roobooo/Usage-Monitor.git
cd Usage-Monitor
```

2. 启动本地服务器
```bash
# 使用Python
python -m http.server 8000

# 或使用Node.js
npx http-server -p 8000

# 或直接在浏览器中打开HTML文件
```

3. 在浏览器中访问 `http://localhost:8000`

## 📖 使用指南

### 1. 阶梯电价设置
首次使用时，请根据当地电价政策设置阶梯电价标准：
- 第一阶梯：0-260度
- 第二阶梯：261-600度
- 第三阶梯：601度以上

### 2. 数据录入
#### 手动录入
在"手动添加"区域填写日期、用电量和电费金额。

#### OCR识别
1. 点击"批量AI识别"区域或拖拽多张账单图片
2. 系统自动进行OCR识别
3. 核对识别结果后选择要导入的记录

#### 文件导入
支持导入包含以下格式的文本文件：
```
2023-01 用电量：123.45度 电费：¥234.56
2023-02 用电量：145.67度 电费：¥267.89
```

### 3. 数据分析
- **月度对比分析**: 查看多年用电趋势，识别高峰和低谷月份
- **阶梯累计分析**: 分析年度用电在阶梯电价中的分布情况

## 🛠️ 技术栈

- **前端框架**: 原生HTML5 + CSS3 + JavaScript (ES6+)
- **UI框架**: Tailwind CSS
- **图表库**: Chart.js
- **OCR引擎**: Tesseract.js
- **图标库**: Font Awesome
- **数据存储**: LocalStorage (浏览器本地存储)

## 📱 浏览器支持

- Chrome 80+
- Firefox 75+
- Safari 13+
- Edge 80+

## 🤝 贡献指南

欢迎提交Issue和Pull Request来改进这个项目！

### 开发环境设置
1. Fork本项目
2. 克隆到本地
3. 在浏览器中直接编辑和测试
4. 提交PR

## 📄 许可证

本项目采用 MIT 许可证 - 查看 [LICENSE](LICENSE) 文件了解详情。

## 🙏 致谢

- 感谢 [Tesseract.js](https://github.com/naptha/tesseract.js) 提供OCR功能
- 感谢 [Chart.js](https://www.chartjs.org/) 提供图表可视化
- 感谢 [Tailwind CSS](https://tailwindcss.com/) 提供现代化UI组件

## 📞 联系方式

项目维护者: [roobooo](https://gitee.com/roobooo)

项目地址: https://gitee.com/roobooo/Usage-Monitor.git

---

**提示**: 所有数据存储在浏览器本地，不会上传到服务器，确保您的隐私安全。</content>
<parameter name="filePath">/Users/fangweijun/Documents/claude_code_projects/usage-monitor/README.md