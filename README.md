<!HTML learning>

### __H__~~tm~~`l`
---

<!DOCKTYPE html>  
```html
<html>
    <head>
        <title> Webpage </title>
    </head>

    <body>
        I am sareng.</br>
        This is my first html programme.</br>
        I am intersted in learning programme.
    </body>
</html>
```  
<image src="./images/initial.png" width="500" title="initial"/>  

### Inside head tag

```html
<!DOCKTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width,initial-scale=1.0">
        <meta name="description" content="Free html tutorial"/>
        <meta name="keywords" content="html,HTML"/>
        <meta name="author" content="sareng sa">
        <style>
            body{
                background-color: aqua;
            }
        </style>   

        <link rel="stylesheet" href="style.css">
        <script src="index.js"></script>
        <title> dipraj sareng </title>
    </head>
    <body>

    </body>
</html>
```

- [x]  Heading Size
- [x]  Horizontal Rule
- [x]  paragraph
- [x]  align
- [x]  

```html
<!DOCTYPE html>
<html>
    <head>
        <title>The Webpage</title>
    </head>
    <body>
        <h1 align="center">Bangladesh</h1><hr/>
        <p align="center"> Bangladesh is beautiful country.It is a pert of asia.This country was famous for agriculture and most cheapest cost for labour. For this reason western country invest for making clothes and other things.</p> <p align="justify"> This country is also famous for sundarban. The world most beautiful and biggest mangrove . The royel bangle tiger is origin of bangladesh.</p><p align="right">There is lot of tourist spot in bangladesh but most common and beautiful is cox's bazar see beach and sajek hill and bandarban.</p>

        <h2>Bangladesh</h2>
        <h3>Bangladesh</h3>
        <h4>Bangladesh</h4>
        <h5>Bangladesh</h5>
        <h6>Bangladesh</h6>
    </body>
</html>
```

### style

- [x] text-align
- [x] color

```html
<!DOCKTYPE html>
<html>
    <head>
        <title></title>
    </head>
    <body style="background-color:AliceBlue;">
        <h1 style="text-align:center; color:blue;">Bangladesh</h1><hr/>
        </br>
        <h4 style="text-align:right; color:#663399;">Bangladesh is a beautiful country.This is the most populated country. Around 200 million people live inside of 1,48,460 km</h4></br>
        <h4 style="text-align:right; color:#00C9DD;">Taking Right & Using Hexadecimal color.</h4></br>
        <h4 style="text-align:left; color:rgb(0,144,191);">Taking Left & Using RGB color.</h4></br>
        <h3 style="text-align:center; color:DarkSeaGreen;">Taking Center & Using color name.</h3></br>
    </body>
</html>
```  
<image src="./images/style.png" width="500" title="style"/>

### Text Format

- [x] Normal
- [x] Small
- [x] Bold
- [x] Italic
- [x] Emphasized
- [x] Underline
- [x] inserted
- [x] Strike
- [x] Deleted
- [x] Superscript
- [x] Subscript
- [x] Marked

```html
<!DOCTYPE html>
<html>
    <head>
        <title> Text Format </title>
    </head>
    <body>
        Normal</br>
        <b>Bold</b></br>
        <i>Italic</i></br>
        <u>Underline</u></br>
        <strike>Strike</strike></br>
        super<sup>script</sup> (a+b)<sup>2</sup>= a<sup>2</sup>+2ab+b<sup>2</sup></br>
        sup<sub>script</sub> H<sub>2</sub>SO4</br>
        <pre> <p style="text-align:center; color:blue;">Trial</p></pre></br>
        <em> Emphasized </em> </br>
        <del> Deleted </del> </br>
        <small> Small </small> </br>
        <ins> Inserted </ins> </br>
        <mark> Marked </mark> </br>
    </body>
</html>
```  
<image src="./images/textformat.png" width="500" title="text-format"/>

### practice
---
</br>  

