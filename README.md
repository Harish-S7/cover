# Ex.06 Book Front Cover Page Design
## Date:10-12-2024

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
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Book Cover Page</title>
  <style>
    /* General Reset */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    /* Body background */
    body {
      background: linear-gradient(to bottom, #f0f8ff, #e6e6fa);
      font-family: 'Arial', sans-serif;
    }

    /* Main wrapper for book cover */
    .bookpage {
      width: 400px;
      height: 600px;
      margin: 50px auto;
      padding: 20px;
      border: 2px solid #333;
      border-radius: 10px;
      box-shadow: 5px 5px 15px rgba(0, 0, 0, 0.3);
      position: relative;
      background-color: white;
    }

    /* Insight header */
    .insight {
      color: black;
      font-size: 20px;
      font-weight: bold;
      text-align: center;
      margin-top: 10px;
    }

    /* Styled red horizontal line */
    .hrstyle {
      margin: 10px auto;
      width: 100px;
      border-top: 3px solid red;
      text-align: center;
    }

    /* Book title */
    .booktitle {
      font-family: 'Courier New', Courier, monospace;
      font-size: 26px;
      text-align: center;
      margin: 20px 0;
    }

    /* Subtitle */
    .subtitle {
      font-family: Tahoma;
      font-size: 16px;
      text-align: center;
      color: #555;
      margin: 10px 0;
    }

    /* Horizontal blue line */
    .id {
      margin: 20px auto;
      width: 80%;
      border-top: 2px solid blue;
    }

    /* Author image with background-image */
    .mypic {
      position: absolute;
      bottom: 100px;
      right: 20px;
      width: 100px;
      height: 100px;
      border-radius: 50%;
      background-image: url('photo.jpg');
      background-size: cover;
      background-position: center;
      border: 2px solid #555;
    }

    /* Author's name */
    .author {
      position: absolute;
      bottom: 40px;
      left: 30px;
      font-family: Georgia;
      font-size: 18px;
      color: black;
    }

    /* Publisher's name */
    .pub {
      font-size: 18px;
      position: absolute;
      bottom: 10px;
      right: 30px;
      color: #333;
    }

    /* Edition information */
    .ed {
      color: black;
      font-size: 16px;
      font-family: Verdana;
      position: absolute;
      bottom: 10px;
      left: 30px;
    }
  </style>
</head>

<body>
  <div class="bookpage">
    <!-- Insight Section -->
    <div class="insight">Learn C</div>
    <div class="hrstyle"></div>

    <!-- Book Title Section -->
    <div class="booktitle">
      <h1>Learning of C Programming</h1>
    </div>

    <!-- Subtitle Section -->
    <div class="subtitle">
      Learn C Program in 3 days
    </div>

    <!-- Decorative blue horizontal line -->
    <div class="id"></div>

    <!-- Author Image Section using CSS background-image -->
    <div class="mypic"></div>

    <!-- Author name Section -->
    <div class="author">
      <p><b>S Harish</b></p>
    </div>

    <!-- Publisher information -->
    <div class="pub">SEC</div>

    <!-- Edition Information Section -->
    <div class="ed">
      <b>Limited Edition</b>
    </div>
  </div>
</body>

</html>


## OUTPUT:
![image](https://github.com/user-attachments/assets/0af9679b-3b5d-4a09-9e11-9d6e2746c359)



## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
