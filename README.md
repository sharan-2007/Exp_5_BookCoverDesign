# Ex.05 Book Front Cover Page Design
## Date:19/12/2025

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
    <title>Book Cover</title>

    <style>
        body {
            margin: 0;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            background: #000000df;
            font-family: "Georgia", serif;
        }

        .book-cover {
            width: 360px;
            height: 560px;
            background-image: url("bg1.jpeg");
            background-size: cover;
            background-position: center;
            position: relative;
            padding: 30px;
            box-sizing: border-box;
            border: 2px solid white;
            box-shadow:
                0 0 15px rgba(255,255,255,0.6),
                0 0 30px rgba(255,255,255,0.4);
        }

        .overlay {
            position: absolute;
            inset: 0;
            background: rgba(255,255,255,0.15);

        }
        .company-badge {
             position: absolute;
             top: 15px;
             right: 15px;
             padding: 6px 12px;
             font-size: 11px;
             letter-spacing: 2px;
             color: white;

             border: 1px solid white;
             background: rgba(0, 0, 0, 0.6);

            z-index: 6;
            text-transform: uppercase;

  box-shadow: 0 0 8px rgba(255,255,255,0.6);
}


        .content {
            position: relative;
            z-index: 2;
            text-align: center;
        }
        .my-name {
            position: absolute;
            bottom: 15px;
            right: 20px;              
            font-size: 14px;
            letter-spacing: 2px;
            color: rgb(0, 0, 0);
            z-index: 5;
            text-shadow: 0 0 8px rgba(0, 0, 0, 0.9);
}


        .title {
            font-size: 32px;
            font-weight: bold;
            line-height: 1.2;
            margin-top: 10px;
        }

        .author {
            margin-top: 15px;
            font-size: 18px;
            font-style: italic;
        }
    </style>
</head>
<body>

    <div class="book-cover">
        <div class="overlay"></div>
       <div class="company-badge">SpYdeR BOOKS</div>

        <div class="content">
        </div>
        <div class="my-name">
             Dinesh Karthik TD <br> 25013939
            </div>
    </div>

</body>
</html>
```

## OUTPUT:

![alt text](image-1.png)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
