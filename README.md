# Ex.06 Book Front Cover Page Design
## Date:20.05.2025

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
```
<html>
<head>
<meta name="veiwport"
content="width=device-width,initial-sacale=1.0">
<style>
.bookpage{
width:400px;
height:600px;
color: white;
margin-left: auto;
margin-right: auto;
padding: 20px;
font-family: 'Franklin Gothic Medium','Arial Narrow',Arial,sans-serief;
background-image: url(bg.webp);
background-size: cover;
}

.insight{
color:rgb(224, 211, 213);
}

.hrstyle{
width: 100px;
}

.author{
display: inline;
position: relative;
color:violet;
top: 190px;
font-family: Georgia;
font-size: medium;
}


.booktitle{
font-family:'Courier New',Courier,manospace;
color:black;
font-size: larger;
text-align: center;
position: relative;
top: 30px;
}

.id{
width:400px;
position: relative;
top:180px;
}

.pub{
font-size:medium;
position: relative;
color:plum;
top:155px;
left:330px;
}

.ed{
color:yellowgreen;
font-size: medium;
font-family: Verdana;
position:relative;
top:85px;
}

.subtitle{
font-family:Tahoma;
font-size:large;
position: relative;
top: 40px;
}

</style>
<title>Book Cover Page</title>
</head>
<body>
<div class="bookpage">
<div class="insight">
  SAVEETHA ENGINEERING COLLEGE
</div>
<div class="booktitle">
<h1>THE SPACE</h1></div>
<div class="subtitle">
beyond quantum theory and relativity
</div>
<div class="id">
<hr style="color:orange;">
</div>
<div class="author">
<p><b>RAMYA S</b></p>
</div>
<div class="pub">
    CSE
</div>
<div class="ed">
<b>First Edition-Updated for 2025</b>
</div>
</div>
</body>
</html>

```

## OUTPUT:
![alt text](<Screenshot 2025-05-20 111016.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
