# 模板和示例

> 📝 **目标**：提供可复制的文档模板，提升创作效率

## 📋 模板使用指南

### 🎯 模板的作用

#### 为什么使用模板？
- **提升效率**：快速创建标准化文档
- **保证质量**：确保文档格式统一
- **降低门槛**：新手也能快速上手
- **减少错误**：避免常见的格式问题

#### 模板使用原则
1. **按需选择**：根据文档类型选择合适模板
2. **灵活调整**：根据实际需求调整模板内容
3. **保持更新**：定期更新模板以适应新需求
4. **规范使用**：严格按照模板规范填写内容

## 📁 核心文件模板

### 📑 _sidebar.md 模板

#### 基础模板

```markdown
<!-- _sidebar.md -->

* [产品概览](overview.md)

* Getting started
  * [快速上手](getting-started/quick-start.md)
  * [基础配置](getting-started/basic-config.md)
  * [常见问题](getting-started/faq.md)

* User Guidebook
  * [功能介绍](user-guide/features.md)
  * [操作指南](user-guide/operations.md)
  * [最佳实践](user-guide/best-practices.md)

* Advanced
  * [高级配置](advanced/advanced-config.md)
  * [API参考](advanced/api-reference.md)
  * [开发指南](advanced/development.md)

* FAQ
  * [常见问题](faq/common-issues.md)
  * [故障排除](faq/troubleshooting.md)
  * [技术支持](faq/support.md)

* [更新日志](changelog.md)
```

#### 使用说明

**文件位置**：每个文档目录的根目录

**命名规范**：必须命名为 `_sidebar.md`

**结构说明**：
- 使用 `*` 创建列表项
- 使用缩进创建子菜单
- 链接格式：`[显示名称](文件路径)`
- 支持多级嵌套（建议不超过3级）

**注意事项**：
```markdown
1. 文件路径必须相对于当前目录
2. 文件名不能包含空格，使用连字符分隔
3. 中文显示名称要简洁明了
4. 保持层级结构清晰合理
```

### 📄 overview.md 模板

#### 产品概览模板

```markdown
# 产品名称

> 📖 **简介**：用一句话描述产品的核心价值

## 🎯 产品概述

### 什么是 [产品名称]？

[产品名称] 是一个 [产品类型]，主要用于 [核心功能描述]。它可以帮助用户 [解决的问题] 和 [带来的价值]。

### 🌟 核心特性

- **特性1**：详细描述第一个核心特性
- **特性2**：详细描述第二个核心特性
- **特性3**：详细描述第三个核心特性
- **特性4**：详细描述第四个核心特性

### 🎨 产品优势

| 优势 | 说明 | 价值 |
|------|------|------|
| 易用性 | 简单直观的操作界面 | 降低学习成本 |
| 稳定性 | 高可用性和可靠性 | 保障业务连续性 |
| 扩展性 | 灵活的配置和扩展 | 适应业务发展 |
| 安全性 | 完善的安全保障 | 保护数据安全 |

## 🚀 快速开始

### 准备工作

在开始使用之前，请确保您已经：

- [ ] 完成账号注册和认证
- [ ] 获得必要的访问权限
- [ ] 准备好相关的配置信息
- [ ] 了解基本的操作概念

### 第一步：[操作名称]

1. 登录到 [平台名称]
2. 进入 [功能模块]
3. 点击 [操作按钮]
4. 完成 [具体操作]

> 💡 **提示**：如果遇到问题，请参考 [故障排除指南](faq/troubleshooting.md)

### 第二步：[操作名称]

1. 在 [位置] 找到 [功能入口]
2. 配置 [参数名称]
3. 保存并应用设置

### 第三步：[操作名称]

1. 验证配置是否生效
2. 测试核心功能
3. 查看运行状态

## 📚 学习路径

### 🔰 新手入门

1. **基础概念**：[基础概念介绍](getting-started/concepts.md)
2. **快速上手**：[快速上手指南](getting-started/quick-start.md)
3. **基础操作**：[基础操作教程](getting-started/basic-operations.md)

### 🎓 进阶学习

1. **高级功能**：[高级功能指南](advanced/advanced-features.md)
2. **最佳实践**：[最佳实践分享](user-guide/best-practices.md)
3. **案例研究**：[典型案例分析](examples/case-studies.md)

### 🔧 开发者资源

1. **API文档**：[API参考手册](advanced/api-reference.md)
2. **SDK下载**：[SDK和工具](advanced/sdk-tools.md)
3. **开发指南**：[开发最佳实践](advanced/development.md)

## 🆘 获取帮助

### 📖 文档资源

- **用户指南**：详细的功能说明和操作指导
- **API文档**：完整的接口文档和示例
- **FAQ**：常见问题和解决方案
- **更新日志**：产品更新和变更记录

### 💬 技术支持

- **在线客服**：工作日 9:00-18:00
- **技术论坛**：[论坛地址](https://forum.example.com)
- **邮件支持**：support@example.com
- **电话支持**：400-xxx-xxxx

### 🔗 相关链接

- [官方网站](https://www.example.com)
- [产品博客](https://blog.example.com)
- [开发者社区](https://developer.example.com)
- [状态页面](https://status.example.com)

---

📝 **最后更新**：2024年1月
```

