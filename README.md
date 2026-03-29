# 🖼️ Typora Image Hosting

这是一个专为 **Typora** 笔记设计的 GitHub 图床仓库。

## ⚙️ 配置参考 (PicGo / Typora)

如果你需要在 PicGo 或其他工具中配置此仓库，请参考以下设置：

* **仓库名 (Repo):** `[你的GitHub用户名]/[你的仓库名]`
* **分支 (Branch):** `main`
* **存储路径 (Path):** `images/`
* **自定义域名 (Custom Domain):** `https://raw.githubusercontent.com/[你的GitHub用户名]/[你的仓库名]/main`

---

## 🚀 快速上手

1. **安装工具**：下载并安装 [PicGo](https://picgo.github.io/PicGo-Doc/) 或使用 Typora 内置的上传功能。
2. **生成 Token**：在 GitHub [Settings -> Developer settings -> Personal access tokens] 申请一个具有 `repo` 权限的 Token。
3. **配置 Typora**：
    * 进入 `偏好设置` -> `图像`。
    * 上传服务选择 `PicGo-Core` 或 `PicGo(app)`。
    * 勾选 `插入图片时...上传图片`。

## 📂 目录结构

```text
.
├── images/             # 统一存放所有笔记图片
│   └── 2026/           # 按年份分类（可选）
└── README.md           # 仓库说明
