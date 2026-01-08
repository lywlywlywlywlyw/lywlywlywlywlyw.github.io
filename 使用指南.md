# Academic Pages 模板文件结构与修改指南

## 核心文件与目录

### 配置文件

#### `_config.yml`
- **功能**：网站的主要配置文件，控制网站的全局设置
- **修改方法**：
  - 修改网站标题、描述、URL等基本信息
  - 更新个人信息（姓名、简历、联系方式等）
  - 设置社交媒体链接
  - 配置分析工具、评论系统等
- **常见修改**：
  ```yaml
  title: "您的网站标题"
  name: "您的姓名"
  description: "网站描述"
  url: "https://您的用户名.github.io"
  author:
    name: "显示在侧边栏的名字"
    bio: "个人简介"
    location: "所在地"
    email: "电子邮箱"
  ```

#### `_data/navigation.yml`
- **功能**：控制网站顶部导航菜单
- **修改方法**：
  - 添加、删除或修改菜单项
  - 更改菜单项的顺序
  - 修改菜单项的标题和链接
- **常见修改**：
  ```yaml
  main:
    - title: "出版物"
      url: /publications/
    - title: "教学"
      url: /teaching/
    # 添加新菜单项
    - title: "新页面"
      url: /new-page/
  ```

#### `_data/ui-text.yml`
- **功能**：控制界面文本，支持多语言
- **修改方法**：
  - 修改特定语言下的文本标签
- **常见修改**：
  ```yaml
  zh-CN:
    page: "页面"
    pagination_previous: "上一页"
    pagination_next: "下一页"
  ```

### 内容文件与目录

#### `_pages/`
- **功能**：存放网站的单独页面
- **重要文件**：
  - `about.md`：网站首页/关于页面
  - `cv.md`：简历页面
  - `markdown.md`：Markdown指南页面
- **修改方法**：
  - 编辑现有页面的内容
  - 添加新的`.md`文件创建新页面
- **常见修改**：
  ```markdown
  ---
  permalink: /your-page/
  title: "您的页面标题"
  author_profile: true
  ---

  这里是页面内容，使用Markdown格式编写。
  ```

#### `_publications/`
- **功能**：存放出版物/论文信息
- **修改方法**：
  - 为每篇论文创建一个`.md`文件
  - 文件名格式建议：`YYYY-MM-DD-paper-title.md`
- **常见修改**：
  ```markdown
  ---
  title: "论文标题"
  collection: publications
  permalink: /publication/paper-id
  date: 2023-01-01
  venue: "期刊名称"
  paperurl: "http://论文链接"
  citation: "引用格式"
  ---

  论文摘要或描述。
  ```

#### `_talks/`
- **功能**：存放演讲/讲座信息
- **修改方法**：
  - 为每次演讲创建一个`.md`文件
  - 文件名格式建议：`YYYY-MM-DD-talk-title.md`
- **常见修改**：
  ```markdown
  ---
  title: "演讲标题"
  collection: talks
  type: "演讲类型"
  permalink: /talks/talk-id
  venue: "演讲地点"
  date: 2023-01-01
  location: "城市，国家"
  ---

  演讲描述或摘要。
  ```

#### `_teaching/`
- **功能**：存放教学经历
- **修改方法**：
  - 为每个课程创建一个`.md`文件
- **常见修改**：
  ```markdown
  ---
  title: "课程名称"
  collection: teaching
  type: "课程类型"
  permalink: /teaching/course-id
  venue: "机构名称"
  date: 2023-01-01
  location: "城市，国家"
  ---

  课程描述。
  ```

#### `_portfolio/`
- **功能**：存放项目/作品集
- **修改方法**：
  - 为每个项目创建一个`.md`文件
- **常见修改**：
  ```markdown
  ---
  title: "项目名称"
  excerpt: "项目简介"
  collection: portfolio
  ---

  项目详细描述。
  ```

#### `_posts/`
- **功能**：存放博客文章
- **修改方法**：
  - 为每篇文章创建一个`.md`文件
  - 文件名格式必须为：`YYYY-MM-DD-title.md`
- **常见修改**：
  ```markdown
  ---
  title: '文章标题'
  date: 2023-01-01
  permalink: /posts/2023/01/post-id/
  tags:
    - 标签1
    - 标签2
  ---

  文章内容。
  ```

### 样式与布局文件

#### `_layouts/`
- **功能**：存放页面布局模板
- **重要文件**：
  - `default.html`：默认布局
  - `single.html`：单页面布局
  - `talk.html`：演讲页面布局
