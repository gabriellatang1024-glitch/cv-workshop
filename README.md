# 用乐高积木玩转 AI 时代简历 · Workshop 2026

> **模块化简历 · 一份 JD 一次拼装 · LaTeX 驱动**
> 
> Harvad Li · Stockholm · 2026

---

## 📦 这个 Repo 里有什么

| 文件 | 用途 |
|---|---|
| `example.tex` | 完整示例简历（Alex Johnson）· 直接在 Overleaf 编译看效果 |
| `cvTemplate.tex` | 空白模板 · 所有内容用 `[占位符]` 标注 · 今天的练习从这里开始 |

---

## 🚀 快速开始 · Task 0

### 第一步 · 先 Fork 这个模板 Repo

打开：

```text
https://github.com/bluehawana/cv-workshop
```

点击右上角 **Fork**，把这个模板复制到你自己的 GitHub 账号下。

Fork 完成后，进入你自己的 repo，打开 **Actions** 页面。如果 GitHub 提示 workflows 需要启用，点击 **I understand my workflows, go ahead and enable them**。

### 第二步 · 从你自己的 GitHub clone 到本地

不要直接 clone `bluehawana/cv-workshop`。直接 clone 我的仓库、或者给我的仓库提 PR，都不算完成。

Fork 完以后，把下面的 `your-username` 换成你自己的 GitHub 用户名：

```bash
git clone https://github.com/your-username/cv-workshop.git
cd cv-workshop
```

### 第三步 · 在本地编辑

用 VS Code / Cursor 打开 `cvTemplate.tex`，把所有 `[占位符]` 换成你的真实信息：

- `[Your Full Name]` → 你的姓名
- `[Your Target Job Title]` → 你的目标职位
- `[Company Name 1]` → 你的公司名
- 以此类推

### 第四步 · Commit + Push `.tex`

```bash
git add cvTemplate.tex
git commit -m "my cv first version"
git push
```

### 第五步 · 在 Overleaf 编译 PDF，再 Push 回 GitHub

1. 打开 [overleaf.com](https://www.overleaf.com) → 登录 → **New Project → Blank Project**
2. 上传你改好的 `cvTemplate.tex`
3. 点击 **Compile**
4. 下载 PDF
5. 把 PDF 放进这个项目文件夹

然后：

```bash
git add your-name-cv.pdf
git commit -m "add compiled cv pdf"
git push
```

> 编译器选 **pdfLaTeX**（Overleaf 默认），无需额外配置。

---

## 🏆 Workshop 挑战 · Task 0 到 Task 4

闯关路径：

1. **Task 0** · Fork `bluehawana/cv-workshop`
2. **Task 1** · Clone 你自己账号下的 repo 到本地
3. **Task 2** · 修改 `cvTemplate.tex`
4. **Task 3** · Compile 成 PDF
5. **Task 4** · `git add` → `git commit` → `git push`

必须 push 到你自己的 GitHub repo，例如：

```text
https://github.com/your-username/cv-workshop
```

直接 clone 我的仓库、直接 push/PR 到 `bluehawana/cv-workshop`，GitHub Actions 不会认定为闯关成功。

如果你的 fork 里 Actions 没有启动，到你自己的 repo 的 **Actions** 页面启用 workflows，然后再 push 一次。

### 彩蛋怎么拿？

在 **2026-05-17 周日 23:59 Stockholm 时间之前**，只要你的 GitHub repo 里同时有：

- `.tex` 源文件
- 编译好的 `.pdf`

GitHub Actions 会自动检查。成功后它会在你的 commit status / commit comment 里发出知识共享群邀请链接：

```text
https://t.me/+kvfCBofvxek2YTBk
```

> 截止后 GitHub Actions 会自动失效，不再发邀请链接。

---

## 📋 所需工具清单

Workshop 结束后记得注册这些（没有的话）：

- [ ] Gmail — `firstname.lastname@gmail.com`
- [ ] GitHub — 用户名用真名简写
- [ ] LinkedIn — 自定义 URL
- [ ] Overleaf — 免费账号即可
- [ ] 个人域名 — `yourname.dev`（约 $9/年）

---

## 🔗 联系方式

| 渠道 | 地址 |
|---|---|
| LinkedIn | [linkedin.com/in/harvad](https://linkedin.com/in/harvad) |
| Email | info@hongyanab.com |
| Subcontract 机会 | [app.verama.com/en/job-requests](https://app.verama.com/en/job-requests) |

---

*Workshop · 2026 · Stockholm · 把今天拼出来的那块积木带回去，下周再拼一块。*
