# dr.ego 产品站

DeepReach dr.ego 双目具身智能数据采集系统 (DR-H01) 产品网站。静态站点，无需构建。

## 目录

- `index.html` — 完整页面（中/英双语切换内置）
- `media/` — 产品图、实拍图、佩戴方案图
- `.nojekyll` — 关闭 GitHub Pages 的 Jekyll 处理

## 本地预览

```bash
python3 -m http.server 8000
# 打开 http://localhost:8000
```

## 部署到 GitHub Pages

Settings → Pages → Source: `Deploy from a branch` → Branch: `main` / `(root)`。
