# 智能技术分析平台 


## 产品概述
智能技术分析平台是面向科研机构、企业研发部门、政府科技管理单位的全栈式技术领域分析系统。基于 Vue 3 + Spring Boot 3 技术栈构建，通过整合专利、论文、项目三类核心数据，实现技术领域的**可视化图谱分析、趋势研判、竞争态势洞察**，并依托大语言模型自动生成深度分析报告，为技术决策、研发布局、竞争策略制定提供数据支撑。

### 核心价值
- **数据整合**：打破专利、论文、项目数据孤岛，构建统一的技术知识库
- **智能分析**：从人工分析到AI驱动，提升技术分析效率与深度
- **可视化呈现**：复杂技术数据转化为直观图表，降低分析门槛
- **决策支撑**：为技术选型、研发投入、竞争应对提供量化依据

## 目标用户
| 用户角色       | 核心需求                                  | 平台价值                                  |
|----------------|-------------------------------------------|-------------------------------------------|
| 科技管理者     | 掌握领域技术布局、竞争态势                | 全局技术图谱、竞争分析报告                |
| 研发人员       | 了解技术发展趋势、热点方向                | 趋势分析、关键词关联网络                  |
| 科研管理人员   | 管理科研数据、生成分析报告                | 数据批量导入、AI报告自动生成              |
| 企业战略分析师 | 研判技术竞争格局、制定研发策略            | 多维度对比分析、技术成熟度评估            |

## ✨ 核心功能
### 1. 技术图谱可视化
- **全球技术分布地图**：交互式展示各国家/地区技术布局，支持下钻查看细分领域
- **技术热点图谱**：基于关键词热度呈现领域核心技术、新兴技术
- **多维度筛选**：按时间、技术类型、主体类型等维度过滤图谱数据

### 2. 技术趋势分析
- **时间序列分析**：展示技术从萌芽到成熟的全生命周期发展曲线
- **年度趋势对比**：多年度技术热度、申请量、研究投入对比
- **技术成熟度评估**：基于专利/论文/项目数据自动评估技术成熟度阶段

### 3. 技术关联网络
- **关键词共现网络**：展示技术术语间的关联强度，挖掘潜在技术组合
- **三层关联网络**：打通专利-论文-项目数据，展示技术落地全链路
- **生态关系图**：呈现技术供给方、需求方、研究机构的生态关系

### 4. AI智能报告生成
- **一键生成报告**：选择技术领域后，自动生成2000字深度分析报告
- **自定义模板**：支持管理员配置报告模板，适配不同场景需求
- **多格式导出**：报告支持在线预览、Markdown格式下载

### 5. 数据管理（管理员）
- **批量数据导入**：支持Excel格式的专利/论文/项目数据批量上传
- **数据验证预览**：导入前校验数据格式，预览数据完整性
- **数据检索管理**：支持多条件筛选、关键词搜索，管理全量数据

### 6. 系统管理
- **用户权限管控**：基于角色的权限管理（普通用户/管理员），细粒度控制功能访问
- **AI配置管理**：管理员可配置大模型API地址、密钥、模型参数
- **系统参数设置**：自定义Token有效期、数据缓存策略等

## 产品优势
| 维度         | 平台优势                                  | 传统分析方式对比                          |
|--------------|-------------------------------------------|-------------------------------------------|
| 效率         | 分钟级生成分析报告，自动化数据处理        | 人工整理数据，数天完成一份分析报告        |
| 全面性       | 整合专利+论文+项目三类核心数据            | 单一数据源分析，视角片面                  |
| 可视化       | 交互式图谱，支持多维度探索                | 静态图表，难以深度交互                    |
| 智能化       | AI驱动的深度分析，挖掘潜在技术关联        | 人工经验判断，易遗漏关键信息              |
| 可扩展性     | 模块化架构，支持新增数据源、分析维度      | 定制化开发，扩展成本高                    |

