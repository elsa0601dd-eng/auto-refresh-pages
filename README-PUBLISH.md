# 产品站发布说明（给 Due）

这个站是给 Creem 域名审核用的，必须先上线（有 HTTPS 的真实网址）才能提交审核。

## 发布前先改 2 个占位符（全站替换）
1. `[SELLER LEGAL NAME]` — 你的法定姓名（护照拼音），出现在条款、退款、页脚。发布前确认卖家名称准确。
2. `[YOUR EMAIL]` — 联系邮箱，建议与 Chrome 商店后台填的那个一致。
在文件夹里全局搜索这两个字符串替换即可，共出现在 index/terms/refund/privacy 四个页面。

## 发布到 GitHub Pages（免费、自带 HTTPS，约 5 分钟）
1. GitHub 新建一个仓库（名字随意，如 page-monitor-site），选 Public。
2. 把本文件夹里的全部文件（index.html、terms.html、refund.html、privacy.html、style.css、assets/）上传到仓库根目录。
3. 仓库 Settings → Pages → Source 选「Deploy from a branch」→ 分支 main、目录 /(root) → Save。
4. 一两分钟后访问 https://<你的用户名>.github.io/page-monitor-site/ 能打开即上线成功。
（若用自定义域名也行，但没必要，github.io 的地址足够过审。）

## 然后回 Creem 后台
在 Creem 后台按当前审核流程提交网站，并检查产品介绍、定价和政策页面。

## 注意
- 首页「Get it on the Chrome Web Store」按钮指向你的条目 ID（ccleacdacmfihchdiepppmddgakjpomj），
  商店审核通过前点开会是 404，通过后自动生效，不用改。
- Pro 页写的是「Coming soon / 未开售」，与实际一致；将来开售后把那段改成已开售即可。