```html
<!DOCKTYPE html>
<html>
	<head>
		<title>Text format Trial</title>
	</head>
	<body>
		<b>Number System</b><p>
		<i>Digital Device</i><p>
		<u> Webdesign and HTML</u><p>
		<b><ins> C programming</ins></b><p>
		LOG<sub>10</sub>X<sup>3</sup><p>
		<small>This is <mark>sareng</mark></small><p>
		<del>Deleted Text</del></br>
	</body>
</html>
```
</br>

<image src="./images/practice.png" width="500" title="practice"/>

### html validate
validate html. upload file. lang & charset wanted
```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="utf-8">
        <title>Validate</title>
    </head>
    <body>
    </body>
</html>
```  
<image src="./images/validate.png" width="500" title="validate"/>

### Bangla font

```html  
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="utf-8">
        <title>বাংলা লিখা</title>
    </head>
    <body style="background-color:#A5E6F7;">
    <b><p style="text-align:center; color:rgb(159,62,51);"> আবু উবাইদা</p></b><hr color="rgb(171,71,188)" width="50%" size="5">
    <p>আমি একজন ছাত্র। আমার জন্ম বাংলাদেশে। আমি ঢাকার অধিবাসি। </p><i><p> এটাকে চর্চা বা অনুশীলন বলা যেতে পারে।</p></i>
    </body>
</html>
```  
<image src="./images/banglafont.png" width="500" title="Bangla Font"/>  

### Entity
- [x] &nbsp (non-breaking space)
- [x] &copy (copyright)
- [x] &lt (less-than)
- [x] &gt (greater-than)
- [x] <! Text Here> (comment) 
- [x] <xmp><pre> </pre></xmp> Type anything show it same on page.
- [x] <xmp><code> </code></xmp>
- [x] &lt;xmp&gt; &lt;/xmp&gt;
- [x] &amp is &

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="uft-8">
        <title>Entity</title>
    </head>
    <body>
        space &nbsp; &nbsp; &nbsp; extra = &ampnbsp; </br>
        &copy; Copyright tag = &ampcopy; </br>
        &lt; = &amplt; </br>
        &gt; = &ampgt; </br>
        invisible comment = <!comment> &lt;!comment&gt; </br>
        <pre>
            life is good
                life is bad
            study well
                work hard
        </pre> 
        <pre>
        &lt;pre&gt;
            life is good
                life is bad
            study well
                work hard
        &lt;/pre&gt;
        </pre>

        <xmp>
            &lt; < Less-than
            &gt; > Greater than
            &amp; & ampersand
            &nbsp;  non-breaking space
            &copy;  copyright
            &quot; " doubble quotation mark
            &apos; ' single quotation mark
            <pre></pre> for show the same type
            <code></code> same
        </xmp>

    </body>
</html>
```
<image src="images/entity.png" width="500" title="entity"/>  

### emoji

```html
<!DOCTYPE html>
<html>
    <head>
        <title></title>
    </head>
    <body>
        	⚽ copy and paste </br>
	        &#9917; using html code &amp#9917; </br>
            &amp# decimal; </br>
	        &amp#x Hex-decimal; </br>
	        &#9889; &amp#decimal-number9889;</br>
	        &#x2705; &amp#xhexa-decimal 2705;</br>
    </body>
</html>
```  
<image src="./images/emoji.png" width="500" title="Emoji"/>  

### Font Style 

```html
<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
        <title>Font Type</title>
    </head>
    <body>
        <font color="red" size="20px" face="fantasy">I love Bangladesh</font>
        <p style="background-color:red; font-size:20px; font-family:fantasy;">I Love Bangladesh</p>  
    </body>
