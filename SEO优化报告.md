# 江苏陵匠建设工程有限公司官网 · SEO 基础优化报告

- 报告日期：2026-10-31
- 正式域名：https://lingjiangconstruction.com/
- 网站类型：单页应用（SPA），栏目使用 hash 路由
- 主要业务：深圳商业空间装修，涵盖办公室、餐饮、零售、酒店
- 核心关键词：深圳装修公司、深圳工装、深圳办公室装修、深圳工装室内设计、深圳工装室内施工

## 一、本次完成内容

| 项目 | 状态 | 说明 |
|---|---|---|
| 首页 Title | 已完成 | 使用指定的完整标题 |
| 首页 Meta Description | 已完成 | 包含公司简介与核心关键词 |
| 首页 Meta Keywords | 已完成 | 覆盖 5 个核心关键词及业务词 |
| 首页 H1 | 已完成 | 包含公司全称与“深圳商业空间装修专家” |
| Organization 结构化数据 | 已完成 | 位于 `<head>` 内，包含名称、Logo、地址、电话、邮箱、服务区域 |
| 各栏目 Title 后缀 | 已完成 | 案例、服务、关于、联系页统一追加“ \| 江苏陵匠建设工程有限公司” |
| robots.txt | 已完成 | 允许搜索引擎与常见 AI 爬虫抓取 |
| sitemap.xml | 已完成 | 当前提交唯一可独立收录的首页 URL |
| 独立 Logo 文件 | 已完成 | 新增 `logo.png`，用于 Organization 与社交分享 |
| 移动端适配检查 | 已完成 | 390px 宽度下 H1 与页面无横向溢出 |

## 二、首页 Title 与 Description

### Title

```text
江苏陵匠建设工程有限公司｜深圳商业空间装修专家｜办公室/餐饮/店铺/酒店装修
```

> 该标题按需求保留完整表述，约 38 个汉字。百度搜索结果中可能被截断，但核心关键词覆盖完整。

### Meta Description

```text
江苏陵匠建设工程有限公司，深圳装修公司，专注深圳工装与商业空间装修，提供深圳办公室装修、餐饮店铺、零售门店、酒店民宿装修及深圳工装室内设计、深圳工装室内施工一体化服务，透明报价、45天标准工期。
```

### Meta Keywords

```text
深圳装修公司,深圳工装,深圳办公室装修,深圳工装室内设计,深圳工装室内施工,商业空间装修,餐饮店铺装修,零售门店装修,酒店装修,陵匠建设,江苏陵匠建设工程有限公司
```

> 说明：百度、Google 对 `meta keywords` 的权重很低，本次按需求补齐，但不会把它作为主要排名手段。

## 三、页面对应 Title 清单

| 栏目 | Title |
|---|---|
| 首页 | 江苏陵匠建设工程有限公司｜深圳商业空间装修专家｜办公室/餐饮/店铺/酒店装修 |
| 案例展示 | 案例展示｜深圳商业空间装修案例 \| 江苏陵匠建设工程有限公司 |
| 服务与报价 | 服务与报价｜深圳工装室内设计施工 \| 江苏陵匠建设工程有限公司 |
| 关于我们 | 关于我们｜深圳商业空间装修公司 \| 江苏陵匠建设工程有限公司 |
| 联系我们 | 联系我们｜深圳商业空间装修咨询 \| 江苏陵匠建设工程有限公司 |

首页标题已经包含公司全称，因此没有重复追加公司后缀；其余 4 个栏目统一追加了指定后缀。

## 四、首页 H1

首页 H1 文本：

```text
江苏陵匠建设工程有限公司
深圳商业空间
装修专家
```

H1 同时包含：

- 公司全称：江苏陵匠建设工程有限公司
- 核心业务：深圳商业空间装修专家

原品牌语“以匠心，筑商业空间之美”保留为 H1 下方引导文案，不再占用 H1。

## 五、Organization 结构化数据

已放在首页 `<head>` 内，主要字段：

- `@type`：Organization
- `name` / `legalName`：江苏陵匠建设工程有限公司
- `alternateName`：陵匠建设、江苏陵匠
- `url`：https://lingjiangconstruction.com/
- `logo`：https://lingjiangconstruction.com/logo.png
- `description`：深圳工装与商业空间装修业务介绍
- `foundingDate`：2018
- `telephone`：+86-13332933761
- `email`：804954643@qq.com
- `address`：深圳市宝安区旭生融和中心 2 栋卓越共赢科创园（西乡项目）10 层 02 号
- `areaServed`：深圳、东莞、惠州、广州
- `knowsAbout`：深圳装修公司、深圳工装、深圳办公室装修、深圳工装室内设计、深圳工装室内施工等
- `contactPoint`：客服电话与邮箱

页面底部原有 `GeneralContractor` 结构化数据保留，用于补充本地商业装修服务信息。

## 六、robots.txt

文件：[robots.txt](robots.txt)

当前策略：

