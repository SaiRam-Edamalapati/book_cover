# Ex.06 Book Front Cover Page Design
# Date:21-11-2024
# AIM:
To design a book front cover page using HTML and CSS.

# DESIGN STEPS:
## Step 1:
Create a Django Admin project.

## Step 2:
Create an app in the Django interface.

## Step 3:
Create a folder named 'static' in the app folder.

## Step 4:
Create a new HTML file in the static folder.

## Step 5:
Write the HTML code with relevant CSS properties.

## Step 6:
Choose the appropriate style and color scheme.

## Step 7:
Insert the images in their appropriate places.

## Step 8:
Publish the website in the LocalHost.

# PROGRAM:
```
<html>
    <head>
        <meta name="viewport" content="width=device=width, initial-scale=1.0">
        <style>

            .bookpage{
                width: 400px;
                height: 600px;
                color: black;
                margin-left: auto;
                margin-right: auto;
                padding: 20px;
                font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
                background-image: url(background.png.jpg);
                background-size: cover;
            }

            .insight{
                color: black;
            }

            .hrstyle{
                width: 100px;
            }

            .author{
                display: inline;
                position: relative;
                color: white;
                top: 230px;

                font-family: Georgia, 'Times New Roman', Times, serif;
                font-size: medium;
            }

            .booktitle{
                font-family: 'Courier New', Courier, monospace;
                font-size: larger;
                text-align: center;
                position: relative;
                top: 30px;
            }

            .id{
                width: 400px;
                position: relative;
                top: 100px;
            }

            .pub{
                font-size: medium;
                position: relative;
                top: 230px;
                left: 315px;
            }

            .ed{
                color: black;
                font-size: medium;
                font-family: Verdana, Geneva, Tahoma, sans-serif;
                position: relative;
                top: 150px;

            }

            .subtitle{
                font-family: Verdana, Geneva, Tahoma, sans-serif;
                font-size: large;
                position: relative;
                top: 40px;
            }

            .mypic{
                position: relative;
                top: 230px;
                left: 260px;
                width: 100px;
                height: 100px;
                background-size: cover;

            }
        </style>
        <title>BOOK COVER</title>
    </head>
    <body>
        <div class="bookpage">
            <div class="insight">SEC INSIGHT</div>
            <div class="hrstyle">
                <hr style="color: yellow;">
            </div>
            <div class="booktitle">
                <h1>Fundamentals Of Web Application Development</h1>
            </div>
            <div class="subtitle">
               web application framework
            </div>
            <div class="mypic">
                <img src="my image.jpg" width="130" height="145" alt="">
            </div>
            <div class="id">
                <hr style="color: orange;">
            </div>
            <div class="author">
                <p><b>Sai Ram E</b></p>
            </div>
            <div class="pub">
                sec
            </div>
            <div class="ed">
                <b>THIRD EDITION</b>
            </div>
        </div>
    </body>
</html>
```
# OUTPUT:
![alt text](<Screenshot 2024-12-07 235626-1.png>)
# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
