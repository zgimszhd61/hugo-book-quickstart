# hugo-book-quickstart
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
## 内容存储在哪里
 - 存储在docs/目录下.

## 参考资料
 - https://github.com/alex-shpak/hugo-book
