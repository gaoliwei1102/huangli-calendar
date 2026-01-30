# 老黄历日历 🧧

一个简洁美观的老黄历日历应用，支持每日宜忌查询和事件管理。

## 功能

- 📅 日历月视图，支持月份切换
- 🧧 每日宜忌、冲煞、吉神显示
- 📱 移动端优先设计，桌面端优化
- 💾 事件本地存储（LocalStorage）
- 🎋 传统中国红金配色
- ⚡ 轻量级，无后端依赖

## 技术栈

- 原生 HTML/CSS/JavaScript
- lunar-javascript 黄历计算库

## 快速开始

### 本地运行

```bash
# 方式一：直接用浏览器打开
open index.html

# 方式二：启动服务器
node server.js
# 访问 http://localhost:8001
```

## 访问地址

- 本地: http://localhost:8001
- 公网: http://<你的公网IP>:8001

## 项目结构

```
huangli-calendar/
├── index.html    # 主页面
├── server.js     # HTTP 服务器
└── README.md     # 说明文档
```

## 演示

![老黄历日历预览](./preview.png)

## License

MIT
