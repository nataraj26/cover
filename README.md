# Ex.06 Book Front Cover Page Design
## Date:

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
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <style>
      .bookpage {
        width: 400px;
        height: 600px;
        color: rgb(0, 234, 255);
        margin-left: auto;
        margin-right: auto;
        padding: 20px;
        font-family: "Franklin Gothic Medium", "Arial Narrow", Arial, sans-serif;
        background-image: url(https://i.ibb.co/9N4dHRp/Black-Beige-Minimalist-Photography-Portfolio-Cover-Page.png);
        background-size: cover;
      }

      .insight {
        color: rgb(42, 165, 65);
      }

      .hrstyle {
        width: 100px;
      }
      .author {
        display: inline;
        position: relative;
        color: rgb(0, 221, 255);
        top: 190px;

        font-family: Georgia;
        font-size: medium;
      }
      .booktitle {
        font-family: "Courier New", Courier, monospace;
        font-size: larger;
        text-align: center;
        position: relative;
        top: 30px;
      }
      .id {
        width: 400px;
        position: relative;
        top: 180px;
      }
      .pub {
        font-size: medium;
        position: relative;
        top: 155px;
        left: 330px;
      }
      .ed {
        color: blue;
        font-size: medium;
        font-family: Verdana;
        position: relative;
        top: 85px;
      }
      .subtitle {
        font-family: Tahoma;
        font-size: large;
        position: relative;
        top: 40px;
      }
      .mypic {
        position: relative;
        top: 135px;
        left: 260px;
        width: 100px;
        height: 100px;
        background-size: cover;
      }
    </style>
    <title>Book Cover Page</title>
  </head>
  <body>
    <div class="bookpage">
      <div class="insight">SEC INSIGHT</div>
      <div class="hrstyle">
        <hr style="color: red" />
      </div>
      <div class="booktitle">
        <h1>Fundamentals of Web Application Development</h1>
      </div>
      <div class="subtitle">HTML and CSS Combined with Django Architecture</div>
      <div class="mypic">
        <img
          src="WhatsApp Image 2024-01-01 at 11.02.33_85b9eb70.jpg"
          width="130"
          height="145"
          alt=""
        />
      </div>
      <div class="id">
        <hr style="color: rgb(208, 255, 0)" />
      </div>
      <div class="author">
        <p><b>NATARAJ KUMARAN S</b></p>
      </div>
      <div class="pub">SEC</div>
      <div class="ed">
        <b>Seventh Edition</b>
      </div>
    </div>
  </body>
</html>

```

## OUTPUT:
![Screenshot 2024-01-01 111615](https://github.com/nataraj26/cover/assets/147514615/33484901-7e57-4b95-82a4-bee8e0d1f25e)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
