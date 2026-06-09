# HY 质检通 (hy-qc)

> **Proprietary — © 2026 Haoyao / HY Saunas (Harry Zeng). All Rights Reserved.**
> This is private, proprietary software. Unauthorized copying, modification,
> distribution, or use is strictly prohibited. See [LICENSE](./LICENSE).

桑拿房 / 光波房产品质检系统。纯前端、零构建，浏览器内运行。

## 模块
- **质检拍照**（`index.html`）：按固定面拍照存档、瑕疵标注（类型快选 + 备注）、功能检查、智能化测试报告，一键导出规范命名的 `型号-编号.zip`（含 `质检备注.csv`）。
- **主管复检**（`supervisor.html`）：导入质检 ZIP 逐台复核、瑕疵复检（补复检后照片，全部修复才可判合格）、补拍包装箱照片、临时保存待终审（本机 IndexedDB）、生成主管复检报告。
- **汇总后台**（`admin.html`）：管理员查看云端汇总。

## 版权与归属
原始作者及权利人：Harry Zeng（Haoyao / HY Saunas）。首次创建 2026-06。
联系：Haoyaocorpsales@gmail.com
