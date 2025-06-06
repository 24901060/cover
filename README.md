# Ex.06 Book Front Cover Page Design
## Date:30-11-2024

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
  <title>Book Cover</title>
</head>
<body style="font-family: Arial, sans-serif; background-color:white; display: flex; justify-content: center; align-items: center; height: 100vh;">

  <div style="position: relative; width: 400px; height: 600px; border: 2px solid #ccc; border-radius: 10px; overflow: hidden; background-image:url(cover.png); background-size: cover; background-position: center;">

    <div style="position: absolute; top: 10px; left: 10px; color: white; font-size: 30px; font-weight: bold;">
      WEB DESIGNING <br> USING <br> HTML AND CSS
    </div>

    <div style="position: absolute; top: 150px; left: 10px; right: 10px; color: white; font-size: 10px; font-weight: lighter;">
      Learn the fundamentals of web designing with this beginner-friendly guide. Build stunning websites using HTML and CSS with practical examples and hands-on exercises.
    </div>

    <div style="position: absolute; bottom: 20px; right: 20px; text-align: right;">
      <img src="photo.jpg" alt="Author's Photo" style="width: 80px; height: 80px; ">
      <p style="color: white; margin-top: 10px; font-size: 1rem; font-weight: bold;">
        By Nanda Kishor S P <br> 24011485
      </p>
    </div>

  </div>

</body>
</html>

```


## OUTPUT:

![alt text](image.png)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
