# Blog

### 1. 创建博客
    hugo new site Blog
    git init
### 2. 下载主题
    cd Blog
    git clone https://github.com/adityatelange/hugo-PaperMod.git --depth=1 themes/PaperMod
    从 themes/PaperMod 的 exampleSite 分支复制 content 到 Blog 目录
### 3. 配置文件
    复制 Blog/themes/hermit/exampleSite/config.yml => Blog/config.yml
    配置文件 config.toml 中添加 publishDir = docs
### 4. 添加文章
    hugo new about/_index.md
    hugo new posts/my-first-post.md
### 5. 生成 docs 静态文件
    hugo