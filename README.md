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

### table accessible

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <mega charset="utf-8"></mega>
        <title>Accessible Table</title>
    </head>
    <body>
        <header>
            <h1>HTML Table</h1>
        </header>
        <main>
            <table>
                <caption>
                    Student Information
                </caption>
                <colgroup>
                <col span="2" style="background-color:blanchedalmond"/>
                </colgroup>
                <thead>
                    <tr>
                        <th scope="col">ID</th>
                        <th scope="col">Name</th>
                        <th scope="col">GPA</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>18102041</td>
                        <td>Ali Banat</td>
                        <td>4.92</td>
                    </tr>
                    <tr>
                        <td>18102042</td>
                        <td>Hamza Ali</td>
                        <td>4.64</td>
                    </tr>
                    <tr>
                        <td>18102043</td>
                        <td>abu ubaida</td>
                        <td>3.99</td>
                    </tr>
                </tbody>
            </table>
        </main>
    </body>
</html>
```

<image src="./images/tableaccessible.png"/>

### Form
---

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <title> Form </title>
    </head>
    <body>
        <h2>Registration Form </h2>

        <form>
            <div>
                <label for="fullname">Full Name: </label>
                <input type="text" name="fullname" id="fullname" required readonly>
            </div> </br>
            <div>
                <label for="email">Email: </label>
                <input type="text" name="email" id="email">
            </div> </br>
            <div>
                <label for="password">Password: </label>
                <input type="password" name="password" id="password">
            </div> </br>
            <div>
                <label for="dob">Date of Birth: </label>
                <input type="date" name="dob" id="dob">
            </div> </br>
            <div>
                <label for="photo">Upload your image </label>
                <input type="file" name="photo" id="photo">
            <div>
                <label for="gender">Gender </label>
                <input type="radio" name="gender" id="gender" value="male">Male
                <input type="radio" name="gender" id="gender" value="female">Female
            </div> </br>
            <div>
                <label for="relagion">Relagion </label>
                <input checked type="checkbox" name="r1" id="muslim" value="islam">Islam
                <input type="checkbox" name="r1" id="hindu" value="hindu">Hindu
                <input type="checkbox" name="r1" id="christan" value="christan">Christan
            </div> </br>
            <div>
                <label for="department">Department: </label>
                <select name="department">
                    <option value="CSE">CSE</option>
                    <option value="EEE">EEE</option>
                    <option value="BBA" selected>BBA</option>
                </select>
            </div></br>
            <div>
                <label for="message">Message</label></br>
                <textarea cols="30" rows="8"></textarea>
            </div>
            <div>
                <input type="submit" value="Registar" disabled>
                <input type="reset" value="Clear">
            </div>
        </form>
    </body>
</html>
```

<image src="./images/form.png"/>

### collect form data using third party API
```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <title>Form</title>
    </head>
    <body>
        <h2>Registration form</h2>
        <form action="https://formspree.io/f/meqyvwlv" method="post">
            <div>
                <label for="fullname">Full Name:</label>
                <input type="text" name="fullname" id="fullname">
            </div> </br>

            <div>
                <label for="email">Email: </label>
                <input type="text" name="email" id="email">
            </div> </br>

            <div>
                <label for="message">Your Message</label></br>
                <textarea cols="30" rows="6" name="message" id="message"></textarea>
            </div>
            <button type="submit">submit</button>
        </form>
    </body>
</html>
```

<image src="./images/formconnectweb.png"/>
<ol>
<li> goto formspee.io
<li> create a html form
<li> formspee page create a new form
<li> give a name and project or defaul project
<li> copy the api from the page paste in html page form action=""
</ol>

### Audio

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <title> audio tutorial </title>
    </head>
    <body>
        <h2>Here audio click to play</h2>
		<audio controls>
        <source src="C:\Users\osman\Downloads\v.mp3" type="audio/mpeg">
		</audio>
    </body>
</html>
```

if the audio and html file in the same page then
<source src="v.mp3" type="audio/mpeg"> location not needed.

<image src="./images/audio.png"/>

### video

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="utf-8">
        <title> Video </title>
    </head>
    <body>
        <h2>click to play</h2>
        <video height="400" width="400" controls>
            <source src="C:\Users\osman\Downloads\433281691_7213297752123411_9127949649223638948_n.mp4" type="video/mp4">
        </video>
    </body>
</html>
```

### a webpage simple project

