# Personal homepage starter

这是一个可直接部署到 GitHub Pages 的静态个人主页。页面使用英文为主，保留一小段中文背景说明。

## 当前状态

姓名、公开邮箱和 UESTC 大二学生身份已经写入主页。页面目前只剩三个可选链接占位：

- `YOUR_GOOGLE_SCHOLAR_URL`：创建 Google Scholar 主页后填入。
- `YOUR_ORCID_URL`：有 ORCID 主页时再填入。
- `YOUR_GITHUB_URL`：有个人 GitHub 主页时再填入。

这些占位不影响主页访问或 OpenReview 的 Homepage URL 要求。

不要把患者资料、实验原始数据、内部路径或未公开论文材料放入网站。

## 本地预览

在此目录运行：

```powershell
python -m http.server 8000
```

浏览器打开 `http://localhost:8000/`。

## GitHub Pages

1. 在 GitHub 创建公开仓库，通常命名为 `<用户名>.github.io`。
2. 上传 `index.html` 和 `styles.css`。
3. 在仓库 Settings → Pages 中选择 `Deploy from a branch`、`main`、`/root`。
4. 公开链接通常是 `https://<用户名>.github.io/`。

GitHub 用户名和公开邮箱尚未从本地资料中确认，所以本轮只创建本地站点，没有创建仓库、推送或发布。
