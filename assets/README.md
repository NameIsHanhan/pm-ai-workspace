# 🎨 资源文件库（Assets）

> 本目录统一管理图片、原型图、流程图等项目资源文件，方便文档引用和团队协作。

---

## 📁 子文件夹说明

| 目录 | 用途 | 支持格式 |
|------|------|----------|
| `images/` | 图片素材 | `.png`, `.jpg`, `.svg`, `.webp` |
| `icons/` | 图标文件 | `.svg`, `.png`, `.ico` |
| `mockups/` | 原型图、设计稿 | `.png`, `.jpg`, `.fig`, `.sketch`, `.pdf` |
| `diagrams/` | 流程图、架构图源文件 | `.drawio`, `.puml`, `.mmd`, `.svg` |

## 📝 资源命名规范

```
[模块名]-[内容描述]-[版本号].扩展名
```

**示例**：

- `user-center-login-flow-v1.png`
- `order-module-er-diagram-v2.svg`
- `payment-page-mockup-v1.png`
- `dashboard-icon-set-v1.svg`

## 🔗 引用方式

在 Markdown 文档中引用资源：

```markdown
<!-- 相对路径引用 -->
![登录流程图](../assets/diagrams/user-center-login-flow-v1.png)

<!-- 从 PRD 文档引用 -->
![页面原型](../assets/mockups/payment-page-mockup-v1.png)
```

## 💡 管理建议

1. **版本管理**：资源更新时递增版本号，保留历史版本
2. **尺寸优化**：图片建议压缩后再上传，减少仓库体积
3. **格式选择**：流程图优先使用 SVG 格式（可缩放、可编辑）
4. **及时清理**：不再使用的资源及时删除或归档
