# 日结招工 - 商业演示材料

> 深圳日结招工人力资源平台

## 项目结构

```
iDayWorkDocs-pitch/
├── README.md           # 本文件
├── docs/               # 商业计划书、Markdown 源文件
│   └── business-plan.md
├── assets/             # 素材资源
│   ├── images/         # 图片、Logo、截图
│   └── data/           # 数据文件 (JSON/CSV)
├── ppt/                # PPT 源文件
├── html/               # HTML 演示 (Reveal.js 等)
└── dist/               # 输出产物 (PDF、最终HTML)
```

## 商业模型

- 工厂付: ¥25/h
- 工人拿: ¥18/h
- 差价: ¥7/h (毛利 28%)
- 工厂月结，公司垫资日发
- 意外险 ¥3/人/天 (工人自担)

## 盈亏平衡

- 300人规模
- 融资 ¥120万
- 预计6月回本

## 技术栈

- 前端: 微信小程序
- 后端: Rust (Axum) + PostgreSQL + Valkey
- 部署: 腾讯云 4C16G

---

*更新时间: 2026-05-31*
