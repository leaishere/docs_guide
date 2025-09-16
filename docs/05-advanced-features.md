# 高级功能使用指南

> 🎯 **目标**：掌握文档平台的高级样式和功能，提升文档表现力

## 🎨 样式功能

### 🏷️ Tabs标签页

**使用场景**：展示多种配置方式、不同平台的操作步骤等

**语法格式1**：
```html
<!-- tabs:start -->

#### **English**

Hello!

#### **French**

Bonjour!

#### **Italian**

Ciao!

<!-- tabs:end -->

```
**语法格式2**：
```html
<!-- tabs:start -->

<!-- tab:English -->

Hello!

<!-- tab:French -->

Bonjour!

<!-- tab:Italian -->

Ciao!

<!-- tabs:end -->

```

**实际示例**：
```html
<!-- tabs:start -->
<!-- tab:控制台操作 -->

1. 登录UCloud控制台
2. 进入产品页面
3. 点击创建按钮

<!-- tab:API调用 -->

```bash
curl -X POST \
  https://api.ucloud.cn/create \
  -H 'Content-Type: application/json'
```

<!-- tabs:end -->
```

**注意事项**：
- 支持在tab内使用所有Markdown语法
- 标签名称要简洁明了

### 💡 提示样式
#### 一般提示：

- 适用于：与上下文内容有关的**重要信息**，需用户注意
- 语法： > 此处有一个一般提示文案 

#### 	帮助提示：
* 适用于：对产品使用提供帮助说明，阅读本提示可以**提升用户在产品使用上的效率**
* 语法： ?> 此处有一个一般提示文案 

#### 告警提示：
* 适用于：向用户说明操作风险和操作限制，忽略本提示可能给用户造成**实质性损失**
* 语法： !> 此处有一个一般提示文案 

### 🔗 超链接样式
#### 基础链接
```markdown
[链接文字](https://链接地址)
```

#### 按钮样式链接
```html
<a href="https://链接地址" class="btn btn-primary">按钮文字</a>
```

#### 新窗口打开
```html
<a href="https://链接地址" target="_blank">链接文字</a>
```

### 📝 副标题功能

**使用场景**：为文档添加补充说明或更新信息

```markdown
# 主标题
## 副标题说明
> 最后更新：2023-12-01
```

### 📋 内容目录
**自动生成目录**：平台支持自动抓取文章内的二级标题生成目录

## 🔧 代码高亮

### 📝 支持的语言

平台支持多种编程语言的语法高亮：

#### 常用语言
- **JavaScript**: `javascript` 或 `js`
- **Python**: `python` 或 `py`
- **Java**: `java`
- **Go**: `go`
- **Shell**: `bash` 或 `shell`
- **JSON**: `json`
- **YAML**: `yaml` 或 `yml`
- **XML**: `xml`
- **SQL**: `sql`
- **PHP**: `php`
- **C++**: `cpp`
- **C#**: `csharp`

#### 配置文件
- **Nginx**: `nginx`
- **Apache**: `apache`
- **Docker**: `dockerfile`
- **Kubernetes**: `yaml`

### 💻 代码块使用

#### 基础语法
```markdown
```语言名称
代码内容
```
```

#### 实际示例

**JavaScript代码**：
```markdown
```javascript
function hello() {
    console.log("Hello World!");
}
```
```

**Shell命令**：
```markdown
```bash
sudo apt-get update
sudo apt-get install nginx
```
```

**JSON配置**：
```markdown
```json
{
    "name": "example",
    "version": "1.0.0"
}
```
```

### 🎯 代码块最佳实践

1. **选择合适的语言标识**
   - 使用准确的语言名称
   - 保持一致的命名风格

2. **代码格式化**
   - 保持适当的缩进
   - 添加必要的注释
   - 删除敏感信息

3. **示例完整性**
   - 提供可运行的完整示例
   - 包含必要的导入语句
   - 说明运行环境要求

## 🎬 多媒体支持

### 🎥 视频支持

**支持格式**：`.mp4`

**嵌入方式**：
```html
<video width="100%" controls>
  <source src="images/demo.mp4" type="video/mp4">
  您的浏览器不支持视频播放。
</video>
```

### 🎞️ GIF动图

**使用场景**：操作演示、流程说明

**嵌入方式**：
```markdown
![操作演示](images/demo.gif)
```

**制作建议**：
- 控制文件大小（建议<5MB）
- 保持清晰度
- 突出关键操作

## 📊 表格高级功能

### 📋 表格对齐

```markdown
| 左对齐 | 居中对齐 | 右对齐 |
|:-------|:--------:|-------:|
| 内容1  |   内容2  |  内容3 |
```
> 单元格内换行，markdown不支持。只能手动写<br></br>实现


## 🔄 收起展开功能

**使用场景**：长内容折叠、可选内容隐藏

```html
<details> 
<summary>展开详情</summary> 
<pre><code> 仓库根目录下的sidebar.md用于定义页面左边栏导航，修改文档内目录顺序来自定义文章排序。 </code></pre> 
</details>
```

---

🎯 **下一步**：[本地编辑工具](07-local-editing.md)
