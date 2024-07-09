# hugo-book
## 简介
 - hugo可以用来做博客。
 - hugo-book是一个有用的主题。
![image](https://github.com/zgimszhd61/hugo-book-quickstart/assets/114722053/d70180e8-6ebd-451a-a16f-f36cb9ce2bec)

## 使用方法
```
brew install hugo
git clone --depth 1 https://github.com/alex-shpak/hugo-book
cd hugo-book
git init
git submodule add https://github.com/alex-shpak/hugo-book themes/hugo-book
cp -R themes/hugo-book/exampleSite/content.en/* ./content
hugo server --minify --theme hugo-book
code .
```

## 站点静态化
```
hugo
```

## 内容存储在哪里
 - 存储在docs/目录下.

## 添加新内容的命令
```
hugo new my-first-page.md
```

## 参考资料
 - https://github.com/alex-shpak/hugo-book
