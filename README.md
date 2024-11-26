# Ex04 Places Around Me
## Date: 26/11/2024

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
map.html
<html>
<body>
<h1 align="center">
<font color="maroon"><b>VENKATAGIRIKOTA</b></font>
</h1>
<h3 align="center">
<font color="sky blue"><b>MOTTA KATTA MOUNIKA (24010589)</b></font>
</h3>
<img src="map.png" usemap="#image-map">
<map name="image-map">
    <area alt="PVR Store" title="PVR Store" href="PVR stores.html" coords="205,184,347,257" shape="rect">
    <area alt="Vkota Flower Market" title="Vkota Flower Market" href="vkota flower market.html" coords="275,277,480,328" shape="rect">
    <area alt="MK tiles" title="MK tiles" href="MK tiles.html" coords="400,655,547,726,676,616" shape="rect">
    <area alt="GMR Cricket Academy" title="GMR Cricket Academy" href="GMR Cricket Academy.html" coords="585,226,822,292" shape="rect">
    <area alt="Hotel Sidhananja Pure Veg" title="Hotel Sidhananja Pure Veg" href="Hotel Sidhananja Pure Veg.html" coords="1164,434,1364,531" shape="rect">
</map>
</body>
</html>
PVR stores.html
<!DOCTYPE html>
<html lang="en"> 
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PVR stores</title>

</head>
<body bgcolor="lavender">
    <h1 style="font-family: cursive; color: rgb(3, 43, 189);">PVR stores</h1>
    <h2 style="font-family: serif;">It is a store in vkota,Andhra pradesh.The products here have good quality.
        PVR stores provides you the best range of hair shampoo,
         sunflower oil, sugar balls, medicated soap, sugar candies & beauty soap with effective & timely delivery.
    </h2>
    
</body>
</html>
vkota flower market.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>vkota flower market</title>

</head>
<body bgcolor="pink">
    <h1 style="font-family: cursive; color: teal;">vkota flower market</h1>
    <h2 style="font-family: serif;">It is a flower market in vkota,Andhra Pradesh.It is famous for varities of flowers.We can see a lot of 
        varities of flowers compared to other states.It is a popular flower market in Andhra pradesh.
    </h2>
    
</body>
</html>
MK tiles.html
<!DOCTYPE html>
<html lang="en"> 
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MK tiles</title>

</head>
<body bgcolor="beige">
    <h1 style="font-family: cursive; color: rgb(171, 0, 97);">MK tiles</h1>
    <h2 style="font-family: serif;">MK tiles are 
    Manufacturer of an Ceiling Tiles, Roof Tile, Clay Tiles, Opal Stone,
     Red Bricks, Gypsum Tiles.


    </h2>
    
</body>
</html>
GMR Cricket Academy.html
<!DOCTYPE html>
<html lang="en"> 
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GMR Cricket Academy</title>

</head>
<body bgcolor="violet">
    <h1 style="font-family: cursive; color: rgb(189, 3, 115);">GMR Cricket Academy</h1>
    <h2 style="font-family: serif;">"A Perfect Recreational Space where in people get to play various
        sports such as Box Cricket, Volley Ball, Snooker Table, Table Tennis with the ease of access 
        to Cafeteria. We would also provide the desired space to conduct Tournaments for the sports 
        and games mentioned above. Note : To mention , There is a dedicated space with Nets and Special
        Pitch allocated for Professional Cricket where a Certified Coach will be associated in training 
        the individual."
 
    </h2>
    
</body>
</html>
Hotel Sidhananja Pure Veg.html
<!DOCTYPE html>
<html lang="en"> 
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hotel Sidhananja Pure Veg</title>

</head>
<body bgcolor="green">
    <h1 style="font-family: cursive; color: rgb(105, 3, 189);">Hotel Sidhananja Pure Veg</h1>
    <h2 style="font-family: serif;"> Fine Dine Hotel And Banquet Hall. Authentic Taste Of Pure Veg. Welcome to Hotel Sidhananja Pure Veg, where a dedication to serving delicious vegetarian meals coexists with culinary brilliance.
    </h2>
    
</body>
</html>
```
## OUTPUT
![alt text](<Screenshot 2024-11-26 112922.png>)
![alt text](<Screenshot 2024-11-26 112933.png>)
![alt text](<Screenshot 2024-11-26 112944.png>)
![alt text](<Screenshot 2024-11-26 112956.png>)
![alt text](<Screenshot 2024-11-26 113007.png>)
![alt text](<Screenshot 2024-11-26 113025.png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