</html>
```  
<image src="./images/fontstyle.png" width="500" title="Font-Style"/>  
</br>  

### order list

```html
<!DOCTYPE html>
<html lang="en">
	<head>
		<meta charset="UTF-8">  
		<title>Order List</title>
	</head>
	<body>
		<h2>Name of cources</h2>
		<ol>
		<li>BBA
		<li>CSE
		<li>EEE
		</ol>
		<h2> More cources</h2>
		<ol start="4">
		<li>LLB
		<li>Pharmacy
		<li>Architecht
		<li>Elictric
		</ol>
		
		<h2> Animals</h2>
		<ol type="A">
		<li>cow
		<li>cat
		<li>rat
		</ol>

		<h2>Furniture</h2>
		<ol type="I">
		<li>Chair
		<li>Table
		<li>Wardrobe
		</ol>
	</body>
</html>
```  
<image src="./images/orderlist.png" width="500" title="OrderList"/>  

### unorder list

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <title>UnOrder List</title>
    </head>
    <body>
        <h2>Department</h2>
        <ul>
            <li>BBA
            <li>CSE
            <li>EEE
        </ul>
        <h2> More </h2>
        <ul start="4">
            <li>Pharmacy
            <li>Architecht
            <li>Elictric
        </ul>

        <h2>Animals</h2>
            <ul type="square">
                <li>cow
                <li>cat
                <li>rat
            </ul>

        <h2>Furniture</h2>
        <ul type="circle">
            <li>chair
            <li>table
            <li>bed
        </ul>
    </body>
</html>
```  
<image src="./images/unorderlist.png" width="500" title="UnOrder-list"/>  

### add images & edit

- [x] add image
- [x] edit

<ol type="I">
<li> add url (source)
<li> width
<li> height
</ol>

<ol type ="I" start="4">
<li> title
<li> align (top,bottom,left,right)
<li> alt 
<li> hspace (Horizontal space left & right)
<li> vspace (Vertical space top & bottom)
<li> border
</ol>

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <title> ADD & EDIT IMAGE</title>
    </head>
    <body>
        <image src="C:\Users\osman\Downloads\stady\html\ramadan.jpg" width="300" height="350" title="Ramada 2024" align="top" alt="ramadan" hspace="500" vspace="100" border="5"/>
    </body>
</html>
```
<image src="./images/addimage.png" width="500" title="ramadan"/>
<image src="./images/errorimage.png" width="500" title="erroradding-image"/>  

### codepen.io  

add image

- [x] open postimg.cc
- [x] upload picture
- [x] copy past url to img tag, that it!

```html
<img src="https://i.postimg.cc/TYpQcY7P/ramadan.jpg" title="Ramadan2024" alt="ramdan calander not showing" border="5" align="right" hspace="200" vspace="20"/>
```
```css
img{
  height: 500px;
  width: 500px;
}
```

<image src="./images/codepen.png" width="500" title="codepen"/>  

### add website & youtube video

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <title>Add website & utube video</title>
    </head>
    <body>
        <iframe src="https://tasman.42web.io/?i=1" width="560" height="315"></iframe>

        <iframe width="560" height="315" src="https://www.youtube.com/embed/QiYk10IyULw?si=bJqwHcEeUzly9EXJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
    </body>
</html>
```  
![website&youtubevideo](./images/websiteyoutube.png)

<h1>Internel Hyper link</h1>

 part 1
### href"url"
### target"blank"

- [x] anchor (a)
- [x] hypertext (h)
- [x] reference (ref)
- [x] href (url)
- [x] target="blank" (tab with new link)
- [x] style="color:black; font-size:20px; font-family:fantasy;"


`<a href="url" target="blank" style="color:red; font-size:20px; font-family:fantasy;">`

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <title>Hypertext</title>
    </head>
    <body>
        <h2> select your information</h2>
		<ol type="I">
		<li>name
		<li>gender
		<a href="file:///C:/Users/osman/Downloads/stady/html/language.html"><li>language</a>
		</ol>
		<h2> more </h2>
		<ol type="I" start="4">
		<li>age
		<li>country
		</ol>
    </body>
</html>
```  
# part 2

```html
<!DOCTYPE html>
<html lang="en">
	<head>
		<meta charset="UTF-8">
		<title>hypertext new page</title>
	</head>
	<body>
		<h2 style="text-align:left; color:blue;"> Language </h2>
		<ul type="square">
		<li>Bangla
		<li>English
		<li>Urdu
		<li>Arabic
		</ul>
	</body>
