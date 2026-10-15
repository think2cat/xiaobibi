# 校比比（Xiaobibi）

校比比是面向深圳市宝安区小学信息查询的项目，帮助用户按地址或小区查看学校基础信息、地图位置和招生资料。项目展示内容以公开资料整理为基础，仅作信息参考，不构成招生资格或录取承诺。

本仓库维护校比比官网静态页面和部署配置。

## 入口

- 官网：[xiaobibi.21ido.com](https://xiaobibi.21ido.com/)
- API 仓库：[think2cat/xiaobibi_api](https://github.com/think2cat/xiaobibi_api)
- 小程序仓库：[think2cat/xiaobibi_mp](https://github.com/think2cat/xiaobibi_mp)

### 小程序码

小程序码尚未纳入仓库。取得正式小程序码后，将以图片文件放入 `docs/miniprogram-code.png` 并在此处更新展示，避免使用失效或非官方二维码。

## 部署文件

- `web/index.html`：官网页面
- `deploy/nginx-xiaobibi.conf`：Nginx 站点配置
- `deploy/README.md`：部署与验证说明

## 版本历史

当前为建设中版本，尚未发布正式版本号。

| 日期 | 版本/提交 | 更新内容 |
|---|---|---|
| 2026-10-15 | `156bf37` | 增加敏感文件忽略规则，准备公开仓库 |
| 2026-10-14 | `c09ee4e` | 初始化官网建设中页面、Nginx 配置和部署说明 |

## 说明

官网当前只提供静态建设中页面，`/api/` 暂时返回 404。后端接口实现、数据库和学校数据服务将在 API 仓库中独立维护。
