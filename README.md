# Ex.06 Book Front Cover Page Design
## Date: 12/05/25

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
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Man of Action - Book Cover</title>
  <style>
    body, html {
      height: 100%;
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      background-color: #111;
    }

    .book-cover {
      width: 300px;
      aspect-ratio: 2 / 3;
      background-image: url('cover.jpg'); 
      background-size: cover;
      background-position: center;
      box-shadow: 0 8px 16px rgba(0,0,0,0.6);
      position: relative;
      border: 4px solid #000;
      border-radius: 10px;
    }

    .overlay {
      position: absolute;
      bottom: 0;
      width: 100%;
      padding: 30px 15px;
      background: rgba(0, 0, 0, 0.6);
      text-align: center;
      color: #fff;
      border-bottom-left-radius: 10px;
      border-bottom-right-radius: 10px;
    }

    .title {
      font-size: 1.8rem;
      font-weight: bold;
    }

    .author {
      font-size: 1.1rem;
      font-style: italic;
      margin-top: 8px;
    }
  </style>
</head>
<body>

  <div class="book-cover">
    <div class="overlay">
      <div class="title">Man of Action</div>
      <div class="author">By Fan</div>
    </div>
  </div>

</body>
</html>
```


## OUTPUT:
![image](https://github.com/user-attachments/assets/9dac99cd-f918-4b62-9405-a238aded81e9)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
