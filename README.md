![黑白](https://user-images.githubusercontent.com/64707090/212085429-902f45db-e774-43c3-b526-38582f3528ef.jpg)


## 线上演示：https://www.yumus.cn/

## 关于SEO设置：https://www.yumus.cn/course/2131.html

这是一款简洁的WordPress主题-YUMU，你也可以叫它的中文名称“语幕主题”，主题非常简洁也非常的纯粹，只适合用来写写博客没有一丝多余的功能。因为有不少网友来问过我用的是什么主题，能不能开源，在百般考虑后还是决定开放出来与大家共享，就当是受惠于社区也反哺于社区吧。

主题在后台仅支持设置页眉和页脚的菜单，也就是说除文章内容、友情链接和菜单以外的所有内容都不支持在后台进行修改，当然主题因为简洁简单需要你自行修改的地方也不多。

### 特别说明

**留个QQ群，水群或有问题可以进群，[QQ群号：136158478](https://qm.qq.com/cgi-bin/qm/qr?k=QXApLNs8o699vSO38i6YleapjXn9n8S-&jump_from=webapi&authKey=dfxBqMAcZNcjDkoz4s/vRhSrbxy6BFwMp5kCKrdrPq4qKGVsg/gVrM8E5RbL3N5P 'QQ群号：136158478')**

**作者微信：asir3q**

本主题基于作者的个人需求编写，使用的是古腾堡编辑器，众所周知古腾堡编辑器很强大，但能用到20%功能的人应该少之又少，作者本人也是如此甚至只用到了10%的功能，因此基于作者撰写博文的需求，本主题前台样式只对标题（h1～h6）、段落、列表（有序和无序）、引用、表格、链接、分割线、图片和代码做了预设，且图片强制水平居中，在后台撰写博文你无须关注样式，只管创作内容即可，如有特殊需求请自行添加CSS样式，作者不会考虑也不准备对更多的内容样式进行预设（对了，本主题禁止前台加载任何wordpress古腾堡编辑器生成的样式文件，拖垮加载速度且花里胡哨与作者理念不合，如有需要自行在hooks.php文件删除相应的禁止代码，同时也不会考虑做ajax评论功能）敬酒虽好可不要贪杯哦～，博客博客重在内容。


本主题已经集成常见的wordpress优化，如有不能使用的情况，请尝试停用优化插件，主题header.php文件中第15行代码只调用了对应首页、文章页、列表页、搜索页和页面的标题，关键字和描述如有需要请查看本说明上方的SEO设置链接或使用第三方SEO插件（使用第三方SEO插件前请删除header.php文件中的第15行代码以免多次调用标题）。

给各位吹个牛逼，请看下图

<img width="1604" alt="截屏2023-03-20 02 35 18" src="https://user-images.githubusercontent.com/64707090/226199237-5897b05d-662d-498f-95dd-e706377d2d39.png">


写于2023年3月20日凌晨，此次上传为3.0版本，作者服务器环境CentOS7+Nginx+PHP8+MySql5.6，经此环境测试无误，前一个版本上传未经严谨测试存在问题请尽快更新。感谢大家对作者的支持，满意请给我Star。

### 功能支持与特点

1.  代码高亮：后台编辑文章时添加“代码”区块，编辑你的代码即可，主题内置了highlightjs，发布文章后前端会自动识别代码语言并高亮显示。
2.  暗黑模式：良好的暗黑模式，细节处理到每一个像素。
3.  全站完美的自适应：适配所有大小的屏幕（像素≥360px）无论是电脑、平板还是手机每一处都能进行完美适应，在所有设备上都可以得到良好的浏览体验。
4.  纯原生写法：整个站点没有多少JS除代码高亮以外没有使用任何前端插件。
5.  良好的表格：自适应表格，表格再后台编辑文章时仅支持添加行和列，但不影响表格再前端的完美展示，不信你就试试。

### 修改方法

1.  网站LOGO：打开**header.php**文件，找到第23行，将LOGO替换成你的即可（注意：为了良好适配暗黑模式和明亮模式，建议内联使用SVG格式的LOGO，暗黑模式下会自动把logo颜色变更为白色）。
2.  页脚描述：打开**footer.php**文件，从第4行开始至第10行结束，你都可以进行改动（但恳请不要修改版权信息，作者不是Coding出于喜爱开源此主题，请让我保持热情，保留版权信息不仅不会损害你的利益还可以让你得到作者的尊重）。

### 再次强调

1. 主题不完全支持古腾堡编辑器，之所以这么说是为了防止过多的样式内容拖垮加载速度和影响前台美观，因此编辑文章无论你对古腾堡的区块如何进行设置在前端都看不到任何效果（因为我们不加载后台样式）。

2. 仅支持在后台编辑段落、标题、列表、引用、代码、表格，链接，分割线，前台浏览图片自动居中，如果有特殊需求，需要你自行编写对应CSS，介意者慎用。

![image](https://user-images.githubusercontent.com/64707090/200598521-6451e026-cade-4f6e-bab3-f6906623db5a.png)

不管代码写的咋样，毕竟我费了一番心血，代码未加密但希望能给我保留个版权链接。

### 更新日志

1.  2022/10/03：支持设置二级菜单。
2.  2022/10/07：①图片资源转移至本地；②优化顶部导航自适应问题。
3.  2023/01/12：①新增暗黑模式；②PC端顶部导航居左；③已知问题修复及细节优化。
4.  2023/03/20：经热心网友提示，主题上传后存在使用问题，检查发现确实是作者上一个版本没有经过严谨测试直接上传了主题代码所致，此版本特地进过检查无误后上传的，可放心使用。①增加了评论墙、网址导航两个页面模板（评论墙不支持ajax提交，请勿对评论墙进行页面缓存，网址导航来源于后台添加的链接，网址导航中的瞄点请在主题菜单-选择友情链接中添加自定义链接）②对前端页面进行了加宽，老版本最大宽度为960px，现改为最大宽度1024px，封面图也进行了加宽和加高处理，完整样式可浏览体验作者的博客（https://www.yumus.cn）。
5.  2023/04/11：①修复文章详情页图片宽度超出的问题；②修复文章详情页连续标题会并行的问题。
6.  2023/04/23：①新增网站SEO关键字与描述设置，请在hooks.php文件的第7行与第12行写入自己的网站默认关键字和默认描述，文章分类页的关键字与描述请在WordPress分类中编辑；

②文章详情页面添加手机阅读二维码；

③新增3个小工具页面模板，分别是家庭称谓计算器、二维码生成器、随机密码生成器，请自行在WordPress创建页面选择对应页面模板；

④美化WordPress后台登录页面；

⑤优化多个不太容易被人发现的体验😀。

![image](https://user-images.githubusercontent.com/64707090/200598521-6451e026-cade-4f6e-bab3-f6906623db5a.png)

### 谢谢金主打赏

![alipay](https://user-images.githubusercontent.com/64707090/226198400-de267169-5bf8-4fed-bfd3-81eb17bb84d8.png)
![wepay](https://user-images.githubusercontent.com/64707090/226198406-2dfb9529-1940-4850-acf1-d8781940e523.png)
