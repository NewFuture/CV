# CV(简历)自动生成
简历模板自动生成gh-pages. A resume template auto builds in github-pages by Jekyll

* [x] 手机端适配
* [x] 打印格式优化(可导PDF)
* [x] html和css压缩
* [x] [HTML5语义化支持](https://validator.w3.org/nu/?doc=https%3A%2F%2Fnewfuture.github.io%2FCV%2F&showoutline=yes)
* [x] 简单markdown嵌套

浏览器兼容:

* [x] Chrome
* [x] Andoroid (系统内置浏览器,微信等)
* [x] Edge
* [x] >=IE7 (支持IE: 7 8 9 10 11)
* [x] Safari (包括 iPhone和iPad)
* [x] FireFox

## 在线使用(需登录github)

1. 修改(`Edit`)[_data/resume.yml](_data/resume.yml)(内容和条目根据需要删减),[点此直接修改](https://github.com/NewFuture/CV/edit/gh-pages/_data/resume.yml)
2. 保存(点击`Commit changes`) (会自动fork和commit)
3. 稍等片刻(commit后会自动编译生成github pages),打开[https://{your-github-id}.github.io/CV/](https://newfuture.github.io/CV/) 查看效果


## 效果截图

<details>
<summary> 1. 标准PC版(宽度> 1024)</summary>

![](assets/img/pc.png)
</details>
<details>
 <summary>2. iPad Pro或窄屏笔记本( 1024 >= width >= 768)</summary>

![](assets/img/large.png)
</details>
<details>
<summary>3. iPad mini或宽屏Note( 768 >= width > 450)</summary>

![](assets/img/ipad.png)
</details>
<details>
<summary>4. 标准手机版( width <= 450)</summary>

![](assets/img/iphone.png)
</details>




## 高级用法

### 导出 PDF
1. 浏览器(推荐chrome)点击页面底部`打印`
2. 选择打印为PDF文档

### 自定义域名

1. 添加[`CNAME`](https://github.com/NewFuture/CV/new/gh-pages/CNAME)文件，一行你的域名,[更多关于域名添加的问题](https://help.github.com/articles/adding-or-removing-a-custom-domain-for-your-github-pages-site/)
2. 修改该域名的DNS的CNAME记录为`{YOUR-github-ID}.github.io`

### 自定义样式
* [`_sass/resume.scss`](_sass/resume.scss) 默认样式
* [`_sass/mobile.scss`](_sass/mobile.scss) 移动端适配
* [`_sass/print.scss`](_sass/print.scss) 打印样式

## 参考

* 简历模板 https://github.com/crispgm/resume
* jekyll简历模板 https://github.com/nternetinspired/jekyll-resume
* html压缩 https://github.com/penibelst/jekyll-compress-html
* svg 压缩 `svgo`