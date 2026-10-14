# Web 页面部署

将 `web/index.html` 安装到 `/var/www/xiaobibi/index.html`，并按服务器已有 TLS 证书路径使用 `nginx-xiaobibi.conf` 配置站点。站点暂时只提供静态建设中页面；`/api/` 明确返回 404，待 API 服务上线后再单独增加反向代理。

部署后验证 `https://xiaobibi.21ido.com/` 返回页面、`https://xiaobibi.21ido.com/api/` 返回 404。当前仓库未包含后端服务。
