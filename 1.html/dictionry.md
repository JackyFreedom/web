

<HTML>,Said this is html file 

<HEAD>,Wrap file title use script style wait   
<TITLE>---</TITLE>,Wrap file title,title show in browser

</HEAD>,<HEAD> End tag

<BODY>,Place show tag and attribute in browser , content show in browser.

</BODY>,<BODY>End tag

</HTML>,<HTML>End tag

 

Other all tag use in <BODY></BODY>:

<A,HREF="…"></A>,Link tag,"…"is file address

<IMG,SRC="…">,Show img tag,"…"is file address

<BR>,Line feed tag

<P>,Piecevise tag

<B></B>,Use black font

<I></I>,Use italic word

<HR>,Level draw line

<TABLE></TABLE>,define,important tag in  HTML

<TR></TR>,Said table row,use in <TABLE></TABLE>

<TD></TD>,Said table cell,use in<TR></TR>

<FONT></FONT>,Word style tag

 

Attribute:

 Attribute is use to modify tag,attribute use in start tag
example:attribute bgcolor="BLACK" Said background color is black.

reference attribute's example:

<BODY,bgcolor="BLACK"></BODY>Said page background is black;

<TABLE,bgcolor="BLACK"></TABLE>Said table background is black.

 

Often attribute:

For attribute,range attribute:

ALIGN=LEFT,for left(default value),WIDTH=pixel or percentage,object width.

ALIGN=CENTER,content,HEIGHT=pixel or percentage ,object hieght.

ALIGN=RIGHT,for right.

Color attribute:

COLOR=#RRGGBB,before color,core table.

BGCOLOR=#RRGGBB,background.

 

<center>Said to center.

 

<table></table>table tag start and end.

attribute:

cellpadding=Number unit is pixel,define table's padding

cellspacing=Number unit is pixel ,define table meta margin

border=Number unit is pixel,define table border width

width=Number unit is pixel,define table width

background=Image link address,defin table background

<tr></tr>Table in row start and end;

<td></td>Table in cell start and end

Attribute:

Colspan="",Cell acorss column;

Rowspan="",Cell acorss row;

Width="";Define table width

Height="";Define table height

Align="";Alignment

Valign="";

Border="",Border width;

Bgcolor="",Background color;

Bordercolor="",Border color;

Bordercolorlight="",Border bright color;

Bordercolordark="",Border dark color;

Cellpadding="",Content to border lenght(default 2);

Cellspacing="",Cell between lenght(default 2);

 

<br>Force line feed

<font></font>Text tag's start and end 

Attribute:

face=word

color=color

<b></b>Bold word tag's start and end

Attribute:

style=font-size:40pt;,Use style set font size,this is 40 point

<div></div>,Distinction tag start and end

属性:

align=|center|left|right|水平对齐方式

<marquee></marquee>动态标识的开始和结束,如标识内放置贴图格式则可实现图片滚动

属性:

scrollamount=1~60,滚动速度

direction=|left|right|up|down|,滚动方向

scrolldelay=滚动延时,单位:毫秒

<P>段落标识,

 空格符,

<img>贴图标识

属性:

src=../../图片链接地址,贴图标识必备属性

style=filter:Alpha(opacity=100,style=2);

filter:样式表滤镜;

Alpha:透明滤镜,

opacity:不透明度100(0~100);

style:样式2(0~3),

rules="none"不显示内框"

<embed,src="…">多媒体文件标识

属性:

SRC="../../FILENAME",

设定音乐文件的路径,文件类型除了可以播放.rm;.mp3;.wav等音频,还可播放.swf和.mov等视频.

AUTOSTART=TRUE/FALSE,

是否要音乐文件传送完就自动播放,TRUE是要,FALSE是不要,默认为FALSE

LOOP=,设定播放重复次数,LOOP=6表示重复6次,true或-1为无限循环,false为播放一次即停止.

STARTIME="分:秒",

设定乐曲的开始播放时间,如20秒后播放写为STARTIME=00:20

VOLUME=0-100,

设定音量的大小.如果没设定的话,就用系统的音量.

WIDTH,HEIGHT,

设定控制面板的大小,都设为0可隐藏播放器

HIDDEN=TRUE,

隐藏控制面板

CONTROLS=CONSOLE/SMALLCONSOLE,

设定控制面板的样子,

<bgsound,src="…">,背景音乐标识,只能用于.wav和.mp3格式.

属性:

