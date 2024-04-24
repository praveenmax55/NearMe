# Ex04 Places Around Me
## Date: 24/04/2024

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE
```
Name : Praveen D
Reg.No : 212222240076
```
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8"/>
        <meta name="viewport" content="width=device=width, initial-scale=1.0"/>
        <title>Document</title>
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    </head>
    <script>
        function coordinate(event) {
            let x = event.clientX;
            let y = event.clientY;
            document.getElementById("X").value = x;
            document.getElementById("Y").value = y;
        }
    </script>
    <body>
        <IMG src="map1.png" width="600" height="230" usemap="#MapNew" onmousemove="coordinate(event)">
            <MAP name="MapNew">
                <AREA shape="rect" coords="240,123,100,30" href="https://apolloartsandsciencecollegechennai.ac.in/"
                Title="Apollo Arts and Science">
                <area shape="rect" coords="466,72,340,190" href="https://pmchri.ac.in/"
                Title="Panimalar Medical College Hospital & Research Institute">
                <area shape="rect" coords="333,117,490,220" href="https://www.asetsafety.ac.in/"
                title="Aset Administrative Office">
            </MAP> <br>
            X-coordinate <input type="text" id="X"><br>
            Y-coordinate <input type="text" id="Y">
    </body>
</html>
```


## OUTPUT

![WD 4](https://github.com/praveenmax55/NearMe/assets/113497509/78efaf3f-f969-48cb-b0c6-2a191ec1266a)

![WD 4 1](https://github.com/praveenmax55/NearMe/assets/113497509/56798b0d-13a5-4013-8f9f-033c22047ca6)

![WD 4 2](https://github.com/praveenmax55/NearMe/assets/113497509/33e1625a-d747-4245-aaac-7833f2b6dc25)

![WD 4 3](https://github.com/praveenmax55/NearMe/assets/113497509/ca4118ad-1b1f-4743-b1e9-6e5794f05ff3)



## RESULT
The program for implementing image maps using HTML is executed successfully.