```html
<!DOCTYPE html>
<html lang="en">
	<head>
		<meta charset="UTF-8">
		<style>
		h2{
		text-align:center;
		color:rgb(39,101,225);
		background-color:silver;
		}
		table{
		width:300px;
		height:200px;
		border:1px solid blue;
		background-color:;
		}
		td{
		border:1px solid rgb(196,32,111);
		text-align:center;
		color:#0E73C8;
		}
		th{
		border:2px solid #27B2D7;
		color:rgb(14,200,197);
		}
		.containar{
		display:flex;
		}
		</style>
	</head>
	<body>
		<p align="center"><image src="C:\Users\osman\Downloads\weblogo.png" width="100px" height="100px" align="center" alt="logo not found" vspace="-600px"/></p>
		<h2 id="header">HTML TUTORIAL</h2>
		<iframe src="https://tasman.42web.io/" width="560" height="315px"></iframe>
		<iframe width="560" height="315" src="https://www.youtube.com/embed/Fp__QlpOsWM?si=sxNBGrfmB9PajQcr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe><hr/>
		<p>HTML full meaning is hyper text markup language. this is a tutorial webpage. we learned and practicing heare. our topic is add picture videos audios
		text paragraph . and the other topic is adding hyper link table form text color background color align border vertical space horizontal space frame font
		family font change height width etc</p>
		<p> Now a days every institute are depanding on webpage. Every where html is using to create webpage and other programme. So, we must learn html to create a page. A page that is a very simple thing to search on internt just within a click we can move to webpage. we can easily get the right things by entering the domain or url.</p><hr/>
		<table style="float:left;">
			<thead>
				<tr>
					<th style="background-color:#F9EBEA;">Id</th>
					<th style="background-color:#FDEDEC;">Name</th>
					<th style="background-color:#F5EEF8;">GPA</th>
				</tr>
			</thead>
			<tbody>
				<tr>
					<td style="background-color:#F2D7D5;">18102041</td>
					<td style="background-color:#FADBD8;">ali banat</td>
					<td style="background-color:#EBDEF0;">4.93</td>
				</tr>
				<tr>
					<td style="background-color:#E6B0AA;">18102042</td>
					<td style="background-color:#F5B7B1;">abu ubaida</td>
					<td style="background-color:#D7BDE2;">4.57</td>
				</tr>
				<tr>
					<td style="background-color:#D98880;">18102043</td>
					<td style="background-color:#F1948A;">hamza ali</td>
					<td style="background-color:#BB8FCE;">3.54</td>
				</tr>
			</tbody>
		</table>
				<table style="float:left;">
			<thead>
				<tr>
					<th style="background-color:#EAF2F8;">Id</th>
					<th style="background-color:#EBF5FB;">Name</th>
					<th style="background-color:#E8F8F5;">GPA</th>
				</tr>
			</thead>
			<tbody>
				<tr>
					<td style="background-color:#E8DAEF;">18102044</td>
					<td style="background-color:#D4E6F1;">karam khan</td>
					<td style="background-color:#D6EAF8;">3.93</td>
				</tr>
				<tr>
					<td style="background-color:#D2B4DE;">18102045</td>
					<td style="background-color:#A9CCE3;">rafu ghani</td>
					<td style="background-color:#AED6F1;">3.57</td>
				</tr>
				<tr>
					<td style="background-color:#BB8FCE;">18102046</td>
					<td style="background-color:#7FB3D5;">kashem haque</td>
					<td style="background-color:#85C1E9;">4.54</td>
				</tr>
			</tbody>
		</table>
				<table style="float:left;">
			<thead>
				<tr>
					<th style="background-color:#E8F8F5;">Id</th>
					<th style="background-color:#E8F6F3;">Name</th>
					<th style="background-color:#E9F7EF;">GPA</th>
				</tr>
			</thead>
			<tbody>
				<tr>
					<td style="background-color:#D1F2EB;">18102047</td>
					<td style="background-color:#D0ECE7;">Afzal karim</td>
					<td style="background-color:#D4EFDF;">4.93</td>
				</tr>
				<tr>
					<td style="background-color:#A3E4D7;">18102048</td>
					<td style="background-color:#A2D9CE;">abu shams</td>
					<td style="background-color:#A9DFBF;">3.89</td>
				</tr>
				<tr>
					<td style="background-color:#76D7C4;">18102049</td>
					<td style="background-color:#73C6B6;">ruhit sinet</td>
					<td style="background-color:#7DCEA0;">2.54</td>
				</tr>
			</tbody>
		</table>
		<table>
			<thead>
				<tr>
					<th style="background-color:#F2F4F4;">Id</th>
					<th style="background-color:#EBEDEF;">Name</th>
					<th style="background-color:#EAECEE;">GPA</th>
				</tr>
			</thead>
			<tbody>
				<tr>
					<td style="background-color:#E5E8E8;">18102050</td>
					<td style="background-color:#D6DBDF;">abu siddiq</td>
					<td style="background-color:#D5D8DC;">3.93</td>
				</tr>
				<tr>
					<td style="background-color:#CCD1D1;">18102051</td>
					<td style="background-color:#AEB6BF;">zaynab kamil</td>
					<td style="background-color:#ABB2B9;">2.89</td>
				</tr>
				<tr>
					<td style="background-color:#B2BABB;">18102052</td>
					<td style="background-color:#85929E;">nazrul uddin</td>
					<td style="background-color:#808B96;">3.54</td>
				</tr>
			</tbody>
		</table><hr/>
		<form>
		<div>
			<label for="fullname">Full Name:</label>
			<input type="text" name="fullname" id="fullname">
		</div></br>
		<div>
			<label for="email">Email:</label>
			<input type="text" name="email" id="email">
		</div></br>
		<div>
			<label for="password">Password:</label>
			<input type="password" name="password" id="password">
		</div></br>
		<div>
			<label for="dob">Date of Birth:</label>
			<input type="date" name="dob" id="dob">
		</div></br>
		<div>
		<label for"photo">Upload Your Image</label>
		<input type="file" name="photo" id="photo">
		</div></br>
		<div>
			<label for="gender">Gender</label>
			<input type="radio" name="gender" id="gender" value="male">Male
			<input type="radio" name="gender" id="gender" value="female">Female
		</div></br>
		<div>
		<label for="relagion">Relagion</label>
		<input checked type="checkbox" name="c1" id="muslim" value="islam">islam
		<input type="checkbox" name="c1" id="hindu" value="hindu">hindu
		<input type="checkbox" name="c1" id="christan" value="christan">Christan
		</div></br>
		<div>
		<label for="department">Department</label>
		<select name="department">
			<option value="CSE">CSE</option>
			<option value="EEE" selected>EEE</option>
			<option value="BBA">BBA</option>
		</select>
		</div></br>
		<div>
		<label for="message">Message</label>
		<br/><textarea cols="30" rows="5"></textarea>
		</div>
		<div>
		<input type="submit" value="Register">
		<input type="reset" value="Clear">
		</div></br>
		</form><hr/>
		<video style="height:40%; width:40%;" controls>
			<source src="C:\Users\osman\Videos\Movavi Library\sayeed.mp4" type="video/mp4">
		</video>
		<audio controls>
			<source src="C:\Users\osman\Downloads\v.mp3" type="audio/mp3">
		</audio>
		<div>
			<ol>
			<li> <a href="https://www.youtube.com" target="blank">Youtube</a>
			<li> <a href="https://tasman.42web.io/" target="blank">My Webpage</a>
			<li> <a href="https://twitter.com" style="color:lightblue;" target="blank">Twitter</a>
			<li> <a href="" id="#top" style="color:#2E4053" target="blank">Go To Top</a>
			</ol>
		</div>
		
		<p> developed by <font color="#F8C471" style="font-family:fantasy; font-size:14px;">&copy; Osman Hossain</font></p>
		
		
	</body>
</html>
```
<image src="./images/webpage.gif"/>