### 基础操作流程
#### 普通用户
1. 登录平台（默认账号：user / 密码：user123）
2. 在「技术分类」模块选择目标领域（如人工智能、半导体）
3. 查看「技术图谱」了解整体布局
4. 进入「趋势分析」查看技术发展脉络
5. 点击「生成报告」获取AI深度分析报告

#### 管理员
1. 登录平台（默认账号：admin / 密码：admin123）
2. 进入「管理后台」→「数据导入」上传Excel格式的技术数据
3. 进入「系统设置」配置AI API信息（确保报告生成功能可用）
4. 管理用户账号、配置系统参数

## 典型使用场景
### 场景1：企业研发方向决策
> 某科技企业欲布局新能源领域，需明确研发重点方向
- 操作：选择「新能源」技术分类，查看技术热点图谱、趋势分析
- 输出：识别出储能、氢能源为高增长领域，AI报告给出研发投入优先级建议
- 价值：避免盲目投入，聚焦高潜力技术方向

### 场景2：政府科技政策制定
> 某地方科技局需制定本地半导体产业扶持政策
- 操作：筛选本地企业专利/项目数据，对比全国技术布局
- 输出：明确本地技术短板、优势领域，生成政策建议报告
- 价值：政策制定基于量化数据，精准扶持核心领域

### 场景3：科研机构项目申报
> 某高校欲申报国家级科研项目，需论证项目创新性
- 操作：分析目标方向的专利/论文分布，生成技术成熟度报告
- 输出：明确项目创新点、差异化优势，支撑申报材料撰写
- 价值：提升项目申报成功率，突出技术创新性

---