- **修改方法**：
  - 谨慎修改，除非您了解HTML和Liquid模板语言
  - 修改布局结构或添加新元素

#### `_includes/`
- **功能**：存放可重用的HTML组件
- **重要文件**：
  - `author-profile.html`：侧边栏作者信息
  - `footer.html`：页脚
  - `masthead.html`：顶部导航栏
- **修改方法**：
  - 修改特定组件的HTML结构
  - 添加新的功能或元素

#### `_sass/`
- **功能**：存放SCSS样式文件
- **重要目录**：
  - `_themes/`：主题样式
  - `layout/`：布局样式
- **修改方法**：
  - 修改颜色、字体、间距等样式
  - 在`_themes/_default.scss`或`_themes/_dark.scss`中修改主题颜色

#### `assets/`
- **功能**：存放网站资源文件
- **重要目录**：
  - `css/`：CSS样式文件
  - `js/`：JavaScript文件
- **修改方法**：
  - 修改`css/main.scss`添加自定义样式
  - 添加新的JavaScript功能

### 静态资源

#### `images/`
- **功能**：存放图片文件
- **重要文件**：
  - `profile.png`：个人头像
- **修改方法**：
  - 替换`profile.png`更换头像
  - 添加新图片并在Markdown中引用

#### `files/`
- **功能**：存放可下载文件（PDF、ZIP等）
- **修改方法**：
  - 上传文件到此目录
  - 通过`https://用户名.github.io/files/文件名`访问

## 常见修改场景

### 1. 修改个人信息

1. 编辑`_config.yml`文件中的`author`部分
2. 更新`name`、`bio`、`location`、`email`等字段
3. 添加或修改社交媒体链接

### 2. 更换头像

1. 准备一张合适的头像图片
2. 将其命名为`profile.png`
3. 上传到`images/`目录，替换原有文件
4. 或者在`_config.yml`中修改`author.avatar`指向新的图片文件

### 3. 修改网站标题和描述

1. 编辑`_config.yml`文件
2. 修改`title`、`name`和`description`字段

### 4. 修改导航菜单

1. 编辑`_data/navigation.yml`文件
2. 在`main`部分添加、删除或修改菜单项
3. 每个菜单项包含`title`（显示文本）和`url`（链接地址）

### 5. 添加新页面

1. 在`_pages/`目录创建新的`.md`文件
2. 添加YAML前置信息，包括`permalink`、`title`等
3. 编写页面内容
4. 在`_data/navigation.yml`中添加链接（如需要）

### 6. 添加出版物/论文

1. 在`_publications/`目录创建新的`.md`文件
2. 添加YAML前置信息，包括`title`、`collection`、`permalink`、`date`等
3. 编写论文描述

### 7. 修改网站颜色主题

1. 编辑`_sass/themes/_default.scss`（默认主题）或`_sass/themes/_dark.scss`（暗色主题）
2. 修改颜色变量
3. 在`_config.yml`中的`site_theme`设置使用的主题

### 8. 添加自定义CSS

1. 编辑`assets/css/main.scss`文件
2. 在文件末尾添加自定义CSS规则

### 9. 上传和链接PDF等文件

1. 将文件上传到`files/`目录
2. 在Markdown中使用`[链接文本](https://用户名.github.io/files/文件名.pdf)`引用

### 10. 修改页脚信息

1. 编辑`_includes/footer.html`文件
2. 修改版权信息或添加自定义内容

## 特殊功能修改

### 启用/禁用评论系统

1. 编辑`_config.yml`文件
2. 修改`comments.provider`字段
3. 配置相应的评论系统参数

### 启用/禁用分析工具

1. 编辑`_config.yml`文件
2. 修改`analytics.provider`字段
3. 添加相应的跟踪ID

### 修改语言设置

1. 编辑`_config.yml`文件
2. 修改`locale`字段（如`"zh-CN"`表示简体中文）

### 添加自定义JavaScript

1. 将JS文件放在`assets/js/`目录
2. 在`_includes/scripts.html`中引用

## 总结

Academic Pages模板的文件结构清晰，便于维护和修改。大多数常见修改只需编辑几个关键文件：
- `_config.yml`：全局设置和个人信息
- `_data/navigation.yml`：导航菜单
- `_pages/about.md`：首页内容
- 各种集合目录（`_publications/`、`_talks/`等）：添加具体内容

通过了解每个文件的功能和修改方法，您可以轻松地定制您的学术网站，展示您的研究成果和专业经历。

记住，每次修改后，GitHub Pages会自动重新构建您的网站，通常需要几分钟时间才能看到更改生效。
