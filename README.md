# Ex.06 Book Front Cover Page Design
## Date:12-04-24

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
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <style type="text/css">
      .bookcover {
        width: 400px;
        height: 640px;
        color: rgb(240, 239, 220);
        margin-left: auto;
        margin-right: auto;
        padding: 20px;
        font-family:Georgia, Times, 'Times New Roman', serif;
        background-image: url(tech.jpg);
        background-size: cover;
      }
      .insight {
        color: white;
      }
      .hr {
        width: 100px;
      }
      .h1 {
        font-size: medium;
        font-family: Georgia, Times, 'Times New Roman', serif;
        color: yellow;
        text-align: center;
        position: relative;
        top: 30px;
      }
      .h3 {
        font-size: larger;
        font-family: Georgia, Times, 'Times New Roman', serif;
        color: rgb(250, 250, 129);
        text-align: center;
        position: relative;
        top: 10px;
      }
      .p {
        font-size: medium;
        font-family: Georgia, Times, 'Times New Roman', serif;
        position: relative;
        top: 60px;
      }
      .edition {
        font-size: large;
        font-family: Georgia, Times, 'Times New Roman', serif;
        color: yellow;
        top: 60px;
        position: relative;
      }
      .photo {
        position: relative;
        top: 100px;
        left: 270px;
        width: 100px;
        height: 70px;
        background-size: cover;
      }
      .hrstyle {
        position: relative;
        width: 400px;
        top: 170px;
      }
      .author {
        font-size: medium;
        font-family: Georgia, Times, 'Times New Roman', serif;
        display: inline;
        position: relative;
        color: whitesmoke;
        top: 165px;
      }
      .publisher {
        font-size: large;
        position: relative;
        top: 135px;
        left: 330px;
      }
    </style>
    <title>Book Front Cover Page</title>
  </head>
  <body>
    <div class="bookcover">
      <div class="insight">SEC INSIGHT</div>
      <div class="hr">
        <hr />
      </div>
      <div class="h1">
        <h1>THE FUTURE SCIENCE</h1>
        <br>
        <h3>"PIONEERING THE BOUNDLESS HORIZONS OF DISCOVERY"</h3>
      </div>
      <div class="p">
        <p>
          he future of science holds exciting possibilities, from advancements in technology like quantum computing and genetic engineering to discoveries in fields like space exploration and artificial intelligence. It's a realm of endless exploration and innovation.




          
        </p>
      </div>
      <div class="photo">
        <img src="COVER KK.jpg" width="135" height="150" alt="" />
      </div>
      <div class="hrstyle">
        <hr />
      </div>
      <div class="author">
        <p><b> KARTHICK KISHORE T </b></p>
      </div>
      <div class="publisher">
        <b> SEC </b>
      </div>
      <div class="edition">
        <b>EXTENDED EDITION</b>
      </div>
    </div>
  </body>
</html>
```

## OUTPUT:
![alt text](<Screenshot (72).png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
