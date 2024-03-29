# EX01 Developing a Simple Webserver
## Date:
29.03.24
## AIM:
To develop a simple webserver to serve html pages.

## DESIGN STEPS:
### Step 1: 
HTML content creation.

### Step 2:
Design of webserver workflow.

### Step 3:
Implementation using Python code.

### Step 4:
Serving the HTML pages.

### Step 5:
Testing the webserver.

## PROGRAM:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
    <style>
        .row1{
            background-color: gainsboro;
            display: flex;
            height: 50px;
            place-items: center;
        }
        i {
            color: #cc324b;
            font-size: 20px;
        }
        a {
            color: #cc324b;
            text-decoration: none;
            font-size: 20px;
            font-family: Arial;
            padding: 10px;
        }
        a:hover {
            color: white;
        }
        i:hover {
            color: white;
        }
    </style>
</head>
<body>
    <div class="row1">
        <div style="width: 40%;">
            <a href=""><i class="bi bi-twitter"></i></a>
            <a href=""><i class="bi bi-youtube"></i></a>
            <a href=""><i class="bi bi-facebook"></i></a>
            <a href=""><i class="bi bi-pinterest"></i></a>
        </div>
        <div style="width: 40%;">
            <a href="">Alumini</a><i class="bi bi-three-dots-vertical"></i>
            <a href="">Events</a><i class="bi bi-three-dots-vertical"></i>
            <a href="">Career</a><i class="bi bi-three-dots-vertical"></i>
            <a href="">Login</a><i class="bi bi-three-dots-vertical"></i>
            <a href="">SEC Portal</a>
        </div>
        <div style="width: 20%;">
            <div style="border: 3px solid; border-radius: 20px;">
                <i class="bi bi-search"></i>
                <input type="text" style="height: 40px; background-color: gainsboro; border: 0px" placeholder="Search"/>
            </div>
        </div>
    </div>
    <script>
        
    </script>
</body>
</html>
## OUTPUT:

![alt text](output.png)

## RESULT:
The program for implementing simple webserver is executed successfully.
