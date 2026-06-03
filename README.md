# 🌾 乡遇 · 农特产+乡村文旅售卖APP

<div align="center">

![乡遇Logo](https://s2.loli.net/2026/01/01/placeholder-logo.png)

**把田园装进口袋，让家乡走向世界**

[![Flutter](https://img.shields.io/badge/Flutter-3.19-02569B?logo=flutter)](https://flutter.dev)
[![Node.js](https://img.shields.io/badge/Node.js-20.x-339933?logo=node.js)](https://nodejs.org)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

</div>

---

## 📖 项目简介

**"乡遇"** 是一款专注于**农特产品电商**与**乡村文旅体验**的一站式移动应用。我们深度连接城市消费者与乡村优质资源，通过「农副文创商城」和「小众乡村打包旅游」两大核心业务，帮助农户增收致富，让用户发现并体验原汁原味的乡土中国。

### 🎯 核心价值

| 价值维度 | 说明 |
|---------|------|
| 🧑‍🌾 **助农兴农** | 产地直发，减少中间环节，让农户获得更高收益 |
| 🎨 **文化传承** | 挖掘非遗手工艺、地方文创，赋予农特产品文化内涵 |
| 🗺️ **深度体验** | 精选小众乡村旅行线路，拒绝千篇一律的景区打卡 |
| ♻️ **可持续** | 倡导绿色消费、生态旅游，助力乡村可持续发展 |

---

## 🏗️ 两大核心业务

### 1. 🛒 农副文创商城

将田间地头的优质农特产和手作文创，通过数字化的方式呈现给全国消费者。

![商城首页](https://s2.loli.net/2026/01/01/placeholder-mall-home.png)

#### 商品品类

```
🌱 生鲜果蔬    🥩 肉禽蛋奶    🍯 特产干货
🍵 茶饮酒酿    🧶 非遗手作    📦 文创周边
```

#### 核心功能

- **产地溯源** — 扫码查看农产品从种植到采摘的全流程溯源信息
- **农户故事** — 每款商品背后都有一个真实农户的创业故事
- **时令甄选** — 根据节气推荐当季最佳农产，不时不食
- **文创定制** — 支持企业/个人定制非遗手作礼品

![商品详情页](https://s2.loli.net/2026/01/01/placeholder-product-detail.png)
![产地溯源页](https://s2.loli.net/2026/01/01/placeholder-traceability.png)

---

### 2. ✈️ 小众乡村打包旅游

告别拥挤的热门景点，带用户走进那些藏在山水之间的绝美村落。

![旅游首页](https://s2.loli.net/2026/01/01/placeholder-travel-home.png)

#### 旅行产品形态

| 类型 | 时长 | 适合人群 |
|------|------|----------|
| 🏕️ 周末微度假 | 1-2天 | 都市白领、亲子家庭 |
| 🎋 深度体验游 | 3-5天 | 摄影爱好者、文化探索者 |
| 🎨 非遗研学营 | 5-7天 | 学生团体、手作爱好者 |
| 🌿 田园康养 | 7-15天 | 银发族、康养需求者 |

#### 服务链路

```
选线路 → 订行程 → 在地接站 → 民宿入住 → 体验活动 → 特产代发 → 返程评价
```

- **全程管家** — 每趟旅程配备在地管家，解决旅途中的一切问题
- **食宿全包** — 严选乡村特色民宿与地道农家菜，住得舒心吃得放心
- **体验工坊** — 插秧、采茶、制陶、扎染等在地手作体验
- **行李无忧** — 当地特产直接代发快递到家，轻装出行

![旅行详情页](https://s2.loli.net/2026/01/01/placeholder-travel-detail.png)
![民宿预订页](https://s2.loli.net/2026/01/01/placeholder-homestay.png)

---

## 🧩 APP功能架构

```
┌─────────────────────────────────────────────────────┐
│                    🏠 首页（个性化推荐）                │
├─────────────────────────────────────────────────────┤
│  ┌──────────┐  ┌──────────┐  ┌──────────┐          │
│  │ 🛒 商城   │  │ ✈️ 旅游   │  │ 👤 我的   │          │
│  │          │  │          │  │          │          │
│  │·商品浏览  │  │·线路浏览  │  │·订单管理  │          │
│  │·分类搜索  │  │·行程预订  │  │·收藏夹   │          │
│  │·购物车   │  │·民宿预订  │  │·地址管理  │          │
│  │·下单支付  │  │·体验预订  │  │·客服中心  │          │
│  │·物流跟踪  │  │·旅游攻略  │  │·设置     │          │
│  │·商品溯源  │  │·在地管家  │  │·成为农户  │          │
│  └──────────┘  └──────────┘  └──────────┘          │
├─────────────────────────────────────────────────────┤
│              🔔 消息中心 · 实时通知                    │
├─────────────────────────────────────────────────────┤
│  ┌──────────────────────────────────────────────┐   │
│  │            🧑‍💼 农户端 · 商家后台              │   │
│  │  商品管理 │ 订单处理 │ 收益结算 │ 店铺装修       │   │
│  └──────────────────────────────────────────────┘   │
├─────────────────────────────────────────────────────┤
│  ┌──────────────────────────────────────────────┐   │
│  │            🛠️ 运营后台 · 管理端               │   │
│  │  内容审核 │ 数据看板 │ 活动配置 │ 用户管理       │   │
│  └──────────────────────────────────────────────┘   │
└─────────────────────────────────────────────────────┘
```

![APP功能架构图](https://s2.loli.net/2026/01/01/placeholder-architecture.png)

### 技术架构

```
┌──────────────────────────────────────────────────┐
│                   客户端层                         │
│  Flutter (iOS / Android) · 微信小程序             │
├──────────────────────────────────────────────────┤
│                   接入层                           │
│  Nginx · API Gateway · WebSocket                 │
├──────────────────────────────────────────────────┤
│                   业务服务层                       │
│  ┌─────────┐ ┌─────────┐ ┌──────────┐           │
│  │ 用户服务 │ │ 商品服务 │ │ 订单服务  │           │
│  ├─────────┤ ├─────────┤ ├──────────┤           │
│  │ 支付服务 │ │ 旅游服务 │ │ 内容服务  │           │
│  ├─────────┤ ├─────────┤ ├──────────┤           │
│  │ 消息服务 │ │ 溯源服务 │ │ 营销服务  │           │
│  └─────────┘ └─────────┘ └──────────┘           │
├──────────────────────────────────────────────────┤
│                   基础设施层                       │
│  MySQL · Redis · Elasticsearch · OSS · MQ        │
└──────────────────────────────────────────────────┘
```

![技术架构图](https://s2.loli.net/2026/01/01/placeholder-tech-architecture.png)

---

## 📦 仓库目录结构

```
xiangyu-app/
├── client/                         # 客户端代码
│   ├── android/                    # Android 原生工程
│   ├── ios/                        # iOS 原生工程
│   └── lib/                        # Flutter 主代码
│       ├── common/                 # 公共组件 & 工具类
│       │   ├── components/         # 通用UI组件
│       │   ├── utils/              # 工具函数
│       │   └── config/             # 应用配置
│       ├── features/               # 功能模块（Feature-first）
│       │   ├── mall/               # 农副文创商城模块
│       │   ├── travel/             # 乡村文旅模块
│       │   ├── user/               # 用户中心模块
│       │   ├── farmer/             # 农户端模块
│       │   └── message/            # 消息模块
│       ├── router/                 # 路由管理
│       ├── store/                  # 状态管理
│       ├── api/                    # 接口请求层
│       └── models/                 # 数据模型
├── server/                         # 服务端代码
│   ├── gateway/                    # API 网关
│   ├── services/                   # 微服务
│   │   ├── user-service/           # 用户服务
│   │   ├── product-service/        # 商品服务
│   │   ├── order-service/          # 订单服务
│   │   ├── payment-service/        # 支付服务
│   │   ├── travel-service/         # 旅游服务
│   │   ├── content-service/        # 内容服务
│   │   ├── trace-service/          # 溯源服务
│   │   └── marketing-service/      # 营销服务
│   └── common/                     # 服务公共模块
├── admin/                          # 运营管理后台
│   ├── web/                        # Web管理端 (Vue3)
│   └── farmer-mini/                # 农户小程序端
├── docs/                           # 项目文档
│   ├── api/                        # API接口文档
│   ├── design/                     # 产品设计稿
│   └── deploy/                     # 部署文档
├── scripts/                        # 部署 & 构建脚本
├── database/                       # 数据库迁移脚本
├── .github/                        # GitHub CI/CD 配置
├── docker-compose.yml              # Docker 编排
├── Makefile                        # 常用命令集合
└── README.md                       # 本文件
```

---

## 🚀 运行部署教程

### 环境要求

| 环境 | 版本要求 |
|------|----------|
| Flutter | >= 3.19.0 |
| Dart | >= 3.3.0 |
| Node.js | >= 20.0.0 |
| MySQL | >= 8.0 |
| Redis | >= 7.0 |
| Docker | >= 24.0 |
| Docker Compose | >= 2.20 |

### 本地开发

#### 1. 克隆仓库

```bash
git clone https://github.com/your-org/xiangyu-app.git
cd xiangyu-app
```

#### 2. 启动后端服务

```bash
# 使用 Docker Compose 一键启动依赖服务
docker-compose up -d mysql redis elasticsearch

# 安装服务依赖并启动
cd server
npm install
npm run dev
```

#### 3. 启动客户端

```bash
cd client

# 安装 Flutter 依赖
flutter pub get

# 启动 APP（连接设备或模拟器）
flutter run

# 或者指定平台运行
flutter run -d ios      # iOS
flutter run -d android  # Android
```

#### 4. 启动管理后台

```bash
cd admin/web
npm install
npm run dev
```

### 环境变量配置

```bash
# server/.env
DATABASE_URL=mysql://root:password@localhost:3306/xiangyu
REDIS_URL=redis://localhost:6379
OSS_ENDPOINT=https://oss-cn-hangzhou.aliyuncs.com
OSS_BUCKET=xiangyu-prod
JWT_SECRET=your-secret-key

# client/.env
API_BASE_URL=http://localhost:3000/api/v1
MAP_KEY=your-amap-key           # 高德地图Key，用于乡村定位
WECHAT_APP_ID=your-wechat-app-id
```

### 生产部署

```bash
# 构建 Docker 镜像
docker-compose -f docker-compose.prod.yml build

# 启动生产环境
docker-compose -f docker-compose.prod.yml up -d

# 数据库迁移
npm run db:migrate:prod
```

> ⚠️ **注意**：生产环境请务必修改默认密钥、启用 HTTPS、配置防火墙规则。详细部署文档请参阅 [docs/deploy/](docs/deploy/)。

---

## 📸 项目效果图

> 以下图片均托管于国内高速图床，确保国内用户访问流畅。图片目录：`docs/screenshots/`

### 商城模块

| 商城首页 | 商品详情 | 购物车 |
|---------|---------|--------|
| ![商城首页](https://s2.loli.net/2026/01/01/placeholder-mall-home.png) | ![商品详情](https://s2.loli.net/2026/01/01/placeholder-product-detail.png) | ![购物车](https://s2.loli.net/2026/01/01/placeholder-cart.png) |

| 产地溯源 | 农户故事 | 订单支付 |
|---------|---------|----------|
| ![产地溯源](https://s2.loli.net/2026/01/01/placeholder-traceability.png) | ![农户故事](https://s2.loli.net/2026/01/01/placeholder-farmer-story.png) | ![订单支付](https://s2.loli.net/2026/01/01/placeholder-payment.png) |

### 旅游模块

| 旅游首页 | 线路详情 | 民宿预订 |
|---------|---------|----------|
| ![旅游首页](https://s2.loli.net/2026/01/01/placeholder-travel-home.png) | ![线路详情](https://s2.loli.net/2026/01/01/placeholder-travel-detail.png) | ![民宿预订](https://s2.loli.net/2026/01/01/placeholder-homestay.png) |

| 在地体验 | 行程管理 | 旅行攻略 |
|---------|---------|----------|
| ![在地体验](https://s2.loli.net/2026/01/01/placeholder-local-experience.png) | ![行程管理](https://s2.loli.net/2026/01/01/placeholder-trip-management.png) | ![旅行攻略](https://s2.loli.net/2026/01/01/placeholder-travel-guide.png) |

### 用户中心 & 农户端

| 个人中心 | 我的订单 | 农户后台 |
|---------|---------|----------|
| ![个人中心](https://s2.loli.net/2026/01/01/placeholder-profile.png) | ![我的订单](https://s2.loli.net/2026/01/01/placeholder-my-orders.png) | ![农户后台](https://s2.loli.net/2026/01/01/placeholder-farmer-dashboard.png) |

### 数据大屏（运营端）

![数据大屏](https://s2.loli.net/2026/01/01/placeholder-admin-dashboard.png)

---

## 🔧 技术栈

| 层级 | 技术选型 | 说明 |
|------|---------|------|
| 移动端 | **Flutter 3.19** | 跨平台高性能UI框架，一套代码双端运行 |
| 小程序 | **微信原生 + Taro** | 覆盖微信生态用户 |
| 管理后台 | **Vue 3 + Vite + Element Plus** | 现代化后台管理界面 |
| 后端框架 | **Node.js + NestJS** | 企业级微服务架构 |
| 数据库 | **MySQL 8.0** | 主数据库，InnoDB引擎 |
| 缓存 | **Redis 7.0** | 会话管理、热点数据缓存、分布式锁 |
| 搜索引擎 | **Elasticsearch 8.x** | 商品/旅游线路全文搜索 |
| 对象存储 | **阿里云 OSS** | 商品图片、游记内容静态存储 |
| 消息队列 | **RabbitMQ** | 订单异步处理、消息推送 |
| 地图服务 | **高德地图 API** | 乡村定位、线路导航、周边搜索 |
| 支付 | **微信支付 + 支付宝** | 双通道聚合支付 |
| CI/CD | **GitHub Actions** | 自动化构建、测试、部署流水线 |

---

## 🗺️ 产品路线图

```mermaid
gantt
    title 乡遇APP 产品路线图
    dateFormat  YYYY-MM
    axisFormat  %Y-%m

    section 一期 — MVP
    商城基础功能（浏览/下单/支付）    :done, v1, 2025-01, 2025-04
    用户注册登录体系                  :done, v1b, 2025-01, 2025-04
    旅游线路浏览与预订                :done, v1c, 2025-03, 2025-06

    section 二期 — 体验升级
    产地溯源系统                     :active, v2, 2025-07, 2025-10
    农户故事内容平台                 :v2b, 2025-08, 2025-11
    在地管家服务系统                 :v2c, 2025-09, 2025-11
    AI个性化推荐                     :v2d, 2025-10, 2025-12

    section 三期 — 生态拓展
    农户端小程序                     :v3, 2026-01, 2026-04
    社区UGC内容（游记/评测）          :v3b, 2026-02, 2026-05
    直播带货                         :v3c, 2026-04, 2026-07
    积分会员体系                     :v3d, 2026-05, 2026-08
```

---

## 📦 打包发布注意事项

### Android 打包

```bash
# 生成签名密钥（仅首次）
keytool -genkey -v -keystore xiangyu-release.keystore \
  -alias xiangyu -keyalg RSA -keysize 2048 -validity 10000

# 创建 key.properties 文件
# client/android/key.properties
storePassword=your-store-password
keyPassword=your-key-password
keyAlias=xiangyu
storeFile=xiangyu-release.keystore

# 构建 release APK / AAB
cd client
flutter build apk --release          # APK 格式
flutter build appbundle --release    # Google Play AAB 格式
```

**注意事项：**
- ⚠️ `key.properties` 和 `.keystore` 文件**切勿提交到 Git 仓库**，已加入 `.gitignore`
- 生产包务必使用独立签名密钥，不要使用 Debug 签名
- Google Play 上架需使用 AAB 格式，APK 仅用于国内应用市场分发
- 国内应用市场（华为、小米、OPPO、vivo、应用宝等）需逐个注册开发者账号并提交审核

### iOS 打包

```bash
# 构建 iOS release
cd client
flutter build ios --release

# 使用 Xcode  Archive 并上传
open ios/Runner.xcworkspace
# Product → Archive → Distribute App
```

**注意事项：**
- 需要 Apple Developer Program 会员（$99/年）
- 确认 `Info.plist` 中隐私权限描述完整（相机、定位、相册等）
- App Store 审核注意：电商类APP需提供完整的退换货政策说明
- 如有直播功能，需额外申请网络视听许可证相关资质

### 微信小程序发布

```bash
# 使用微信开发者工具打开
# admin/farmer-mini/ → 上传代码 → 提交审核
```

**注意事项：**
- 小程序类目需选择「电商平台」或「旅游服务」
- 涉及支付需开通微信支付商户号
- 用户生成内容（UGC）需接入内容安全检测API
- 小程序包体积限制：主包 ≤ 2MB，分包 ≤ 20MB

### 通用发布清单

| 检查项 | 说明 |
|--------|------|
| 🔑 API密钥 | 生产环境替换所有测试密钥 |
| 🌐 域名备案 | API域名需完成ICP备案 |
| 🔒 HTTPS | 全站强制HTTPS，证书使用Let's Encrypt或阿里云免费证书 |
| 📊 埋点 | 确认数据分析埋点已接入（友盟/神策） |
| 🛡️ 隐私协议 | APP首次启动展示《隐私政策》和《用户协议》 |
| 📝 资质文件 | 食品经营许可证（农产品销售）、旅行社业务经营许可证（旅游业务） |
| 🧪 测试覆盖 | 核心业务流程测试通过，无P0级Bug |
| 🚨 异常监控 | 接入Sentry或类似异常监控平台 |
| 📦 资源优化 | 图片压缩、代码混淆、分包加载优化 |
| 🔄 灰度发布 | 建议先1%→5%→20%→100%逐步放量 |

---

## 🤝 贡献指南

我们欢迎所有形式的贡献！请参阅 [CONTRIBUTING.md](CONTRIBUTING.md) 了解详细规范。

### 贡献流程

1. **Fork** 本仓库
2. 创建特性分支：`git checkout -b feat/amazing-feature`
3. 提交更改：`git commit -m 'feat: add amazing feature'`
4. 推送到分支：`git push origin feat/amazing-feature`
5. 提交 **Pull Request**

### Commit Message 规范

```
feat:     新功能
fix:      Bug修复
docs:     文档更新
style:    代码格式（不影响功能）
refactor: 重构
perf:     性能优化
test:     测试相关
chore:    构建/工具链相关
```

---

## 📄 开源协议

本项目基于 **Apache License 2.0** 开源协议发布，详见 [LICENSE](LICENSE) 文件。

```
Copyright 2025 乡遇开发团队

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```

> ⚠️ **免责声明**：本项目源代码可供学习、研究及商业使用。但项目中涉及的**品牌名称、Logo、商品图片、农户肖像**等数字资产的版权归原作者所有，未经授权不得用于商业目的。

---

## 📞 联系我们

| 渠道 | 联系方式 |
|------|----------|
| 📧 邮箱 | dev@xiangyu-app.com |
| 🌐 官网 | https://www.xiangyu-app.com |
| 📱 公众号 | 搜索「乡遇」关注我们 |
| 🐛 问题反馈 | [GitHub Issues](https://github.com/your-org/xiangyu-app/issues) |

---

<div align="center">

**🌾 乡遇 — 让每一次出发都有家的温度**

Made with ❤️ by 乡遇开发团队 | © 2025 XiangYu Team

</div>
