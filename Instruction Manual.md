# 专业化现代化商业化使用说明书：盘点大师Pro

## 中文版

### 产品概述
**盘点大师Pro** 是一款专业的硅片盘点计算工具，专为半导体制造行业设计。本工具通过精确的算法和直观的可视化界面，帮助用户高效管理盘点数据，实现精准计算和批量导出功能。

### 主要特性
- **本地数据存储**：所有数据存储在本地浏览器中，确保数据隐私和安全
- **自动销毁机制**：24小时后自动清除历史记录，保护敏感数据
- **实时计算**：输入数据即时计算，结果实时更新
- **多格式导出**：支持文本复制和文件下载，方便数据分享
- **多机台管理**：支持同时管理多达11个机台的盘点数据
- **数据可视化**：提供饼图、柱状图和环形图三种数据展示方式

### 系统要求
- 现代浏览器（Chrome 70+、Firefox 65+、Safari 12+、Edge 79+）
- JavaScript enabled
- 推荐屏幕分辨率：1920×1080或更高

### 快速入门

#### 1. 选择机台
从右上角"机台选择"下拉菜单中选择要盘点的机台编号（1#-11#）

#### 2. 设置舟内硅片数
- 选择标准舟内硅片数（默认17,472）
- 或选择"自定义"选项，输入缺失槽位数（0-112）
- 系统自动计算实际舟内硅片数

#### 3. 输入花篮数据
- **平台花篮**：输入A湿、A干、B湿、B干四个区域的数值
- **湿花篮**：输入A湿、B湿区域数值
- **干花篮**：输入A干、B干区域数值

#### 4. 查看计算结果
- 系统自动计算并显示：
  - 花篮内硅片总和（各花篮数量×104）
  - 最终硅片总量（舟内硅片数+花篮内硅片总和）

#### 5. 保存与导出
- 点击"保存结果"将当前计算保存到历史记录
- 点击"导出结果"可批量导出多机台数据

### 详细功能说明

#### 数据输入区域
- **机台选择**：支持11个机台的同时管理，数据独立存储
- **舟计算**：支持4种标准配置和自定义缺失槽位计算
- **花篮输入**：支持小数输入，保持原始数据精度

#### 可视化区域
- **数据概览**：直观显示当前各类花篮数量
- **图表展示**：三种图表类型展示数据分布
  - 饼图：比例分布视图
  - 柱状图：数量对比视图
  - 环形图：美观的比例展示

#### 数据管理
- **历史记录**：保存最近5次计算记录
- **24小时倒计时**：数据保存24小时后自动清除
- **批量导出**：支持多机台数据同时导出

#### 导出功能
- 格式化的文本输出，便于直接复制到报告
- 支持文本文件下载
- 可选择导出特定机台或全部机台数据

### 数据计算逻辑
1. 舟内硅片数 = (112 - 缺失槽位数) × 156
2. 花篮总和 = 平台花篮总和 + 湿花篮总和 + 干花篮总和
3. 花篮内硅片总和 = 花篮总和 × 104
4. 最终硅片总量 = 舟内硅片数 + 花篮内硅片总和

### 技术支持
- 开发者：Dou Changyou
- 邮箱：dcyyd_kcug@yeah.net
- 电话：+86 176 3396 3626
- GitHub：https://github.com/dcyyd

### 注意事项
- 本工具使用浏览器本地存储，清除浏览器数据会导致所有记录丢失
- 建议定期导出重要数据
- 数据在保存24小时后自动销毁，请及时备份

---

## English Version

### Product Overview
**Inventory Master Pro** is a professional silicon wafer inventory calculation tool designed for the semiconductor manufacturing industry. This tool helps users efficiently manage inventory data through precise algorithms and an intuitive visual interface, enabling accurate calculations and batch export functionality.

### Key Features
- **Local Data Storage**: All data is stored in the local browser, ensuring data privacy and security
- **Auto-Destruction Mechanism**: Automatic clearance of history records after 24 hours, protecting sensitive data
- **Real-time Calculation**: Instant calculation as data is entered, with real-time result updates
- **Multi-format Export**: Supports text copying and file downloading for easy data sharing
- **Multi-machine Management**: Supports simultaneous management of inventory data for up to 11 machines
- **Data Visualization**: Provides three data display methods: pie chart, bar chart, and doughnut chart

### System Requirements
- Modern browsers (Chrome 70+, Firefox 65+, Safari 12+, Edge 79+)
- JavaScript enabled
- Recommended screen resolution: 1920×1080 or higher

### Quick Start Guide

#### 1. Select Machine
Choose the machine number to inventory (1#-11#) from the "Machine Selection" dropdown in the upper right corner

#### 2. Set Boat Wafer Count
- Select standard boat wafer count (default 17,472)
- Or select "Custom" option and enter missing slots (0-112)
- System automatically calculates actual boat wafer count

#### 3. Enter Basket Data
- **Platform Baskets**: Enter values for A Wet, A Dry, B Wet, B Dry areas
- **Wet Baskets**: Enter values for A Wet, B Wet areas
- **Dry Baskets**: Enter values for A Dry, B Dry areas

#### 4. View Calculation Results
- System automatically calculates and displays:
  - Total wafers in baskets (basket count × 104)
  - Final total wafers (boat wafers + basket wafers)

#### 5. Save & Export
- Click "Save Results" to save current calculation to history
- Click "Export Results" to batch export multiple machine data

### Detailed Function Description

#### Data Input Area
- **Machine Selection**: Supports simultaneous management of 11 machines with independent data storage
- **Boat Calculation**: Supports 4 standard configurations and custom missing slot calculations
- **Basket Input**: Supports decimal input, maintaining original data precision

#### Visualization Area
- **Data Overview**: Intuitively displays current quantities of various basket types
- **Chart Display**: Three chart types to present data distribution:
  - Pie Chart: Proportional distribution view
  - Bar Chart: Quantity comparison view
  - Doughnut Chart: Aesthetic proportion display

#### Data Management
- **History Records**: Saves up to 5 recent calculations
- **24-hour Countdown**: Data automatically clears 24 hours after saving
- **Batch Export**: Supports simultaneous export of multiple machine data

#### Export Functionality
- Formatted text output for easy copying to reports
- Supports text file download
- Option to export specific machines or all machine data

### Data Calculation Logic
1. Boat wafers = (112 - Missing slots) × 156
2. Basket total = Platform basket total + Wet basket total + Dry basket total
3. Total wafers in baskets = Basket total × 104
4. Final total wafers = Boat wafers + Total wafers in baskets

### Technical Support
- Developer: Dou Changyou
- Email: dcyyd_kcug@yeah.net
- Phone: +86 176 3396 3626
- GitHub: https://github.com/dcyyd

### Important Notes
- This tool uses browser local storage; clearing browser data will cause all records to be lost
- Regularly export important data
- Data is automatically destroyed 24 hours after saving; please backup in time

---

**版权信息 © 2025 Dou CY. 保留所有权利。**
**Copyright © 2025 Dou CY. All rights reserved.**