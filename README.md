# 大熊猫之家 · 香港海洋公园 | Panda Family · Ocean Park Hong Kong

香港海洋公园六只大熊猫（乐乐、盈盈、加加、得得、安安、可可）的三语（简/繁/EN）介绍网站。
A trilingual (Simplified Chinese / Traditional Chinese / English) introduction site for the six giant pandas of Ocean Park Hong Kong.

**在线网址 / Live URL**: https://huiyahuiya123.github.io/hk-pandas/

## 仓库结构 / Repository Structure

```
index.html      页面入口 / Entry page
style.css       全部样式 / All styles
app.js          三语数据与交互逻辑 / i18n data & interactions
assets/
  img/          10 张图片（首页大图、6 只熊猫、3 张日常）/ 10 images
  fonts/        站酷快乐体 ZCOOL KuaiLe 字体（SIL OFL 开源许可）/ Font (SIL OFL)
```

## ⚠️ 首次部署还差一步 / One More Step Before First Deploy

代码文件（index.html / style.css / app.js）已经推送完成。图片和字体是二进制文件，需要你在 GitHub 网页上手动上传一次：

1. 从 Kimi 对话里的网站版本卡片下载「全部文件」压缩包（或此前交付的 `海洋公园大熊猫之家-网站发布包.zip`），解压得到 `assets` 文件夹；
2. 打开 https://github.com/huiyahuiya123/hk-pandas ，点击 **Add file → Upload files**；
3. 把解压出来的整个 `assets` 文件夹（包含 `img/` 和 `fonts/` 两个子文件夹）**拖进上传区域**，确认路径显示为 `assets/img/...` 和 `assets/fonts/...`；
4. 点击 **Commit changes**。

The code files are already in the repo. Upload the binary `assets` folder once via GitHub web (Add file → Upload files, drag the whole `assets` folder in).

## 开启 GitHub Pages / Enable GitHub Pages

1. 仓库页面 → **Settings** → 左侧 **Pages**；
2. **Source** 选择 **Deploy from a branch**，Branch 选 **main** / (root)，点 **Save**；
3. 等待 1–2 分钟，访问 https://huiyahuiya123.github.io/hk-pandas/

## 后续更新 / Future Updates

想更新网站内容时，直接在 Kimi 对话里说一声即可——代码改动会通过 GitHub 自动推送到本仓库，Pages 会在 1 分钟左右自动重新部署，无需手动操作。

## 许可 / License

- 字体 ZCOOL KuaiLe：SIL Open Font License 1.1（google/fonts 官方仓库）
- 图片：AI 生成的示意图片，仅作非营利介绍用途
- 本页面为粉丝自制介绍页，非香港海洋公园官方网站
