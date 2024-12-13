# Ex.08 Design of Interactive Image Gallery
## Date: 13.12.2024

## AIM:
To design a web application for an inteactive image gallery with minimum five images.

## DESIGN STEPS:

### Step 1:
Clone the github repository and create Django admin interface.

### Step 2:
Change settings.py file to allow request from all hosts.

### Step 3:
Use CSS for positioning and styling.

### Step 4:
Write JavaScript program for implementing interactivity.

### Step 5:
Validate the HTML and CSS code.

### Step 6:
Publish the website in the given URL.

## PROGRAM :
```
<html>
    <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Toothless</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Satisfy&family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto','sans-serif'; 

            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            background-color: #5e0606;
            color: #333;
        }

        h1 {
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;

            font-size: 3em;
            margin: 20px;
            color: #2115c29e;
            text-align: center;

        }
        h2 {
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;

            font-size: 3em;
            margin: 20px;
            color: #da2695;
            text-align: center;
        }

        .gallery {
            display: flex;
            flex-wrap: wrap;
            gap: 15px;
            max-width: 1200px;
            padding: 10px;
            justify-content: center;
        }

        .gallery-item {
            text-align: center;
            width: 200px;
            margin: 10px;
            border: 2px solid #3b0303;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            overflow: hidden;
            transition: transform 0.3s;
        }

        .gallery-item img {
            width: 200px;
            height: 200px;
            object-fit: cover; 
            border-bottom: 1px solid #450505;
        }

        .gallery-item p {
            font-family: 'Satisfy', cursive;
            font-size: 1.3em;
            color: #555;
            padding: 10px 0;
            margin: 0;
        }

        .gallery-item:hover {
            transform: scale(1.05);
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
        }
    </style>
</head>

<body>
    <h1>Image Gallery</h1>
    <h2>Anjali.k (24900073)</h2>
    
    <div class="gallery">
        <div class="gallery-item">
            <img src="lion.jpg" alt="Image 1">
        </div>
        <div class="gallery-item">
            <img src="giraffee.jpg" alt="Image 2">
        </div>
        <div class="gallery-item">
            <img src="tiger.jpg" alt="Image 3">
        </div>
        <div class="gallery-item">
            <img src="panda.jpg" alt="Image 4">
        </div>
        <div class="gallery-item">
            <img src="gorilla.jpg"alt="Image 5">
        </div>
        <div class="gallery-item">
            <img src="cheetah.jpg" alt="Image 6">
        </div>
        <div class="gallery-item">
            <img src="deer.jpg" alt="Image 7">
        </div>
        <div class="gallery-item">
            <img src="elephant.jpg" alt="Image 8">
        </div>
      </div>
   </body>
</html>
```

## OUTPUT:
![alt text](<Screenshot (24).png>)

## RESULT:
The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
