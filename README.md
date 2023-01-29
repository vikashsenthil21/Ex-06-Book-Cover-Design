# Ex-06-Book-Cover-Design
AIM:

To design a static web site for a book cover page.

#DESIGN STEPS:

Step 1:

Clone the github repository and create a django admin interface.

Step 2:

Write HTML and CSS for designing book cover page and execute them.

Step 3:

Validate the HTML and CSS code.

Step 4:

Publish the website in the given URL.

PROGRAM

HTML CODE.
```
<!DOCTYPE html>
{% load static %}
<html lang="en">

<head>
   <meta charset="UTF-8">
   <meta http-equiv="X-UA-Compatible" content="IE=edge">
   <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <title>coverpage</title>
   <link rel="stylesheet" href="static/css/cover.css">
   <style>
   main{
   background-color: rgb(58, 54, 54);
   background-image: url('static/images/book.png');
   height: 1000px;
   width:800px;
   margin-left: 500px;
}
   </style>
</head>
<body>
   <main>
       <h4>EXPERT INSIGHT</h4>
       <hr id="start" color="orange">
       <h1>
           Responsive Web <br>
           Design with <br>
           HTML5 and CSS
       </h1>
       <p>Develop future-proof responsive websites <br>
       using the latest HTML5 and CSS techniques</p>

       
       <p id="edision">THIRD EDISION</p>
       <hr id="aj" color="orange">
       <img src="static/images/ben.png" alt="sdfgh">
       
          <p id="author">Ben Frain</p>
           <p id="packt"> <u> Packt> </u></p>
   
   
   </main>
  
</body>
</html>>
  ```
COVER-PAGE-DESIGNE:

![WhatsApp Image 2023-01-29 at 00 08 45](https://user-images.githubusercontent.com/119433834/215318835-99296c3c-ecd5-471a-9924-1e94d930c1f1.jpg)


RESULT:

The program for designing book cover page using HTML and CSS is executed successfully.