#### 使用指导

**适用场景**：
- 产品首页介绍
- 功能模块概览
- 新用户引导页面

**填写要点**：
```markdown
1. 产品名称要准确一致
2. 简介要突出核心价值
3. 特性描述要具体明确
4. 快速开始要可操作
5. 学习路径要循序渐进
6. 联系方式要真实有效
```

## 🏷️ 高级样式模板

### 📑 Tabs 标签页模板

#### 基础用法

```html
<!-- tabs:start -->

#### **Windows**

在 Windows 系统上的操作步骤：

1. 打开命令提示符
2. 输入以下命令：
   ```cmd
   echo "Hello Windows"
   ```
3. 按回车执行

#### **macOS**

在 macOS 系统上的操作步骤：

1. 打开终端应用
2. 输入以下命令：
   ```bash
   echo "Hello macOS"
   ```
3. 按回车执行

#### **Linux**

在 Linux 系统上的操作步骤：

1. 打开终端
2. 输入以下命令：
   ```bash
   echo "Hello Linux"
   ```
3. 按回车执行

<!-- tabs:end -->
```

#### 高级用法

```html
<!-- tabs:start -->

#### **方案一：快速部署**

适合快速验证和测试的部署方案：

**优点**：
- 部署速度快
- 配置简单
- 资源消耗少

**缺点**：
- 功能有限
- 不适合生产环境

**部署步骤**：
1. 下载安装包
2. 解压到指定目录
3. 运行启动脚本

#### **方案二：标准部署**

适合生产环境的标准部署方案：

**优点**：
- 功能完整
- 性能稳定
- 支持扩展

**缺点**：
- 配置复杂
- 资源需求高

**部署步骤**：
1. 准备服务器环境
2. 安装依赖组件
3. 配置数据库
4. 部署应用程序
5. 配置负载均衡

#### **方案三：容器化部署**

基于Docker的容器化部署方案：

**优点**：
- 环境一致性
- 易于管理
- 支持自动扩缩容

**缺点**：
- 需要容器技术基础
- 初期学习成本高

**部署步骤**：
1. 准备Docker环境
2. 构建镜像
3. 编写docker-compose文件
4. 启动容器服务

<!-- tabs:end -->
```

### 🎨 提示样式模板

#### 信息提示

```markdown
> 💡 **提示**：这是一个有用的提示信息

> ⚠️ **注意**：这是需要注意的重要信息

> ❌ **警告**：这是警告信息，请谨慎操作

> ✅ **成功**：操作成功完成

> 📝 **说明**：这是详细的说明信息

> 🔍 **示例**：这是一个具体的示例
```

#### 复杂提示框

```markdown
> 💡 **最佳实践**
> 
> 在配置生产环境时，建议遵循以下原则：
> 
> 1. **安全第一**：启用所有安全特性
> 2. **性能优化**：根据负载调整参数
> 3. **监控告警**：设置完善的监控体系
> 4. **备份恢复**：建立可靠的备份机制

> ⚠️ **重要提醒**
> 
> 在执行以下操作前，请确保：
> 
> - [ ] 已备份重要数据
> - [ ] 已通知相关用户
> - [ ] 已准备回滚方案
> - [ ] 已获得必要授权
```

### 🔗 超链接样式模板

#### 基础链接

```markdown
<!-- 内部文档链接 -->
请参考 [快速上手指南](getting-started/quick-start.md) 了解详细信息。

<!-- 外部链接 -->
访问 [官方网站](https://www.example.com) 获取更多资源。

<!-- 锚点链接 -->
跳转到 [配置说明](#配置说明) 部分。
```

#### 高级链接样式