LOOP=,设定播放重复次数,LOOP=6表示重复6次,true或-1为无限循环,false为播放一次即停止.

 

表单标签:

<form></form>表格标识的开始和结束,表单的内容都放在这里.

下边的标签放在表单内:

<select>下拉选择框

<option></option>

</select>

属性:

Multiple,多选

<textarea></textarea>,大量文字输入的编辑块

属性:

Cols="",行;

Rows="",列;

<input,type="text">,文本框

<input,type="password">,密码框

<input,type="submit">,提交按扭

<input,type="checkbox">,复选框

<input,type="radio">,单选框

<input,type="reset">,重置按扭

<input,type="image">,图片按扭

<input,type="hidden">,隐藏域

<input,type="button">,按扭

<input,type="file">,浏览文件

公共属性:

Name="";

Value=""

Size=""

 

框架标签:

<FRAMESET>...</FRAMESET>,定义框架.

<FRAME>,放在框架标签内,定义每个框架的内容.

属性:

Cols=""

Rows=""

Frameborder=""

Framespacing=""

src=""

Scrolling="",滚动条(No,Yes);

Noresize,框加大小不可变;

Marginhight="",高度空余空间;

Marginwidth="",宽度空余空间;

Target="",目标框架.

 

其他标签:

<bgsound>,背景音乐;

Src=""

Loop="",循环次数;

<embed>,媒体播放块;

Src=""

Loop="",循环次数;

<marquee></marquee>,滚动部分;

属性:

Bgcolor=""

Behavior,设置或获取文本如何在字幕中滚动.

Direction="",滚动方向;

Height=""

Width=""

Loop="",环次数;

scrollAmount="",设置或获取介于每个字幕绘制序列之间的文本滚动像素数.

scrollDelay="",设置或获取字幕滚动的速度.

scrollHeight="",获取对象的滚动高度;

scrollLeft="",设置或获取位于对象左边界和窗口中目前可见内容的最左端之间的距离.

scrollTop="",设置或获取位于对象最顶端和窗口中可见内容的最顶端之间的距离.

trueSpeed="",设置或获取字幕的位置是否使用scrollDelay和scrollAmount属性计算,已过的实际时间来自于时钟计时.

 

<!--...-->,注释标记,在"<!--"与"-->"之间的内容将不在浏览器中显示.

 

--

 

基本标签:

<html></html>,创建一个HTML文档;

<head></head>,设置文档标题和其它在网页中不显示的信息;

<title></title>,设置文档的标题;

<h1></h1>,最大的标题;

<pre></pre>,预先格式化文本;

<u></u>,下划线

<b></b>,黑体字;

<i></i>,斜体字;

<tt></tt>,打字机风格的字体;

<cite></cite>,引用,通常是斜体;

<em></em>,强调文本(通常是斜体加黑体);

<strong></strong>,加重文本(通常是斜体加黑体);

<font,size="",color=""></font>,设置字体大小从1到7,颜色使用名字或RGB的十六进制值;

<BASEFONT></BASEFONT>,基准字体标记;

<big></big>,字体加大;

<SMALL></SMALL>,字体缩小;

<STRIKE></STRIKE>,加删除线;

<CODE></CODE>,程式码;

<KBD></KBD>,键盘字;

<SAMP></SAMP>,范例;

<VAR></VAR>,变量;

<BLOCKQUOTE></BLOCKQUOTE>,向右缩排;

<DFN></DFN>,述语定义;

<ADDRESS></ADDRESS>,地址标记;

<sup></SUP>,上标字;

<SUB></SUB>,下标字;

<xmp>...</xmp>固定宽度字体(在文件中空白、换行、定位功能有效)

<plaintext>...</plaintext>固定宽度字体(不执行标记符号);

<listing>...</listing>,固定宽度小字体;

<font,color=00ff00>...</font>字体颜色;

<font,size=1>...</font>最小字体;

<font,style,='font-size:100,px'>...</font>无限增大.

 

格式标签:

 

<p></p>,创建一个段落;

<p,align="">,将段落按左、中、右对齐;

<br>,换行,插入一个回车换行符;

<blockquote></blockquote>,从两边缩进文本;

 

<dl></dl>,列表标签,定义列表;

<dt>,定义列表标题;

<dd>,定义列表内容;

例:

<dl>

<dt>标题1</dt>

<dd>内容11</dd>

<dd>内容12</dd>

<dt>标题2</dt>

<dd>内容21</dd>

<dd>内容22</dd>

</dl>

 

<ol></ol>,列表标签,定义一个标有数字的列表;

 

