# Ex.06 Book Front Cover Page Design
## Date:29/04/2025

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
  <meta charset="UTF-8">
  <title>Book Cover with Photo</title>
  <style>
    body {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
      background-color: #e0e0e0;
      font-family: 'Georgia', serif;
    }
    .book-cover {
      width: 300px;
      height: 450px;
      background: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), 
                  url('https://images.unsplash.com/photo-1507842217343-583bb7270b66?ixlib=rb-4.0.3&auto=format&fit=crop&w=800&q=60') 
                  center/cover no-repeat;
      color: white;
      padding: 20px;
      box-shadow: 0 10px 20px rgba(0,0,0,0.3);
      display: flex;
      flex-direction: column;
      justify-content: space-between;
      border-radius: 10px;
      text-align: center;
      overflow: hidden;
    }
    .book-cover img {
      width: 100%;
      height: 180px;
      object-fit: cover;
      border-radius: 10px 10px 0 0;
      margin-bottom: 10px;
    }
    .title {
      font-size: 24px;
      font-weight: bold;
      margin-top: 10px;
    }
    .subtitle {
      font-size: 16px;
      margin-top: 10px;
    }
    .author {
      font-size: 18px;
      margin-bottom: 20px;
      font-style: italic;
    }
  </style>
</head>
<body>
  <div class="book-cover">
    <img src="https://images.unsplash.com/photo-1512820790803-83ca734da794?ixlib=rb-4.0.3&auto=format&fit=crop&w=800&q=60" alt="Book Image">
    <div class="title">The Adventure</div>
    <div class="subtitle">A Journey Beyond</div>
    <div class="author">by Alex Carter</div>
  </div>
</body>
</html>

```

## OUTPUT:
![image](https://github.com/user-attachments/assets/e895ed78-2275-4630-8339-11e1326cdbf3)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
