# Ex.05 Design a Website for Server Side Processing
## Date:

## AIM:
 To design a website to calculate the power of a lamp filament in an incandescent bulb in the server side. 


## FORMULA:
P = I<sup>2</sup>R
<br> P --> Power (in watts)
<br> I --> Intensity
<br> R --> Resistance

## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Create python programs for views and urls to perform server side processing.

### Step 5:
Create a HTML file to implement form based input and output.

### Step 6:
Publish the website in the given URL.

## PROGRAM :
```
<html>
    <head>
        <title>BMI_Calculator</title>
        <style>
            body {
                background-color:cyan;
                font-family: Arial;
                display: flex;
                justify-content: center;
                align-content: center;
                height: 100vh;
            }
            .bmibox {
                background-color: purple;
                border: 2px inset red;
                padding: 30px;
                text-align: center;
                height: 280px;
                width: 300px;
                display: block;
            }
            input[type="text"] {
                width: 80%;
                padding: 8px;
                margin: 10pypx;
                border: 2px solid black;
                background-color: purple;
            }
            #subitha{
                background-color: purple;

            }
            .give{
                background-color:white;
            }
<html>
    <head>
        <title>BMI_Calculator</title>
        <style>
            body {
                background-color: white;
                font-family: Arial;
                display: flex;
                justify-content: center;
                align-content: center;
                height: 100vh;
            }
            .bmibox {
                background-color: purple;
                border: 2px inset red;
                padding: 30px;
                text-align: center;
                height: 280px;
                width: 300px;
                display: block;
            }
            input[type="text"] {
                width: 80%;
                padding: 8px;
                margin: 10pypx;
                border: 2px solid black;
                background-color: plum;
            }
            #subitha{
                background-color: purple;

            }
            .give{

             background-color: purple;   
            }
        </style>
    </head>

    <body>
        
        <br>
        <div class="bmibox">
            <h2 textalign="center">BMI CALCULATOR - <br>SUBITHA(25014966)</h2>
            <form method="POST">
            {%csrf_token %}
            <div class="formelt">
            Height: <input type="text" name="height" value="{{height}}" placeholder="Enter height in m">

            <br>
            <br>
            </div>
            <div class="formelt give">
            Weight: <input type="text" name="weight" value="{{weight}}" placeholder="Enter weight in kg">
            <br>
            <br>
            </div>
            <div class="formelt give">
            <input  type="submit" value="Calculate">
            <br>
            <br>
            </div>
            <div class="formelt" id="subitha">
            BMI: <input type="text" name="BMI" value="{{BMI}}">
            <br>
            </div>
            </form>
        </div>
    </body>
</html>



```


## SERVER SIDE PROCESSING:
![alt text](<subi/mathapp/templates/mathapp/Screenshot (18).png>)
## HOMEPAGE:
![alt text](<subi/mathapp/templates/mathapp/Screenshot (17).png>)
## RESULT:
The program for performing server side processing is completed successfully.
