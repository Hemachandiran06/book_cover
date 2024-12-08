# Ex.06 Book Front Cover Page Design
# Date:07-11-2024
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
book.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Book Cover</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            font-family: Arial, sans-serif;
            
        }
        .cover {
            width: 400px;
            height: 600px;
            border: 2px solid #000;
            background-color: #fff;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            background-image: url(WhatsApp\ Image\ 2024-10-17\ at\ 14.07.59_028a1064.jpg);
        }
        .title {
            font-size: 36px;
            font-weight: bold;
            margin-bottom: 20px;
            color: #fff;
        }
        .subtitle {
            font-size: 24px;
            margin-bottom: 40px;
            color: wheat;
        }
        .author {
            font-size: 18px;
            font-style: italic;
            color: #333;
        }
        .bottom-text {
            margin-top: auto;
            font-size: 14px;
            color: burlywood     }
    </style>
</head>
<body>
    <div class="cover">
        <div class="title"> THE TEMPEST</div>
        <div class="bottom-text">published by ARIHANT BOOKS</div>
    </div>
</body>
</html>
```
# OUTPUT
![alt text](<book/Screenshot (29).png>)

# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