<ul></ul>,列表标签,定义一个标有圆点的列表;

<li>,放在每个列表项之前;

放在<ol></ol>之间则每个列表项加上一个数字,放在<ul></ul>之间则每个列表项加上一个圆点;

 

<div,align=""></div>,分区标签,用来排版大块HTML段落,也用于格式化表;

<MENU>,选项清单;

<DIR>,目录清单;

<nobr></nobr>,强行不换行;

<hr,size='9',width='80%',color='ff0000'>水平线(设定宽度);

<center></center>,水平居中.

 

链接标签:

<a,href="URL"></a>,创建超文本链接;

<a,href="mailtEMAIL">

</a>,创建自动发送电子邮件的链接;

<a,name="name"></a>,创建位于文档内部的书签;

<a,href="#name"></a>,创建指向位于文档内部书签的链接;

<BASE>,文档中不能被该站点辨识的其它所有链接源的URL;

<LINK>,定义一个链接和源之间的相互关系;

 

链接标签注解:

target="...",决定链接源在什么地方显示(用户自定义的名字,_blank,_parent,_self,_top);

rel="...",发送链接的类型;

rev="...",保存链接的类型;

accesskey="...",指定该元素的热键;

shape="...",允许我们使用已定义的形状定义客户端的图形镜像(default,rect,circle,poly);

coord="...",使用像素或者长度百分比来定义形状的尺寸;

tabindex="...",使用定义过的tabindex元素设置在各个元素之间的焦点获取顺序(使用tab键使元素获得焦点).

 

表格标签:

<table></table>,创建一个表格;

<tr></tr>,表格中的每一行;

<td></td>,表格中一行中的每一个格子;

<th></th>,设置表格头:通常是黑体居中文字;

<table,cellspacing="">,设置表格格子之间空间的大小;

<table,border="">,设置边框的宽度;

<table,cellpadding="">,设置表格格子边框与其内部内容之间空间的大小;

<table,width="">,设置表格的宽度.用绝对像素值或总宽度的百分比;

<table,align="">,设置表格格子的水平对齐方式(left,center,right,justify);

<tr,align="">,设置表格格子的水平对齐方式(left,center,right,justify);

<tr,valign="">,设置表格格子的垂直对齐方式(baseline,bottom,middle,top);

<td,colspan="">,设置一个表格格子跨占的列数(缺省值为1);

<td,rowspan="">,设置一个表格格子跨占的行数(缺省值为1);

<td,nowrap>,禁止表格格子内的内容自动断行;

<CAPTION></CAPTION>,表格的标题;

<COLGROUP></COLGROUP>,定义多个列为一组列;

<TABLE></TABLE>,创建一个表格;

<THEAD></THEAD>,定义表格的页眉;

<COL>,定义一个列组中的列，以便对它们能够同时设置有关属性;

<TBODY></TBODY>,定义一个表格的实体;

<TFOOT></TFOOT>,定义一个表格的页脚;

 

表单标签:

<form></form>,创建表单;

action="...",接收数据的服务器的URL;

method="...",HTTP的方法(get,,post),其中get是被反对使用的;

enctype="...",指定MIME(Internet媒体类型);

onsubmit="...",当提交表单时发生的内部事件;

noreset="...",在重新设置表单时发生的内部事件;

target="...",决定把内容显示在什么地方(_blank,_parent,_self,_top)

<select,multiple,name="name",size=""></select>,创建滚动菜单,size设置在需要滚动前可以看到的表单项数目;

<option>,设置每个表单项的内容;

<select,name="name"></select>,创建下拉菜单;

<textarea,name="name",cols=40,rows=8></textarea>,创建一个文本框区域,列的数目设置宽度,行的数目设置高度;

<input,type="checkbox",name="name">,创建一个复选框,文字在标签后面;

<input,type="radio",name="name",value="">,创建一个单选框,文字在标志后面;

<input,type=text,name="foo",size=20>,创建一个单行文本输入区域,size设置以字符串的宽度;

<input,type="submit",value="name">,创建提交(submit)按钮;

<input,type="image",border=0,name="name",src="name.gif">,创建一个使用图象的提交(submit)按钮;

<input,type="reset">,创建重置(reset)按钮;

<BUTTON></BUTTON>,创建一个按钮;

disabled="...",把按钮的状态设置为不能;

name="...",按钮的控制名,value="...",按钮的值;

type="...",按钮的类型(button,,submit,,reset);

