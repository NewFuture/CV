# CV(简历自动生成)
简历模板自动生成gh-pages. A resume template auto builds in github-pages by Jekyll

* [x] 手机端适配
* [x] 打印格式优化
* [x] html和css压缩

## 立即在线使用

1. 修改(`Edit`)[_data/resume.yml](https://github.com/NewFuture/CV/edit/gh-pages/_data/resume.yml)(内容和条目更具需要删减)
2. 保存(点击`Commit changes`) (会自动fork和commit)
3. 打开[https://{your-github-id}.github.io/CV/](https://newfuture.github.io/CV/) 查看效果(commit后会自动编译生成github pages)

## 高级用法

### 导出 PDF
1. 浏览器打开右键选择`打印`
2. 选择打印为PDF文档

### 自定义样式
* [`_sass/resume.scss`](_sass/resume.scss) 默认样式
* [`_sass/mobile.scss`](_sass/mobile.scss) 移动端适配
* [`_sass/print.scss`](_sass/print.scss) 打印样式

## 参考

* 简历模板 https://github.com/crispgm/resume
* jekyll简历模板 https://github.com/nternetinspired/jekyll-resume
* html压缩 https://github.com/penibelst/jekyll-compress-html
* svg 压缩 `svgo`