</html>
``` 
<image src="./images/hypertext.gif" width="500" title="hypertext"/>  

### New Tab with hypertext link

<p style="color:white;"> * &lta href="url" target="blank">name&lt/a></p> 

```html
<!DOCTYPE html>
<html lang="en">
	<head>
		<meta charset="UTF-8">
		<title>HyperText</title>
	</head>
	<body>
		<h2> select your information</h2>
		<ol type="I">
		<li>name
		<li>gender
		<a href="file:///C:/Users/osman/Downloads/stady/html/language.html" target="blank"><li>language</a>
		</ol>
		<h2> more </h2>
		<ol type="I" start="4">
		<li>age
		<li>country
		</ol>
	</body>
</html>
```
```html
<!DOCTYPE html>
<html lang="en">
	<head>
		<meta charset="UTF-8">
		<title>hypertext new page</title>
	</head>
	<body>
		<h2 style="text-align:left; color:blue;"> Language </h2>
		<ul type="square">
		<li>Bangla
		<li>English
		<li>Urdu
		<li>Arabic
		</ul>
	</body>
</html>
```  
<image src="./images/newtablink.gif"/> 

<h1>External link</h1>



```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <title>External link</title>
    </head>
    <body>
        <ol type="A">
            <li><p style="text-align:center"><a href="http://www.google.com" target="blank" style="color:#D5E509; font-size:25px; font-family:fantasy;">Google</a> </p> </br>
            <li><p style="text-align:center"><a href="http://www.youtube.com" target="blank" style="color:red; font-size:25px; font-family:fantasy;">YouTube</a></p></br>
            <li><p style="text-align:center"><a href="http://www.tasman.42web.io" target="blank" style="color:rgb(0,213,234); font-size:25px; font-family:fantasy;">TasMan</a></p></br>
            <li><p style="text-align:center"><a href="C:\Users\osman\Desktop\ramadan.jpg" target="blank" style="color:blue; font-size:20px; font-family:fantasy; background-color:silver;"> Ramadan Calender 2024</a></p></br>
        </ol>
    </body>
</html>
```  
<image src="./images/external.gif"/>  

### same folder direct link 
<p> if the major file is in the same image or another html file folder, don't have to input address only file name will work </p>

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF=8">
        <title>Same folder Direct Link</title>
    </head>
    <body>
        <a href="test.html" target="blank" style="color:blue; font-size:25px; font-family:fantasy;">Test</a></br>
        <a href="test1.html" style="color:red; font-size:25px; font-family:fantasy;">Test1</a></br>
    </body>
</html>
```  

</br>

<image src="./images/directurl.gif"/>

### How to divide a page on html

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="utf-8">
        <title> Divided page </title>
    </head>
    <body>
        <div id="div1" style="background-color:lightgreen; height:200px; width:100%;">
            <p style="text-align:center; color:rgb(39,135,225);"> This is a paragraph inside div1 </p>
        </div>
        <div id="div2" style="background-color:lightblue; height:200px; width:100%;">
            <p> This is a paragraph inside div2 </p>
        </div>
        <div id="div3" style="background-color:lightyellow; height:200px; width:100%;">
            <p> This is a paragraph inside div3 </p>
        </div>
    </body>
</html>
```
<image src="./images/divide.png" title="divide" alt="image not found" height="200px" width="100%"/>

### HTML Table

<ol>
<li> Table Head <thead>
<li> Table body <tbody>
<li> Table foot <tfoot>
<li> Table row <tr>
<li> Table data <td>
<li> Table header <th>

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="utf-8">
        <title> HTML Table </title>
    </head>
    <body>
        <table border="2" height="200  " wedth="300">
            <thead>
                <tr align="center">
                    <th>Id </th>
                    <th>Name </th>
                    <th>GPA </th>
                </tr>
            </thead>
            <tbody>
                <tr align="center">
                    <td>18102041</td>
                    <td>ali banat</td>
                    <td>4.89</td>
                </tr>
                <tr align="center">
                    <td>18102042</td>
                    <td>abu ubaida</td>
                    <td>4.38</td>
                </tr>
                <tr align="center">
                    <td>18102043</td>
                    <td>hamza ali</td>
                    <td>3.97</td>
                </tr>

        </table>
    </body>
</html>
```
![table](./images/table.png)

