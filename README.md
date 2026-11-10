# Personal homepage starter

这是一个可直接部署到 GitHub Pages 的静态个人主页。页面使用英文为主，保留一小段中文背景说明。

## 发布前必须替换

在 `index.html` 中搜索并替换：

- 姓名已设置为 `Zijian Wu`。
- 页面已写入公开邮箱 `xvfengnianwzj@gmail.com`。
- 页面身份已设置为 `sophomore at UESTC`。
- `YOUR_GOOGLE_SCHOLAR_URL`：创建 Google Scholar 主页后填入。
- `YOUR_ORCID_URL`、`YOUR_GITHUB_URL`：有对应主页时再填。

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
