# Ex.08 Design of Interactive Image Gallery
## Date:

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
    <!DOCTYPE html>
    <html>
    <head>
        <title>My Summer Stories</title>
        <style>
            body {
                font-family: 'Arial', sans-serif;
                background: linear-gradient(to bottom, #FFFAE3, #FFD59E); 
                margin: 0;
                padding: 0;
                text-align: center;
                position: relative;
            }
    
            h1 {
                color: #FF7F50;
                margin-top: 20px;
                font-size: 2.5rem;
            }
    
            .profile-section {
                position: absolute;
                top: 20px;
                right: 20px;
                text-align: center;
            }
    
            .profile-pic {
                width: 60px;
                height: 60px;
                border-radius: 50%;
                border: 3px solid #fffacd;
                object-fit: cover;
            }
    
            .profile-name {
                font-size: 0.9rem;
                color: #D2691E;
                margin-top: -2.5px;  
            }
    
            .gallery {
                display: flex;
                flex-wrap: wrap;
                justify-content: center;
                gap: 20px;
                padding: 20px;
                margin-top: 20px;
            }
    
            .gallery img {
                width: 220px;
                height: 180px;
                object-fit: cover;
                border: 5px solid #fffacd;
                border-radius: 10px;
                box-shadow: 2px 2px 10px rgba(0,0,0,0.1);
            }
    
            .footer-quote {
                margin-top: 30px;
                font-size: 2rem;
                color: #D2691E;
                font-style: italic;
                padding: 15px;
            }
        </style>
    </head>
    <body>
        <div class="profile-section">
            <img src="\static\pfp.jpg" alt="My Profile Picture" class="profile-pic">
            <div class="profile-name">Hari Priya's Summer Memories</div>
        </div>
    
        <h1>My Summer Gallery</h1>
    
        <div class="gallery">
            <img src="\static\summer1.jpg" alt="Summer Pic 1">
            <img src="\static\summer2.jpg" alt="Summer Pic 2">
            <img src="\static\summer3.jpg" alt="Summer Pic 3">
            <img src="\static\summer4.jpg" alt="Summer Pic 4">
            <img src="\static\summer5.jpg" alt="Summer Pic 5">
            <img src="\static\summer6.jpg" alt="Summer Pic 6">
            <img src="\static\summer7.jpg" alt="Summer Pic 7">
            <img src="\static\summer8.jpg" alt="Summer Pic 8">
            <img src="\static\summer9.jpg" alt="Summer Pic 9">
            <img src="\static\summer10.jpg" alt="Summer Pic 10">
        </div>
    
        <div class="footer-quote">
            "Sun's Out! Fun's Out!"
        </div>
    </body>
    </html>
  
## OUTPUT:
![Screenshot 2025-05-03 185807](https://github.com/user-attachments/assets/02561f0a-c06b-45b8-b916-9d3c3bec758a)

## RESULT:
The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