### progress and svg

```html
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <title>Progress and Svg</title>
    </head>
    <body>
        <img src="C:\Users\osman\Downloads\boat.svg" height="200px"/>

        <ol>
            <li> HTML <progress max="100" min="0" value="70"></progress></li>
            <li> CSS <progress max="100" min="0" value="20"></progress></li>
            <li> JavaScript <progress max="100" min="0" value="40"></progress></li>
        </ol>
    </body>
</html>
```
<img src="./images/boat.png"/>

### details summary figure caption

```html
<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
        <title> Details and summary and figure</title>
        <style>
            details[open] > summary{
                background-color:lightblue;
            }
        </style>
    </head>
    <body>
        <details>
            <summary> Summary Here</summary>
            Bangladesh is a country. It's situated in asia. around 20billion people live here. cox's bazar sea beach and sundar ban mangrove is the most beautiful visited places here.
			Most of the peoples are muslim and some hindu and christan and other relagious people live here.
        </details>
        <figure>
            <img src="C:\Users\osman\Downloads\anton.jpeg" alt="turkey" style="height:300px;"/>
            <figcaption>
                fig 1: turkey touriest spot
            </figcaption>
    </body>
</html>
```
<img src="./images/figure.png"/>

### web accessibilities

### * Section

```html
<ul>
    <li><a href="#">Home</a></li>
    <li><a href="about">About</a></li>
    <li><a href="table">Table</a></li>
</ul>

<section id="about">
    <p> about </p>
    This is ... name. story...
</section>

<section id="table">
    <p> Table </p>
    <table>
        <tr>
            <th>id</th>
            <th>name</th>
        </tr>
    </table>
</section>
```
### * Tabindex and wrap label

```html

<form>
		<div>
			<label for="fullname">Full Name
			<input tabindex="2" type="text" name="fullname" id="fullname">
			</label>
		</div></br>
		<div>
			<label tabindex="1" for="email">Email:
			<input type="text" name="email" id="email">
			</label>
		</div></br>
		<div>
			<label for="password">Password:
			<input type="password" name="password" id="password">
			</label>
		</div></br>
</form>
```
### * color contrast check

https://webaim.org/resources/contrastchecker/ 

check color and get the recommended

### * publish the page to git hub

<ul>
<li>save index.html
<li>git push to github
<li>go to settings
<li>go to page
<li> select branch master
<ul>

Header-main-footer