```markdown
<!-- 带图标的链接 -->
📖 [用户手册](user-guide/manual.md) | 🔧 [配置指南](config/guide.md) | 🆘 [故障排除](faq/troubleshooting.md)

<!-- 按钮样式链接 -->
[🚀 立即开始](getting-started/quick-start.md) [📚 查看文档](user-guide/overview.md) [💬 获取支持](support/contact.md)

<!-- 卡片样式链接 -->
| 📋 [基础教程](tutorials/basic.md) | 🎓 [进阶指南](tutorials/advanced.md) | 🔬 [实验功能](labs/experimental.md) |
|:---:|:---:|:---:|
| 适合新手用户 | 适合有经验用户 | 适合技术专家 |
```

### 📊 表格模板

#### 基础表格

```markdown
| 参数名称 | 类型 | 必填 | 默认值 | 说明 |
|----------|------|------|--------|------|
| name | string | 是 | - | 配置名称 |
| enabled | boolean | 否 | true | 是否启用 |
| timeout | number | 否 | 30 | 超时时间（秒） |
| retries | number | 否 | 3 | 重试次数 |
```

#### 对比表格

```markdown
| 功能特性 | 基础版 | 专业版 | 企业版 |
|----------|:------:|:------:|:------:|
| 用户数量 | 10 | 100 | 无限制 |
| 存储空间 | 1GB | 10GB | 100GB |
| API调用 | 1000/天 | 10000/天 | 无限制 |
| 技术支持 | 社区 | 邮件 | 电话+专属 |
| 价格 | 免费 | ¥99/月 | ¥999/月 |
```

#### 状态表格

```markdown
| 服务名称 | 状态 | 版本 | 最后更新 | 操作 |
|----------|------|------|----------|------|
| Web服务 | 🟢 运行中 | v2.1.0 | 2024-01-15 | [重启](actions/restart.md) |
| 数据库 | 🟢 运行中 | v8.0.32 | 2024-01-14 | [备份](actions/backup.md) |
| 缓存服务 | 🟡 警告 | v6.2.7 | 2024-01-13 | [检查](actions/check.md) |
| 消息队列 | 🔴 停止 | v3.8.0 | 2024-01-12 | [启动](actions/start.md) |
```

## 🎬 收起展开模板

### 基础收起展开

```html
<details>
<summary>点击展开详细信息</summary>

这里是被收起的内容，可以包含：

- 详细的配置说明
- 复杂的代码示例
- 长篇的解释文档
- 可选的高级功能

```json
{
  "config": {
    "database": {
      "host": "localhost",
      "port": 3306,
      "username": "admin",
      "password": "password"
    }
  }
}
```

</details>
```

### 高级收起展开

```html
<details>
<summary>🔧 高级配置选项</summary>

### 数据库配置

```yaml
database:
  host: localhost
  port: 3306
  username: admin
  password: ${DB_PASSWORD}
  pool:
    min: 5
    max: 20
    idle_timeout: 300
```

### 缓存配置

```yaml
cache:
  type: redis
  host: localhost
  port: 6379
  ttl: 3600
```

### 日志配置

```yaml
logging:
  level: info
  format: json
  output: /var/log/app.log
  rotation:
    max_size: 100MB
    max_files: 10
```

</details>

<details>
<summary>📊 性能调优参数</summary>

### JVM参数

```bash
-Xms2g -Xmx4g
-XX:+UseG1GC
-XX:MaxGCPauseMillis=200
-XX:+PrintGCDetails
```

### 线程池配置

| 参数 | 推荐值 | 说明 |
|------|--------|------|
| core_pool_size | 10 | 核心线程数 |
| max_pool_size | 50 | 最大线程数 |
| queue_capacity | 1000 | 队列容量 |
| keep_alive_time | 60s | 线程存活时间 |

</details>
```

## 📝 文档结构模板

### 📖 标准文档模板

