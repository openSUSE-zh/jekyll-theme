# openSUSE 中文社区 jekyll 主题

openSUSE 中文社区 jekyll 主题

## 安装

## 开发

### 如何配置环境

```bash
sudo zypper in ruby ruby-devel
bundle config set path 'vendor/bundle'
bundle install
```

### 如何构建网站

```bash
bundle exec jekyll build
```

构建的成果应该在 `_site` 目录。

### 如何在本地预览

```bash
bundle exec jekyll serve
```

用你的浏览器访问 <http://127.0.0.1:4000/> 。