### similar css style using

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="utf-8">
        <title> HTML Table </title>
		
		<style>
			table{
			height:200px;
			width:300px;
			border:1px solid pink;
			border-collapse:collapse;
			}
			td,tr{
			border:1px solid pink;
			text-align:center;
			padding:25px;
			}
			th{
			color:darkblue;
			border:1px solid silver;
			}
			caption{
			color:darkgreen;
			font-family:fantasy;
			font-size:18px;
			}
		</style>
    </head>
    <body>
        <table>
		<caption>
			Student details
		</caption>
            <thead>
                <tr>
                    <th>Id</th>
                    <th>Name</th>
                    <th>GPA</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>18102041</td>
                    <td>ali banat</td>
                    <td>4.89</td>
                </tr>
                <tr>
                    <td>18102042</td>
                    <td>abu ubaida</td>
                    <td>4.38</td>
                </tr>
                <tr>
                    <td>18102043</td>
                    <td>hamza ali</td>
                    <td>3.97</td>
                </tr>

        </table>
    </body>
</html>
```
<image src="./images/collapce.png"/>

### alternative

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="utf-8">
        <title> HTML Table </title>
		
		<style>
			table{
			height:200px;
			width:300px;
			border:1px solid pink;

			border-spacing:5px;
			}
			td,tr{
			border:1px solid pink;
			text-align:center;
			padding:25px;
			}
			th{
			color:darkblue;
			border:1px solid silver;
			}
			caption{
			color:darkgreen;
			font-family:fantasy;
			font-size:18px;
			}
		</style>
    </head>
    <body>
        <table>
		<caption>
			Student details
		</caption>
            <thead>
                <tr>
                    <th>Id</th>
                    <th>Name</th>
                    <th>GPA</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>18102041</td>
                    <td>ali banat</td>
                    <td>4.89</td>
                </tr>
                <tr>
                    <td>18102042</td>
                    <td>abu ubaida</td>
                    <td>4.38</td>
                </tr>
                <tr>
                    <td>18102043</td>
                    <td>hamza ali</td>
                    <td>3.97</td>
                </tr>

        </table>
    </body>
</html>
```
<image src="./images/borderspacing.png"/>

### rowspan and colspan/merge

```html
<!DOCTYPE html>
<html lang="en">
	<head>
		<meta charset="utf-8">
		<title> Rowspan </title>
		<style>
			table{
			height:200px;
			width:300px;
			border:1px solid blue;
			}
			th{
			color:darkblue;
			border:2px solid black;
			}
			td{
			border:1px solid black;
			text-align:center;
			padding:25px;
			}
			table{
			border-collapse:collapse;
			}
		</style>
	</head>
	<body>
		<table>
			<thead>
				<tr>
					<th> ID </th>
					<th> Name </th>
					<th colspan="2"> Telephone </th>
				</tr>
			</thead>
			<tbody>
				<tr>
					<td> 18102041 </td>
					<td> abu ubaida </td>
					<td> 02189260616</td>
					<td rowspan="2"> 01923061618</td>
				</tr>
				<tr>
					<td> 18102042 </td>
					<td> ali banat </td>
					<td>0183458291 </td>
				</tr>
				<tr>
					<td>18102043 </td>
					<td> hamza ali </td>
					<td> 01924060516</td>
					<td> 01730462242</td>
				</tr>
			</tbody>
		</table>
	</body>
</html>
```
<image src="./images/rowspancolspan.png"/>