```markdown
# 文档标题

> 📖 **简介**：用一句话描述文档的主要内容

## 📋 目录

- [概述](#概述)
- [准备工作](#准备工作)
- [详细步骤](#详细步骤)
- [常见问题](#常见问题)
- [相关资源](#相关资源)

## 🎯 概述

### 文档目的

本文档旨在帮助用户 [具体目标]，通过阅读本文档，您将学会：

- 目标1：具体描述
- 目标2：具体描述
- 目标3：具体描述

### 适用范围

- **适用人群**：[目标用户群体]
- **前置条件**：[需要的基础知识或条件]
- **预计时间**：[完成所需时间]

## 🛠️ 准备工作

在开始之前，请确保您已经：

- [ ] 准备项1
- [ ] 准备项2
- [ ] 准备项3

### 环境要求

| 项目 | 要求 | 说明 |
|------|------|------|
| 操作系统 | Windows 10+ / macOS 10.15+ / Ubuntu 18.04+ | 支持的操作系统版本 |
| 内存 | 4GB+ | 推荐8GB以上 |
| 存储空间 | 10GB+ | 用于安装和数据存储 |
| 网络 | 稳定的互联网连接 | 用于下载和同步 |

## 📝 详细步骤

### Step 1: [步骤名称]

1. **操作描述**：详细说明第一个操作
   
   ```bash
   # 示例命令
   command --option value
   ```

2. **验证结果**：如何确认操作成功
   
   > 💡 **提示**：如果看到以下输出，说明操作成功：
   > ```
   > Success: Operation completed
   > ```

3. **故障排除**：常见问题和解决方法
   
   > ⚠️ **注意**：如果遇到错误，请检查 [具体检查项]

### Step 2: [步骤名称]

1. **操作描述**：详细说明第二个操作
2. **配置说明**：相关配置的详细说明
3. **最佳实践**：推荐的操作方式

### Step 3: [步骤名称]

1. **操作描述**：详细说明第三个操作
2. **验证测试**：如何测试配置是否正确
3. **性能优化**：可选的优化建议

## 🆘 常见问题

### Q: 问题1？

**A: 解答1**

详细的解答内容，包括：
- 问题原因分析
- 具体解决步骤
- 预防措施建议

### Q: 问题2？

**A: 解答2**

可以包含代码示例：

```bash
# 解决方案命令
solution-command --fix
```

### Q: 问题3？

**A: 解答3**

可以使用收起展开来组织复杂内容：

<details>
<summary>详细解决方案</summary>

1. 第一步：具体操作
2. 第二步：具体操作
3. 第三步：具体操作

</details>

## 🔗 相关资源

### 📚 延伸阅读

- [相关文档1](link1.md)
- [相关文档2](link2.md)
- [官方文档](https://example.com/docs)

### 🛠️ 工具和下载

- [工具1下载](https://example.com/tool1)
- [工具2下载](https://example.com/tool2)
- [示例代码](https://github.com/example/repo)

### 💬 获取帮助

- [技术支持](support/contact.md)
- [社区论坛](https://forum.example.com)
- [问题反馈](https://github.com/example/issues)

---

📝 **文档信息**
- **创建时间**：2024年1月
- **最后更新**：2024年1月
- **文档版本**：v1.0
- **负责人**：[姓名]
```

### 🔧 API文档模板

```markdown
# API 接口文档

## 接口概述

### 基本信息

- **接口名称**：[接口名称]
- **接口地址**：`/api/v1/endpoint`
- **请求方式**：`POST`
- **内容类型**：`application/json`

### 功能描述

[详细描述接口的功能和用途]

## 请求参数

### Headers

| 参数名 | 类型 | 必填 | 说明 |
|--------|------|------|------|
| Authorization | string | 是 | Bearer token |
| Content-Type | string | 是 | application/json |

### Body参数

| 参数名 | 类型 | 必填 | 默认值 | 说明 |
|--------|------|------|--------|------|
| name | string | 是 | - | 名称 |
| type | string | 否 | "default" | 类型 |
| config | object | 否 | {} | 配置对象 |

### 请求示例

```bash
curl -X POST \
  https://api.example.com/v1/endpoint \
  -H 'Authorization: Bearer your-token' \
  -H 'Content-Type: application/json' \
  -d '{
    "name": "example",
    "type": "custom",
    "config": {
      "enabled": true,
      "timeout": 30
    }
  }'
```

## 响应结果

### 成功响应

**状态码**：`200 OK`

```json
{
  "code": 0,
  "message": "success",
  "data": {
    "id": "12345",
    "name": "example",
    "status": "active",
    "created_at": "2024-01-15T10:30:00Z"
  }
}
```

### 错误响应

**状态码**：`400 Bad Request`

```json
{
  "code": 1001,
  "message": "参数错误",
  "errors": [
    {
      "field": "name",
      "message": "名称不能为空"
    }
  ]
}
```

### 响应字段说明

| 字段名 | 类型 | 说明 |
|--------|------|------|
| code | number | 状态码，0表示成功 |
| message | string | 响应消息 |
| data | object | 响应数据 |
| errors | array | 错误详情（仅错误时返回） |

## 错误码说明

| 错误码 | 说明 | 解决方案 |
|--------|------|----------|
| 1001 | 参数错误 | 检查请求参数格式和必填项 |
| 1002 | 认证失败 | 检查Authorization header |
| 1003 | 权限不足 | 联系管理员获取权限 |
| 5001 | 服务器错误 | 稍后重试或联系技术支持 |

## 使用示例

### JavaScript示例

```javascript
const response = await fetch('https://api.example.com/v1/endpoint', {
  method: 'POST',
  headers: {
    'Authorization': 'Bearer your-token',
    'Content-Type': 'application/json'
  },
  body: JSON.stringify({
    name: 'example',
    type: 'custom',
    config: {
      enabled: true,
      timeout: 30
    }
  })
});

