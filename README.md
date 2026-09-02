# Yifan Cheng's Personal Homepage

网站地址：<https://cyfan688.github.io/>

这个主页只使用普通 HTML 和 CSS，不需要修改 Jekyll 配置。

## 平时修改哪里

- **index.html**：姓名、简介、研究兴趣、项目、论文和链接等页面内容。
- **style.css**：字体、颜色、间距和手机布局。一般不需要修改。
- **images/**：头像和其他照片。
- **files/**：CV、论文等可下载文件。

index.html 中已经添加了 PROFILE、ABOUT、INTERESTS、PUBLICATIONS、
PROJECTS 和 PHOTOS 注释。搜索这些大写单词即可找到对应位置。

## 添加 CV

1. 将 PDF 命名为 Yifan_Cheng_CV.pdf，上传到 files/ 文件夹。
2. 在 index.html 的 CV 注释处加入：

~~~html
<a href="/files/Yifan_Cheng_CV.pdf">CV</a>
~~~

## 添加论文

搜索 PUBLICATIONS，移除示例区块外层的 HTML 注释，然后填写论文题目、作者、
会议或期刊、年份以及 Paper/Code 链接。每增加一篇论文，复制一个 article 区块。

## 添加照片

先将照片上传到 images/，再搜索 PHOTOS，移除示例区块外层的 HTML 注释并修改
图片文件名、说明文字和 caption。