# 细节如下：
一个基于 Vue 3 + Spring Boot 3 的全栈技术分析系统，用于对技术领域进行细粒度分析，包括技术内容、技术布局、技术研发和技术生态分析。系统通过采集专利、论文和项目数据，构建领域技术知识库，分析国内外竞争态势，生成智能分析报告。

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Vue](https://img.shields.io/badge/Vue-3.4-blue)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.2-brightgreen)
![MySQL](https://img.shields.io/badge/MySQL-8.0-orange)

---

## 📋 目录

- [功能特性](#功能特性)
- [技术栈](#技术栈)
- [快速开始](#快速开始)
- [详细配置](#详细配置)
- [使用指南](#使用指南)
- [项目结构](#项目结构)
- [API 文档](#api-文档)
- [常见问题](#常见问题)
- [开发指南](#开发指南)
- [许可证](#许可证)
---

## ✨ 功能特性

### 🎯 核心功能

1. **📊 技术图谱可视化**
   - 交互式技术分布地图
   - 全球技术热点展示
   - 多维度数据可视化

2. **📈 趋势分析**
   - 技术发展时间序列分析
   - 年度趋势对比
   - 技术成熟度分析

3. **🔗 关联网络**
   - 技术关键词共现网络
   - 三层关联网络（专利-论文-项目）
   - 技术生态关系图

4. **🤖 AI 智能报告生成**
   - 基于大语言模型的报告生成
   - 自定义报告模板
   - 2000字深度分析报告

5. **👥 用户管理**
   - 用户注册/登录
   - JWT 身份认证
   - 角色权限管理（普通用户/管理员）

6. **📥 数据管理（管理员）**
   - Excel 数据批量导入
   - 专利/论文/项目数据管理
   - 数据预览与验证

7. **⚙️ 系统配置（管理员）**
   - AI API 密钥配置
   - 系统参数设置
   - 模板文件管理

---

## 🛠 技术栈

### 前端技术

| 技术 | 版本 | 说明 |
|------|------|------|
| **Vue** | 3.4 | 渐进式 JavaScript 框架 |
| **TypeScript** | 5.3 | 类型安全的 JavaScript 超集 |
| **Vite** | 5.0 | 下一代前端构建工具 |
| **Pinia** | 2.1 | Vue 官方状态管理库 |
| **Vue Router** | 4.2 | Vue 官方路由管理器 |
| **Element Plus** | 2.4 | Vue 3 UI 组件库 |
| **ECharts** | 5.4 | 强大的数据可视化库 |
| **Tailwind CSS** | 3.4 | 原子化 CSS 框架 |
| **Axios** | 1.6 | HTTP 客户端库 |

### 后端技术

| 技术 | 版本 | 说明 |
|------|------|------|
| **Spring Boot** | 3.2 | Java 企业级应用框架 |
| **Spring Security** | 6.x | 安全框架 |
| **MyBatis-Plus** | 3.5 | MyBatis 增强工具 |
| **MySQL** | 8.0+ | 关系型数据库 |
| **JWT** | 0.12 | JSON Web Token 认证 |
| **Apache POI** | 5.2 | Excel 文件处理 |
| **Jackson** | - | JSON 处理 |

### 开发工具

- **Maven** 3.8+ - Java 项目构建工具
- **Node.js** 18+ - JavaScript 运行时
- **npm** - 包管理器

---

## 🚀 快速开始

### 环境要求

- **JDK** 17+
- **Node.js** 18+ (推荐 20 LTS)
- **MySQL** 8.0+
- **Maven** 3.8+

### 1. 克隆项目

```bash
git clone <repository-url>
cd techanalysis
```

### 2. 数据库初始化

```bash
# 登录 MySQL
mysql -u root -p

# 执行初始化脚本
mysql -u root -p < backend/src/main/resources/db/init.sql

# 执行性能优化索引
mysql -u root -p tech_analysis < backend/src/main/resources/db/V2__add_performance_indexes.sql
```

### 3. 配置后端

编辑 `backend/src/main/resources/application.yml`：

```yaml
spring:
  datasource:
    url: jdbc:mysql://localhost:3306/tech_analysis?useUnicode=true&characterEncoding=utf-8&serverTimezone=Asia/Shanghai
    username: root              # 修改为你的数据库用户名
    password: your_password     # 修改为你的数据库密码

jwt:
  secret: your-secret-key       # 修改为你的 JWT 密钥
  expiration: 86400000          # Token 有效期（毫秒）
```

### 4. 启动后端

```bash
cd backend
mvn clean install -DskipTests
mvn spring-boot:run
```

后端启动成功后，访问：http://localhost:8080

### 5. 启动前端

```bash
cd frontend
npm install
npm run dev
```

前端启动成功后，访问：http://localhost:5173

### 6. 默认账户

| 用户名 | 密码 | 角色 |
|--------|------|------|
| admin | admin123 | 管理员 |
| user | user123 | 普通用户 |

⚠️ **首次登录后建议立即修改密码！**

---

## 📖 详细配置

### 后端配置

#### application.yml 主要配置项

```yaml
server:
  port: 8080                    # 后端服务端口

spring:
  datasource:
    url: jdbc:mysql://localhost:3306/tech_analysis
    username: root              # 数据库用户名
    password: your_password     # 数据库密码
    hikari:
      maximum-pool-size: 20     # 连接池最大连接数
      minimum-idle: 5           # 连接池最小空闲连接数

jwt:
  secret: your-secret-key       # JWT 签名密钥
  expiration: 86400000          # Token 有效期（24小时）

logging:
  level:
    com.techanalysis: INFO      # 日志级别
```

### 前端配置

#### API 基础地址

如果需要修改后端 API 地址，编辑 `frontend/src/api/request.ts`：

```typescript
const request = axios.create({
  baseURL: '/api',              // API 基础路径
  timeout: 120000               // 请求超时时间（毫秒）
})
```

### AI 报告生成配置

1. 登录系统（管理员账户）
2. 进入「系统设置」页面
3. 配置 AI API 信息：
   - **API URL**: 大模型 API 地址（如：`https://open.bigmodel.cn/api/paas/v4/chat/completions`）
   - **API Key**: 大模型 API 密钥
   - **模型名称**: 使用的模型（如：`glm-4-flash`）

### 报告模板配置

报告模板文件位于：
- **提示词模板**: `backend/src/main/resources/templates/report-prompt.template`
- **回退模板**: `backend/src/main/resources/templates/report-fallback.template`

修改模板文件后，需要重启后端服务生效。

---

## 📚 使用指南

### 用户端功能

#### 1. 登录/注册

- 访问系统首页，点击「登录」
- 输入用户名和密码登录
- 新用户可点击「注册」创建账户

#### 2. 选择技术分类

1. 登录后，点击「分类」或访问「分类选择」页面
2. 选择要分析的技术领域（如：人工智能、机器学习等）
3. 选择后自动跳转到相关分析页面

#### 3. 查看技术图谱

- 访问「技术图谱」页面
- 查看全球技术分布地图
- 交互式探索技术热点
- 查看各国技术竞争态势

#### 4. 趋势分析

- 访问「趋势分析」页面
- 查看技术发展时间序列
- 对比不同年份的技术趋势
- 分析技术成熟度

#### 5. 关联网络

- 访问「关联网络」页面
- 查看技术关键词共现关系
- 探索专利-论文-项目三层关联
- 分析技术生态关系

#### 6. 生成 AI 报告

1. 选择技术分类后，访问「报告生成」页面
2. 点击「生成报告」按钮
3. 等待 1-2 分钟，系统自动生成 2000 字的技术分析报告
4. 报告生成后可：
   - 预览报告内容
   - 保存报告到数据库
   - 下载报告为 Markdown 文件

#### 7. 搜索功能

- 在搜索框输入关键词
- 支持搜索专利、论文、项目
- 使用多条件筛选
- 查看详细数据信息

### 管理员功能

#### 1. 数据导入

1. 登录管理员账户
2. 访问「管理后台」页面
3. 选择数据导入类型（专利/论文/项目）
4. 上传 Excel 文件
5. 预览数据并确认导入

**Excel 文件格式要求：**
- 专利数据：包含专利号、标题、摘要、申请人等字段
- 论文数据：包含标题、作者、摘要、关键词等字段
- 项目数据：包含项目名称、资助机构、执行机构等字段

#### 2. 系统配置

1. 访问「系统设置」页面
2. 配置 AI API 信息（URL、Key、模型）
3. 保存配置后即可使用 AI 报告生成功能

#### 3. 数据管理

- 查看导入的专利/论文/项目数据
- 支持数据搜索和筛选
- 查看数据统计信息

---

## 📁 项目结构

```
techanalysis/
├── backend/                          # 后端 Spring Boot 项目
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/
│   │   │   │   └── com/techanalysis/
│   │   │   │       ├── config/       # 配置类（安全、跨域等）
│   │   │   │       ├── controller/   # REST API 控制器
│   │   │   │       ├── service/      # 业务逻辑层
│   │   │   │       ├── repository/   # 数据访问层（Mapper）
│   │   │   │       ├── entity/       # 实体类
│   │   │   │       ├── dto/          # 数据传输对象
│   │   │   │       └── util/         # 工具类
│   │   │   └── resources/
│   │   │       ├── application.yml   # 应用配置
│   │   │       ├── db/               # 数据库脚本
│   │   │       │   ├── init.sql      # 初始化脚本
│   │   │       │   └── V2__add_performance_indexes.sql  # 性能索引
│   │   │       └── templates/        # 报告模板文件
│   │   │           ├── report-prompt.template
│   │   │           └── report-fallback.template
│   │   └── test/                     # 测试代码
│   └── pom.xml                       # Maven 配置
│
├── frontend/                         # 前端 Vue 项目
│   ├── src/
│   │   ├── api/                      # API 接口定义
│   │   ├── components/               # 通用组件
│   │   ├── views/                    # 页面组件
│   │   ├── router/                   # 路由配置
│   │   ├── stores/                   # Pinia 状态管理
│   │   ├── assets/                   # 静态资源
│   │   ├── App.vue                   # 根组件
│   │   └── main.ts                   # 入口文件
│   ├── public/                       # 公共资源
│   ├── package.json                  # npm 配置
│   └── vite.config.ts                # Vite 配置
│
├── 资料/                             # 原始数据文件（Excel）
│   ├── 1-5w（国家）_中英实体关键词.xlsx
│   ├── 2024年专利_中英实体关键词.xlsx
│   ├── 2024年项目_中英实体关键词.xlsx
│   └── ...
│
├── README.md                         # 项目说明文档
└── 安装部署手册.md                   # 详细部署手册
```

---

## 📡 API 文档

### 认证相关

| 方法 | 路径 | 说明 | 权限 |
|------|------|------|------|
| POST | `/api/auth/login` | 用户登录 | 公开 |
| POST | `/api/auth/register` | 用户注册 | 公开 |
| GET | `/api/auth/profile` | 获取用户信息 | 需登录 |

### 分析相关

| 方法 | 路径 | 说明 | 权限 |
|------|------|------|------|
| GET | `/api/analysis/techmap` | 获取技术图谱数据 | 需登录 |
| GET | `/api/analysis/trend` | 获取趋势分析数据 | 需登录 |
| GET | `/api/analysis/competition` | 获取竞争态势数据 | 需登录 |
| GET | `/api/analysis/network` | 获取关联网络数据 | 需登录 |
| GET | `/api/analysis/hottech` | 获取热门技术数据 | 需登录 |

### 数据查询

| 方法 | 路径 | 说明 | 权限 |
|------|------|------|------|
| GET | `/api/patent` | 获取专利列表 | 需登录 |
| GET | `/api/paper` | 获取论文列表 | 需登录 |
| GET | `/api/project` | 获取项目列表 | 需登录 |
| GET | `/api/search` | 搜索数据 | 需登录 |

### 报告生成

| 方法 | 路径 | 说明 | 权限 |
|------|------|------|------|
| POST | `/api/report/generate` | 生成 AI 报告 | 需登录 |
| POST | `/api/report/save` | 保存报告 | 需登录 |
| GET | `/api/report/list` | 获取报告列表 | 需登录 |

### 管理功能（管理员）

| 方法 | 路径 | 说明 | 权限 |
|------|------|------|------|
| POST | `/api/admin/import/patent` | 导入专利数据 | 管理员 |
| POST | `/api/admin/import/paper` | 导入论文数据 | 管理员 |
| POST | `/api/admin/import/project` | 导入项目数据 | 管理员 |
| GET | `/api/config` | 获取系统配置 | 管理员 |
| POST | `/api/config` | 更新系统配置 | 管理员 |

---

## ❓ 常见问题

### 1. 后端启动失败

**问题：数据库连接失败**
```
Communications link failure
```

**解决方案：**
1. 确认 MySQL 服务已启动
2. 检查 `application.yml` 中的数据库配置
3. 确认数据库 `tech_analysis` 已创建
4. 确认数据库用户有足够的权限

**问题：端口被占用**
```
Port 8080 is already in use
```

**解决方案（Windows）：**
```powershell
# 查找占用端口的进程
netstat -ano | findstr :8080
# 结束进程
taskkill /PID <进程ID> /F
```

**解决方案（macOS/Linux）：**
```bash
# 查找占用端口的进程
lsof -i :8080
# 结束进程
kill -9 <PID>
```

### 2. 前端启动失败

**问题：依赖安装失败**
```
npm ERR! code ERESOLVE
```

**解决方案：**
```bash
# 清除缓存重试
npm cache clean --force
rm -rf node_modules package-lock.json
npm install
```

**问题：API 请求 CORS 错误**
```
Access to XMLHttpRequest blocked by CORS policy
```

**解决方案：**
1. 确认后端服务已启动
2. 检查后端 `CorsConfig.java` 配置
3. 确认前端请求的 API 地址正确

### 3. 数据库问题

**问题：中文乱码**

**解决方案：**
确保数据库使用 `utf8mb4` 编码：
```sql
ALTER DATABASE tech_analysis CHARACTER SET utf8mb4 COLLATE utf8mb4_unicode_ci;
```

**问题：`system_config` 表不存在**

**解决方案：**
```bash
# 执行数据库初始化脚本
mysql -u root -p tech_analysis < backend/src/main/resources/db/init.sql
```

### 4. AI 报告生成问题

**问题：报告生成失败，提示 API Key 未配置**

**解决方案：**
1. 使用管理员账户登录
2. 进入「系统设置」页面
3. 配置 AI API 信息（URL、Key、模型）
4. 保存配置后重新生成报告

**问题：报告字数不符合要求**

**解决方案：**
1. 检查提示词模板文件（`backend/src/main/resources/templates/report-prompt.template`）
2. 确保模板中明确要求 2000 字
3. 调整 `max_tokens` 参数（当前为 8192，可能需要增加到 ）
4. 修改模板后需要重启后端服务

### 5. 数据导入问题

**问题：Excel 文件导入失败**

**解决方案：**
1. 检查 Excel 文件格式是否符合要求
2. 确认文件大小不超过 500MB
3. 检查列名是否正确
4. 查看后端日志了解详细错误信息

---

## 🔧 开发指南

### 开发环境设置

1. **后端开发**
   ```bash
   cd backend
   mvn clean install
   mvn spring-boot:run
   ```

2. **前端开发**
   ```bash
   cd frontend
   npm install
   npm run dev
   ```

### 代码规范

- **后端**: 遵循 Java 编码规范，使用 MyBatis-Plus 进行数据库操作
- **前端**: 使用 TypeScript，遵循 Vue 3 Composition API 最佳实践

### 数据库迁移

当需要修改数据库结构时：
1. 创建新的 SQL 迁移脚本
2. 放在 `backend/src/main/resources/db/` 目录下
3. 按照版本号命名（如：`V3__xxx.sql`）
4. 手动执行迁移脚本

### 添加新功能？

1. **后端新功能**
   - 在 `controller` 包创建控制器
   - 在 `service` 包实现业务逻辑
   - 在 `repository` 包创建 Mapper 接口
   - 在 `entity` 包创建实体类

2. **前端新功能**
   - 在 `views` 包创建页面组件
   - 在 `api` 包定义 API 接口
   - 在 `router/index.ts` 添加路由配置
   - 如需状态管理，在 `stores` 包创建 store

### 构建生产版本

**后端：**
```bash
cd backend
mvn clean package -DskipTests
# 生成的 JAR 文件在 target/ 目录
java -jar target/tech-analysis-platform-1.0.0-SNAPSHOT.jar
```

**前端：**
```bash
cd frontend
npm run build
# 生成的静态文件在 dist/ 目录
```

---

## 🔐 安全建议

1. **生产环境部署**
   - 修改默认密码和 JWT 密钥
   - 使用 HTTPS 加密传输
   - 配置防火墙规则
   - 定期备份数据库

2. **API 安全**
   - 所有 API 都需要身份认证（除登录/注册）
   - 管理员接口需要额外的权限检查
   - 使用 JWT Token 进行身份验证

3. **数据安全**
   - 敏感信息不要硬编码在代码中
   - 使用环境变量管理配置
   - 定期更新依赖包修复安全漏洞


---

## 📄 许可证

本项目采用 MIT 许可证。详情请参阅 LICENSE 文件。

---

## 📞 技术支持

如有问题，请：
1. 查看本文档的「常见问题」部分
2. 查看后端日志（控制台输出）
3. 查看前端浏览器控制台（F12）
4. 检查数据库连接和配置

---

## 🎯 未来改进可能

- [ ] 支持更多数据源导入
- [ ] 增强报告生成功能
- [ ] 添加数据导出功能
- [ ] 支持多语言
- [ ] 添加数据可视化图表类型
- [ ] 性能优化和缓存改进

---

**最后更新**: 2026年1月  
**版本**: 1.0.0