const data = await response.json();
console.log(data);
```

### Python示例

```python
import requests
import json

url = 'https://api.example.com/v1/endpoint'
headers = {
    'Authorization': 'Bearer your-token',
    'Content-Type': 'application/json'
}
data = {
    'name': 'example',
    'type': 'custom',
    'config': {
        'enabled': True,
        'timeout': 30
    }
}

response = requests.post(url, headers=headers, json=data)
result = response.json()
print(result)
```
```

## 📋 检查清单模板

### 📝 文档发布检查清单

```markdown
## 📋 文档发布前检查清单

### ✅ 内容质量检查

- [ ] **标题准确**：标题清晰准确，符合内容主题
- [ ] **结构完整**：包含必要的章节和内容
- [ ] **信息准确**：所有信息都经过验证，确保准确性
- [ ] **语言规范**：语法正确，表达清晰
- [ ] **示例有效**：所有代码示例都经过测试

### ✅ 格式规范检查

- [ ] **Markdown语法**：正确使用Markdown语法
- [ ] **链接有效**：所有内部和外部链接都可以正常访问
- [ ] **图片显示**：所有图片都能正常显示
- [ ] **代码高亮**：代码块使用正确的语言标识
- [ ] **表格格式**：表格格式正确，对齐美观

### ✅ 导航和结构检查

- [ ] **侧边栏更新**：_sidebar.md文件已更新
- [ ] **目录结构**：文件放在正确的目录中
- [ ] **文件命名**：文件名符合命名规范
- [ ] **路径正确**：所有文件路径都正确

### ✅ 用户体验检查

- [ ] **阅读流畅**：内容逻辑清晰，阅读流畅
- [ ] **操作可行**：所有操作步骤都可以实际执行
- [ ] **问题解答**：预期的常见问题都有解答
- [ ] **获取帮助**：提供了获取进一步帮助的途径

### ✅ 技术验证检查

- [ ] **环境测试**：在目标环境中测试所有操作
- [ ] **兼容性**：确认在不同浏览器中显示正常
- [ ] **响应式**：在不同设备上显示效果良好
- [ ] **加载速度**：页面和图片加载速度合理

### ✅ 最终确认

- [ ] **同行评审**：至少一位同事审核过内容
- [ ] **管理审批**：获得必要的发布审批
- [ ] **备份完成**：重要内容已备份
- [ ] **发布计划**：确认发布时间和方式
```

## 🎯 使用建议

### 📝 模板选择指南

#### 根据文档类型选择

| 文档类型 | 推荐模板 | 说明 |
|----------|----------|------|
| 产品介绍 | overview.md模板 | 适合产品概览和功能介绍 |
| 操作指南 | 标准文档模板 | 适合步骤性的操作说明 |
| API文档 | API文档模板 | 适合接口文档编写 |
| 故障排除 | FAQ模板 | 适合问题解答类文档 |
| 配置说明 | 收起展开模板 | 适合复杂配置的说明 |

#### 根据用户群体选择

- **新手用户**：使用更多提示和说明
- **专业用户**：可以使用更简洁的格式
- **开发者**：重点使用代码示例和API模板
- **管理员**：重点使用配置和权限相关模板

### 🔧 模板定制建议

#### 个性化调整

1. **品牌元素**：
   - 调整颜色和图标以匹配品牌
   - 使用统一的术语和表达方式
   - 添加公司特有的免责声明

2. **内容结构**：
   - 根据产品特点调整章节结构
   - 增加或删除不适用的部分
   - 调整详细程度以匹配用户需求

3. **样式优化**：
   - 统一使用表情符号和图标
   - 保持一致的格式和缩进
   - 优化表格和列表的显示效果

#### 团队协作

```markdown
1. 建立团队共享的模板库
2. 定期更新和优化模板
3. 收集使用反馈并持续改进
4. 培训团队成员正确使用模板
```

---

🎯 **下一步**：[常见问题解答](10-faq.md)