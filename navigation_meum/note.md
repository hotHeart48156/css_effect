css                        选择器
.class类                        选择器
#id id                        选择器
* 所有元素
element 所有的element
element,element1所有的element和element1
element element1                        选择element元素下的所有elemenet1
element>element1                        选择element下的第一个element1，或者                        选择父级是element的element1.
element+element1紧接着element的element1元素



有关a元素的伪元素
:link	a:link	选择所有未访问链接
:visited	a:visited	选择所有访问过的链接
:active	a:active	选择活动链接
:hover	a:hover	选择鼠标在链接上面时
[attribute^=value]	a[src^="https"]	选择每一个src属性的值以"https"开头的元素
[attribute$=value]	a[src$=".pdf"]	选择每一个src属性的值以".pdf"结尾的元素
[attribute*=value]	a[src*="runoob"]	选择每一个src属性的值包含子字符"runoob"

有关p元素
:first-letter	p:first-letter	选择每一个<p>元素的第一个字母
:first-line	p:first-line	选择每一个<p>元素的第一行
:first-child	p:first-child	。	指定只有当<p>元素是其父级的第一个子级的样式
:before	p:before	在每个<p>元素之前插入内容
:after	p:after	在每个<p>元素之后插入内容
:lang(language)	p:lang(it)	选择一个lang属性的起始值="it"的所有<p>元素
element1~element2		p~ul 	选择p元素之后的每一个ul元
:first-of-type	p:first-of-type	选择每个p元素是其父级的第一个p元素
:last-of-type	p:last-of-type	选择每个p元素是其父级的最后一个p元素
:only-of-type	p:only-of-type	选择每个p元素是其父级的唯一p元素
:only-child	p:only-child	选择每个p元素是其父级的唯一子元素
:nth-child(n)	p:nth-child(2)	选择每个p元素是其父级的第二个子元素
:nth-last-child(n)	p:nth-last-child(2)	选择每个p元素的是其父级的第二个子元素，从最后一个子项计数
:nth-of-type(n)	p:nth-of-type(2)	选择每个p元素是其父级的第二个p元素
:nth-last-of-type(n)	p:nth-last-of-type(2)	选择每个p元素的是其父级的第二个p元素，从最后一个子项计数
:last-child	p:last-child	选择每个p元素是其父级的最后一个子级



display标签
none	此元素不会被显示。
block	此元素将显示为块级元素，此元素前后会带有换行符。
inline	默认。此元素会被显示为内联元素，元素前后没有换行符。
inline-block	行内块元素。（CSS2.1 新增的值）
list-item	此元素会作为列表显示。
run-in	此元素会根据上下文作为块级元素或内联元素显示。
compact	CSS 中有值 compact，不过由于缺乏广泛支持，已经从 CSS2.1 中删除。
marker	CSS 中有值 marker，不过由于缺乏广泛支持，已经从 CSS2.1 中删除。
table	此元素会作为块级表格来显示（类似 <table>），表格前后带有换行符。
inline-table	此元素会作为内联表格来显示（类似 <table>），表格前后没有换行符。
table-row-group	此元素会作为一个或多个行的分组来显示（类似 <tbody>）。
table-header-group	此元素会作为一个或多个行的分组来显示（类似 <thead>）。
table-footer-group	此元素会作为一个或多个行的分组来显示（类似 <tfoot>）。
table-row	此元素会作为一个表格行显示（类似 <tr>）。
table-column-group	此元素会作为一个或多个列的分组来显示（类似 <colgroup>）。
table-column	此元素会作为一个单元格列显示（类似 <col>）
table-cell	此元素会作为一个表格单元格显示（类似 <td> 和 <th>）
table-caption	此元素会作为一个表格标题显示（类似 <caption>）
inherit	规定应该从父元素继承 display 属性的值。



标签下加花括号表示标签内部的值,美元符号代表序号
例如a{值$}



布局



伪元素