- `Baiduspider`、`Baiduspider-render`、`Baiduspider-image` 允许抓取
- `Googlebot`、`Bingbot`、搜狗、360、神马、字节等搜索引擎允许抓取
- `GPTBot`、`ChatGPT-User`、`OAI-SearchBot`、`ClaudeBot`、`PerplexityBot`、`Google-Extended`、`Applebot-Extended`、`CCBot` 等 AI 爬虫允许抓取
- 所有其他爬虫通过 `User-agent: *` 允许抓取
- 已声明 sitemap 地址

线上地址：

```text
https://lingjiangconstruction.com/robots.txt
```

## 七、sitemap.xml

文件：[sitemap.xml](sitemap.xml)

当前包含：

```text
https://lingjiangconstruction.com/
```

**重要说明：**

当前网站是单页应用，`#cases`、`#services`、`#about`、`#contact` 是同一个 HTML 页面内的锚点，不是独立可索引 URL。把 hash 地址写进 sitemap 通常不会被百度当作独立页面，因此本次只提交首页。

如果后续希望案例、服务、关于、联系四个页面分别进入百度索引，需要将 SPA 拆成独立静态页面，例如：

```text
https://lingjiangconstruction.com/cases/
https://lingjiangconstruction.com/services/
https://lingjiangconstruction.com/about/
https://lingjiangconstruction.com/contact/
```

拆分后再把这些真实 URL 加入 sitemap。

## 八、关键词布局

| 关键词 | 已布局位置 |
|---|---|
| 深圳装修公司 | Title、Description、Keywords、Organization、关于页 |
| 深圳工装 | Description、Keywords、H1 下方文案、服务页 |
| 深圳办公室装修 | Description、Keywords、案例/服务描述 |
| 深圳工装室内设计 | Description、Keywords、服务页 Title |
| 深圳工装室内施工 | Description、Keywords、服务页描述 |

建议后续围绕每个核心关键词补充独立内容页，而不是只依赖首页堆叠关键词。

## 九、技术检查

| 检查项 | 结果 |
|---|---|
| HTTPS 访问 | 通过 |
| canonical | 指向 https://lingjiangconstruction.com/ |
| 百度验证代码 | 已存在，位于 `<head>` 前部 |
| Organization JSON-LD | JSON 解析通过 |
| 页面 Title | 5 个栏目均有独立标题 |
| Meta Description | 5 个栏目均有独立描述 |
| Meta Keywords | 5 个栏目均有配置 |
| 移动端横向溢出 | 390px 下无溢出 |
| H1 数量 | 首页 1 个 H1 |
| robots.txt | 存在且允许抓取 |
| sitemap.xml | 存在且 XML 有效 |

## 十、仍需处理的事项

### 1. 部署本次修改
本地已修改，但需要把以下文件部署到 GitHub Pages 仓库根目录：

```text
index.html
robots.txt
sitemap.xml
logo.png
CNAME
```

部署后检查：

```text
https://lingjiangconstruction.com/
https://lingjiangconstruction.com/robots.txt
https://lingjiangconstruction.com/sitemap.xml
https://lingjiangconstruction.com/logo.png
```

### 2. 百度搜索资源平台
- 验证站点：`https://lingjiangconstruction.com/`
- 提交 sitemap：`https://lingjiangconstruction.com/sitemap.xml`
- 提交首页 URL
- 使用“抓取诊断”检查百度是否能正常抓取
- 使用“普通收录”提交首页

### 3. 开启 HTTPS 强制跳转
GitHub Pages 后台建议开启 **Enforce HTTPS**，确保 `http://` 自动跳转到 `https://`。

### 4. 页面性能
首页 HTML 约 3.7 MB，主要来自内嵌 Base64 图片。页面体积偏大，可能影响百度抓取和移动端体验。建议后续：

- 压缩案例图片为 WebP；
- 将图片改为独立静态资源，使用浏览器缓存；
- 减少首屏一次性加载的图片数量；
- 对非首屏图片使用懒加载。

### 5. 外链与内容
“被其他网站引用”必须由第三方网站发布链接，无法通过修改本站代码直接生成。建议：

- 使用 [友链交换文案.md](友链交换文案.md) 联系行业网站；
- 发布真实的项目案例文章；
- 在行业媒体、设计平台、园区和商业地产页面获得自然引用；
- 不要购买批量垃圾外链。

### 6. 单页应用限制
这是当前最大的 SEO 结构限制：

- 百度通常只索引首页；
- 5 个栏目共用同一个 Title 初始 HTML；
- 动态修改的 Title/Description 不保证被百度执行。

要真正实现“每个栏目都被收录”，建议下一步拆分为独立静态页面，并为每个页面设置独立 canonical、Title、Description 和 sitemap URL。

## 十一、结论

本次已完成基础 SEO 配置：Title、Description、Keywords、H1、Organization 结构化数据、robots.txt、sitemap.xml、页面标题后缀和移动端检查。

当前最需要继续推进的是：

1. 部署本次文件；
2. 百度后台验证并提交 sitemap；
3. 拆分单页应用，让案例、服务、关于、联系成为独立可收录页面；
4. 持续补充内容和外部引用。

SEO 收录和排名需要时间，本报告不承诺具体收录时间或排名结果。
