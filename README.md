# CHCNAV Web 设计规范

单页 Web 设计规范文档，适用于 GitHub Pages 部署。

## 本地预览

用浏览器直接打开 `index.html`，或使用本地服务器：

```bash
# Python 3
python3 -m http.server 8000

# 或 npx
npx serve .
```

然后访问 http://localhost:8000

## 部署到 GitHub Pages

1. 在 GitHub 新建仓库（例如 `CHCNAV_Design`），将本目录推上去。
2. 仓库设置：**Settings → Pages**
3. **Source** 选择 **Deploy from a branch**
4. **Branch** 选 `main`（或你的默认分支），**Folder** 选 **/ (root)**
5. 保存后等待构建，页面地址为：  
   `https://<你的用户名>.github.io/CHCNAV_Design/`

若仓库名为 `<用户名>.github.io`，则根目录的 `index.html` 会作为首页，地址为：  
`https://<用户名>.github.io/`

## 页面结构

- **色彩**：主色、语义色、文字色
- **字体与层级**：标题与正文字号、字重
- **间距体系**：4/8/16/24/32/48px
- **圆角与阴影**：组件圆角与阴影层级
- **组件示例**：按钮等基础组件

可根据项目需要增删区块或替换为你们的设计 token。
