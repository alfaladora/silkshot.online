# silkshot.online – Instant Railgun Forge for Silksong

**Live**: https://silkshot.online  
**Tech**: Single static HTML (31 KB) – no build, no backend.

## 1. 一键部署（任意静态托管）
1. 下载 `index.html` + 可选 `/images/*.webp`
2. 上传到：
   - **Cloudflare Pages**（推荐 – 自动 HTTPS）
   - **GitHub Pages** / **Netlify** / **Vercel Static**
3. 绑定域名 → 强制 HTTPS → 完成

## 2. 合规要点
| 维度 | 状态 |
|---|---|
| 版权 | 仅嵌入官方 Wiki + 注明「Not affiliated」 |
| 隐私 | 无 Cookie、无表单、追踪代码已 `anonymize_ip` |
| 弹窗 | 0 第三方广告/弹窗，分享按钮为纯 `window.open` |
| 内容 | 全部原创，无抄袭官方文案 |

## 3. 统计代码
- **Plausible**: `data-domain="silkshot.online"`
- **Google Analytics**: `GTAG G-KRSM93TDXZ`（IP 匿名化）

## 4. 更新日志
| 日期 | 说明 |
|---|---|
| 2025-09-15 | 初版：单文件、无评论、合规、统计集成 |

## 5. 常见问题
**Q: 需要 Cookie 横幅吗？**  
A: 本页无功能性 Cookie，统计均为匿名，欧盟隐性同意模式即可。

**Q: 能否删除统计？**  
A: 直接删掉 `&lt;head&gt;` 内两段 `&lt;script&gt;` 即可零追踪。
