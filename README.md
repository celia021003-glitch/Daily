# 小本 · 饮食 & 体重记录

一个完全离线可用的个人健康记录 App，单文件纯 HTML，无需服务器。

## 功能
- 体重记录 + 趋势折线图
- 喝水打卡
- 饮食记录（支持 AI 拍照自动识别）
- 生理期追踪
- 食材库 + 想吃清单
- 账单记录（支持计算表达式）
- 多清单管理
- 手帐（带胶带/贴纸装饰）
- 秘密星空空间
- 五套主题 + 自定义配色
- 数据导出/导入备份

## 部署（GitHub Pages）
1. 把这个仓库的 `index.html` 推送到 GitHub
2. 进入仓库 Settings → Pages → Branch 选 `main` → 目录选 `/ (root)` → Save
3. 等约 1 分钟，访问 `https://你的用户名.github.io/仓库名`

## AI 食物识别
在 App 内 ⚙️ 设置 → 填入 Anthropic API Key（在 console.anthropic.com 获取）
之后拍照即可自动识别食物、分量、热量并记录。

## 数据说明
数据存储在浏览器本地（IndexedDB），换设备前请在 ⚙️ 设置里导出备份。