<FIELDSET></FIELDSET>,把相互关联的控件组合成一组;

<ISINDEX>,提示用户输入;

<LABEL></LABEL>,为一个控件提供标签;

<LEGEND></LEGEND>,为FIELDSET元素指定一标题;

<SELECT></SELECT>,为用户做选择创建各个选项;

<TEXTAREA></TEXTAREA>,创建一个允许用户多行输入的区域.

 

表单标签注解:

type="...",用于输入控件的类型(text,password,checkbox,radio,submit,reset,file,hidden,image,button);

name="...",控件的控制名(要求是除了submit和reset之外的任何名字);

value="...",控件的初始值;

checked="...",把一个单选钮设置为选中的状态;

disabled="...",把控件的状态设置为不能使用;

readonly="...",只对输入密码的文本框使用;

size="...",表示以像素为单位的除了文本框和密码框控件之外的其它控件的宽度,它是用来指定字符的数目;

src="...",一个图像控件的URL;

maxlength="...",指定可以输入的最多的字符数目;

alt="...",另外一种文本描述;

usemap="...",到客户端图形镜像的URL;

align="...",被反对.控制对齐方式(left,,center,,right,,justify);

tabindex="...",通过定义的tabindex值确定在不同元素之间获得焦点的顺序;

onfocus="...",当元素获得焦点时发生的事件;

onblur="...",当元素失去焦点时发生的事件;

onselect="...",当元素被选中时发生的事件;

onchang="...",当元素状态被改变时发生的事件;

accept="...",允许上载的文件类型.

 

帧标签(框架标签):

<frameset></frameset>,放在一个帧文档的<body>标签之前,也可以嵌在其他帧文档中;

<frameset,rows="value,value">,定义一个帧内的行数,可用像素值或高度百分比;

<frameset,cols="value,value">,定义一个帧内的列数,可用像素值或宽度百分比;

<frame>,定义一个帧内的单一窗或窗区域;

<noframes></noframes>,定义在不支持帧的浏览器中显示什么提示;

<frame,src="URL">,规定帧内显示的HTML文档;

<frame,name="name">,命名帧或区域以便别的帧可以指向它;

<frame,marginwidth="">,定义帧左右边缘的空白大小,必须大于等于1;

<frame,marginheight="">,定义帧上下边缘的空白大小,必须大于等于1;

<frame,scrolling="">,设置帧是否有滚动栏,其值可以是"yes","no",或"auto";

<frame,noresize>,禁止用户调整一个帧的大小;

<IFRAME></IFRAME>,创建一个内联的帧;

scr="...",定义在帧中显示的内容的来源;

frameborder="...",定义帧之间的边界(0或1);

align="...",被反对,控制对齐方式(left,,center,,right,,justify);

height="...",帧的高度,width="..."帧的宽度;

<marquee>...</marquee>,普通卷动;

<marquee,behavior=slide>...</marquee>,滑动;

<marquee,behavior=scroll>...</marquee>,预设卷动;

<marquee,behavior=alternate>...</marquee>,来回卷动;

<marquee,direction=down>...</marquee>,向下卷动;

<marquee,direction=up>...</marquee>,向上卷动;

<marquee,direction=right></marquee>,向右卷动;

<marquee,direction='left'></marquee>,向左卷动;

<marquee,loop=2>...</marquee>,卷动次数;

<marquee,width=180>...</marquee>,设定宽度;

<marquee,height=30>...</marquee>,设定高度;

<marquee,bgcolor=FF0000>...</marquee>,设定背景颜色;

<marquee,scrollamount=30>...</marquee>,设定卷动距离;

<marquee,scrolldelay=300>...</marquee>,设定卷动时间;

<img,src="">,插入图片,参数有:width="宽",alt="说明文字",height="高",boder="边框".

 

文档整体属性标签:

<body,bgcolor="">,设置背景颜色.使用名字或RGB的十六进制值;

<body,background="">,设置背景图片;

<body,bgsound="">,设置背景音乐;

<body,bgproperties="fixed">,固定背景图片(IE适用);

<body,text="">,设置文本颜色.使用名字或RGB的十六进制值;

<body,link="">,设置链接颜色.使用名,字或RGB的十六进制值;

<body,vlink="">,设置已使用的链接的颜色.使用名字或RGB的十六进制值;

<body,alink="">,设置正在被击中的链接的颜色.使用名字或RGB的十六进制值;

<body,topmargin="">,设置页面的上边距;

<body,leftmargin="">,设置页面的左边距.