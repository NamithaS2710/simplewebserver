# EX01 Developing a Simple Webserver
## Date:

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
```
HOME.HTML

<!DOCTYPE html>
<html lang="en">
<head>
    {% load static %}
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <style>
        i{
            color: #0b0b0b;
            font-size: 20px;
            padding: 10px;
        }
        i:hover{
            color: rgb(238, 9, 9);
        }
        a{
            text-decoration: none;
            color: #cc324b;
            font-size: 15px;
            font-family: arial;
            padding: 5px;
        }
    </style>
</head>
<body>
    <div>
        <div class="row" style="background-color: #a8a8a4;">
            <div class="col-1">
                <img src="{% static 'images/clglogo.png'%}" alt="" style="width:100px">
            </div>
            <div class="col-4 border" style="text-align: center; margin: auto;">
                <a href=""><i class="bi bi-twitter"></i></a>
                <a href=""><i class="bi bi-youtube"></i></a>
                <a href=""><i class="bi bi-facebook"></i></a>
                <a href=""><i class="bi bi-linkedin"></i></a>
                <a href=""><i class="bi bi-pinterest"></i></a>
                <a href=""><i class="bi bi-whatsapp"></i></a>
                <a href=""><i class="bi bi-instagram"></i></a>
            </div>
            <div class="col-4 border" style="margin: auto;">
                <a href="">Alumni</a><i class="bi bi-three-dots-vertical"></i>
                <a href="">Career</a><i class="bi bi-three-dots-vertical"></i>
                <a href="">Login</a><i class="bi bi-three-dots-vertical"></i>
                <a href="">SEC Portal</a>
            </div>
            <div class="col-3 border" style="margin: auto;">
                <div style="border: 2px solid; border-radius: 15px">
                    <i class="bi bi-search"></i>
                    <input type="text" placeholder="Search" 
                    style="background-color: #f3f3f3; border: opx; outline: none;">
                </div>
            </div>
        </div>
    </div>
    <!-- slider -->
    <div id="carouselExampleControls" class="carousel slide" data-ride="carousel">
        <div class="carousel-inner">
          <div class="carousel-item active">
            <img class="d-block w-100" src="{% static 'images/clg1.jpg' %}" alt="First slide">
          </div>
          <div class="carousel-item">
            <img class="d-block w-100" src="{% static 'images/clg2.jpg' %}" alt="Second slide">
          </div>
          <div class="carousel-item">
            <img class="d-block w-100" src="{% static 'images/clg3.jpg' %}" alt="Third slide">
          </div>
        </div>
        <a class="carousel-control-prev" href="#carouselExampleControls" role="button" data-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="sr-only">Previous</span>
        </a>
        <a class="carousel-control-next" href="#carouselExampleControls" role="button" data-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="sr-only">Next</span>
        </a>
      </div>

</body>
</html>
```


## OUTPUT:

![output1](https://github.com/NamithaS2710/simplewebserver/assets/133190822/f21dc719-05a7-49b1-8eb4-e41f074b9bb6)


## RESULT:
The program for implementing simple webserver is executed successfully.
