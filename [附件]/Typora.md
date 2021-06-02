# 常用技巧



## 上标注释

- 英文

  ​		<ruby>excuse<rp>(<rp><rt>借口</rt><rp>)</rp></ruby>[^1]

- 中文

  ​		<ruby>饕<rp>(<rp><rt>tao</rt><rp>)</rp>&nbsp;餮<rp>(</rp><rt>&nbsp;tie</rt><rp>)</rp></ruby>



## 注释

附件[^2]

其它[^2]

正文[^注释]

[^1]:excuse me?
[^2]:悬停即可预览内容。
[^注释]:脚注内容



## 待办

- [x] 西瓜
- [ ] 苹果
- [ ] 鸭梨



## 页内跳转

[任意文字] (#标题名称)

如：[跳转到需要的标题](#表格)

如：人如果能凝视自然就好了<a name="第二种跳转"></a>

例：[我要跳转到前面去](#第二种跳转)



## 黄色高亮

==黄色高亮==





# 高级技巧



## 对齐

<h6 align="center">This is heading 1</h1>
<h6 align="right">This is heading 1</h1>

<h6 align="left">This is heading 1</h1>


## 引用

<p>以下内容引用自 WWF 的网站：</p>
<blockquote cite="http://www.worldwildlife.org/who/index.html">
五十年来，WWF 一直致力于保护自然界的未来。
世界领先的环保组织，WWF 工作于 100 个国家，
并得到美国一百二十万会员及全球近五百万会员的支持。
</blockquote>


## 隐藏文字

<p hidden="hidden">这是一段隐藏的段落。</p>
<p>这里有一段隐藏段落。</p>



## 占位符

空格：&nbsp

上标注释中也可用。



## 换行

```
<br />
```



## 嵌入

有些网站提供基于iframe的嵌入代码，你也可以将其粘贴到Typora中，例如：

<iframe height='265' scrolling='no' title='Fancy Animated SVG Menu' src='http://codepen.io/jeangontijo/embed/OxVywj/?height=265&theme-id=0&default-tab=css,result&embed-version=2' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'></iframe>



## 视频

<video src="D:\[存档]\[影视]\[游戏录制]\合金装备5\Metal Gear Solid V  The Phantom Pain 09.18.2017 - 17.09.25.02.mp4" />

> 本地地址：D:\[存档]\[影视]\[游戏录制]\合金装备5\Metal Gear Solid V  The Phantom Pain 09.18.2017 - 17.09.25.02.mp4
>
> - [x] 尝试网络地址视频



<video src="https://home.miui.com/videos/landing-page-video.mp4" />



## 折叠菜单

<details>
<summary>菜单</summary>
菜单内容
</details>

```text
<details>
<summary>菜单</summary>
菜单内容
</details>
```





# 表格



## 不规则表格

<!doctype html>
<html>
   <head>
      <meta charset="utf-8">
      <title>table</title>
   </head>
   <style media="screen">
      table{
         border-collapse: collapse;
      }
   </style>
   <body>
      <table width="300px" height="300px" border="1px">
         <tr>
            <td colspan="2">11</td>
            <td rowspan="2">13</td>
         </tr>
         <tr>
            <td rowspan="2">21</td>
            <td>22</td>
         </tr>
         <tr>
            <td colspan="2">32</td>
         </tr>
      </table>
   </body>
</html>


## 人物简介

<table border=2>
    <tr><td colspan=4>清川清正<br />きよかわ きよま</td>
    <tr><td width="125">身高</td><td colspan=3>171</td>
    <tr><td>生日</td><td colspan=3>4月3日</td>
    <tr><td>印象动物</td><td colspan=3>猫</td>
    <tr><td>梦想</td><td colspan=3>世界和平</td>
    <tr><td>志愿</td><td colspan=3>就职于出版公司或动漫行业</td>
    <tr><td>喜好</td><td colspan=3>咖啡、芒果、虚拟偶像</td>
    <tr><td>厌恶</td><td colspan=3>狗、社交、集体活动</td>
    <tr><td>&nbsp;&nbsp;&nbsp;介绍</td><td colspan=3><br />性格淡然，自甘孤独的平凡高中生。家中有一位同岁的姐姐，父母是在附近企业工作的高层人员。内心忧郁且敏感，是一位悲观主义者。<br />曾经维持着充实的生活，但对脆弱的人际关系感到失望而选择退步。<br />目前正承担着身为独立画师力所能及的相关工作，在与椎名穹乃的相处中逐渐认识到了人与人之间关系的真正意义，同时在试图用与穹乃所不同的方法找到属于自己的答案。<br />&nbsp;</td>
    </tr></table>


#### 一个好看的表格

<table border="2">
    <tr>
    <th>Global<br />Class</th>
    <td>2年C班</td>
    </tr>
    <tr>
        <th rowspan="2" align="center">英语课</th>
        <td align="left">08:30~</td>
    </tr>
    <tr>
    <td align="right">09:20</td>
    </tr>
</table>
<table border="2">
    <tr>
    <td>起源</td>
    <td>厄洛尔·卡什</td>
    </tr>
    <tr>
        <td rowspan="2" align="center">星境起源</td>
        <td align="left">AD1993~</td>
    </tr>
    <tr>
    <td align="right">AD2035</td>
    </tr>
</table>



## AUS介绍

<table border=2>
    <tr><td colspan=6>类型：</td><td colspan=18>先锋型</td></tr>
    <tr><td colspan=6>内部型号：</td><td colspan=18>H301 T3-A</td></tr>
    <tr><td colspan=4>操作</td><td colspan=4>机动</td><td colspan=4>攻击</td><td colspan=4>防御</td><td colspan=4>扩展</td><td colspan=4>性能</td></tr>
    <tr><td colspan=4>7</td><td colspan=4>10</td><td colspan=4>7</td><td colspan=4>6</td><td colspan=4>7</td><td colspan=4>7.4</td></tr>
</table>




# 图片



## HTML 图片调整

- 图片尺寸

<div align="center"><img width="300" height="280" src="https://gitee.com/Nafish/images/raw/master/img/B46215D97FFFD0B6AC57D5DAA151F68B.jpg"/></div>

- 图片并列

<div align="center"> <img src="https://gitee.com/Nafish/images/raw/master/img/B46215D97FFFD0B6AC57D5DAA151F68B.jpg" height="300px" alt="图片说明" ><img src="https://gitee.com/Nafish/images/raw/master/img/B46215D97FFFD0B6AC57D5DAA151F68B.jpg" height="300px" alt="图片说明" >   </div>



- 图片对齐

  <img src='https://gitee.com/Nafish/images/raw/master/img/64380cd7912397dd1e880df45582b2b7d1a28749' style='float:left; width:300px;height:100 px'/>



## HTML 文字环绕

<div style="float: left; clear: both;" align="left">
<img width="300" height="280" src="https://gitee.com/Nafish/images/raw/master/img/B46215D97FFFD0B6AC57D5DAA151F68B.jpg" align=right hspace="5" vspace="5"/>
通常在计算方面，推动处理器技术的发展主要是通过减小特性大小和增加时钟速率来实现的。我们只是把晶体管做得越来越小，从240纳米，到65纳米，再到14纳米，再到现在智能手机上的7纳米设计。晶体管越小，开关所需的电压就越低。这就是为什么具有更大特征尺寸的老处理器基本上不受辐射影响——具体来说，不受所谓的单事件扰动(SEUs)的影响。粒子撞击产生的电压太低，无法真正影响足够大的计算机的运行。但是，当面向太空的人类缩小尺寸，在芯片上安装更多的晶体管时，这些粒子产生的电压就足以制造麻烦了。
</div>





待办






# 学习区








<!DOCTYPE html>
<html lang="zh-CN">
<head>
  <title>table-test</title>
  <style>
    table {
      border: solid 2px black;
    }
  </style>
</head>
<body>
  <table>
    <tr>
      <td>hellow</td>
      <td>world</td>
      <td>hellow</td>
      <td>world</td>
    </tr>

lightblue





```html
<!DOCTYPE html>
<html style="height: 100%">
   <head>
       <meta charset="utf-8">
   </head>
   <body style="height: 100%; margin: 0">
       <div id="container" style="height: 100%"></div>
       <script type="text/javascript" src="http://echarts.baidu.com/gallery/vendors/echarts/echarts.min.js"></script>
       <script type="text/javascript" src="http://echarts.baidu.com/gallery/vendors/echarts-gl/echarts-gl.min.js"></script>
       <script type="text/javascript" src="http://echarts.baidu.com/gallery/vendors/echarts-stat/ecStat.min.js"></script>
       <script type="text/javascript" src="http://echarts.baidu.com/gallery/vendors/echarts/extension/dataTool.min.js"></script>
       <script type="text/javascript" src="http://echarts.baidu.com/gallery/vendors/echarts/map/js/china.js"></script>
       <script type="text/javascript" src="http://echarts.baidu.com/gallery/vendors/echarts/map/js/world.js"></script>
       <script type="text/javascript" src="http://api.map.baidu.com/api?v=2.0&ak=ZUONbpqGBsYGXNIYHicvbAbM"></script>
       <script type="text/javascript" src="http://echarts.baidu.com/gallery/vendors/echarts/extension/bmap.min.js"></script>
      
       <script type="text/javascript">
var dom = document.getElementById("container");
var myChart = echarts.init(dom);
var app = {};
option = null;
option = {
    title: {
        text: '基础雷达图'
    },
    tooltip: {},
    legend: {
        data: ['预算分配（Allocated Budget）', '实际开销（Actual Spending）']
    },
    radar: {
        // shape: 'circle',
        name: {
            textStyle: {
                color: '#fff',
                backgroundColor: '#999',
                borderRadius: 3,
                padding: [3, 5]
           }
        },
        indicator: [
           { name: '销售（sales）', max: 65},
           { name: '管理（Administration）', max: 160},
           { name: '信息技术（Information Techology）', max: 300},
           { name: '客服（Customer Support）', max: 380},
           { name: '研发（Development）', max: 520},
           { name: '市场（Marketing）', max: 250}
        ]
    },
    series: [{
        name: '预算 vs 开销（Budget vs spending）',
        type: 'radar',
        // areaStyle: {normal: {}},
        data : [
            {
                value : [43, 100, 280, 350, 500, 190],
                name : '预算分配（Allocated Budget）'
            },
             {
                value : [50, 140, 280, 310, 420, 210],
                name : '实际开销（Actual Spending）'
            }
        ]
    }]
};;
if (option && typeof option === "object") {
    myChart.setOption(option, true);
}
       </script>
   </body>
</html>
```





<details>
<summary>菜单</summary>
菜单内容
菜单内容2
</details>




- Emoji

:cry:





- 数学公式


$$
\mathbf{V}_1 \times \mathbf{V}_2 =  \begin{vmatrix}
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
\frac{\partial X}{\partial u} &  \frac{\partial Y}{\partial u} & 0 \\
\frac{\partial X}{\partial v} &  \frac{\partial Y}{\partial v} & 0 \\
\end{vmatrix}
$$






Markdown

:Text-to-HTML conversion tool

Authors

: John

: Luke



- 缩写

The <abbr title="People's Republic of China">PRC</abbr> was founded in 1949.

The <abbr title="Hyper Text Markup Language">HTML</abbr> specification is maintained by the <abbr title="World Wide Web Consortium">W3C</abbr>.





==Ω==



This is [an example](http://example.com/ "Title") inline link.

[This link](http://example.net/) has no title attribute.





**音乐**

-----

<p>这里是一首歌</p>
<video src="F:\[缓冲区]\网易云音乐下载\ShibayanRecords - タイニーリトル・アジアンタム.mp3" />

----









**HTML**

* [HTML]:1111





* [HTML]:wadwa









```
<!-- 这是一段注释 -->

<p>这是一个段落。</p>

<!-- 记得在此处添加信息 -->
```









### 其它





#### 选择列表 \<select\>

- 创建带有4个选项的选择列表

<select>
  <option value ="volvo">Volvo</option>
  <option value ="saab">Saab</option>
  <option value="opel">Opel</option>
  <option value="audi">Audi</option>
</select>





#### 注册机 \<keygen\>

<form action="demo_keygen.asp" method="get">
Username: <input type="text" name="usr_name" />
Encryption: <keygen name="security" />
<input type="submit" />
</form>

















<form>
  <fieldset>
    <legend>health information</legend>
    height: <input type="text" />
    weight: <input type="text" />
  </fieldset>
</form>











```
<frameset cols = "25%, 25%,*">
  <noframes>
  <body>Your browser does not handle frames!</body>
  </noframes>
  <frame src ="venus.htm" />
  <frame src   ="sun.htm" />
  <frame src ="mercur.htm"   />
</frameset>
```

```
<img src="planets.jpg" border="0" usemap="#planetmap" alt="Planets" />

<map name="planetmap" id="planetmap">
  <area shape="circle" coords="180,139,14" href ="venus.html" alt="Venus" />
  <area shape="circle" coords="129,161,10" href ="mercur.html" alt="Mercury" />
  <area shape="rect" coords="0,0,110,260" href ="sun.html" alt="Sun" />
</map>
```















