# Ex04 Places Around Me
## Date:28/09/2025

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
    <head>
        <title>My City</title>
        
    </head>
    <body>
        <h1 align=" center" >
     <font color="green"><b>CUDDALORE</b></font>
        </h1>
        <h3 align="center">
        <font color="blue"><b>Vishwa S<br> 25012636 </b></font>

        </h3>
        <center>
            <img src="map.png" usemap="Mycity"  height="610" width="1450">
             <map name="MyCity">
                <area shape ="rect" coords="700,250,850,400" href="map.html" title="My home city">
                
             <img src="map.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="Panruti" title="Panruti" href="panruti.html" coords="432,114,608,205" shape="rect">
    <area target="" alt="Nellikkuppam" title="Nellikkuppam" href="nellikkuppam.html" coords="1169,115,1218,109,1257,121,1280,137,1285,165,1277,194,1255,203,1235,208,1211,208,1184,199,1153,184,1113,164,1118,121,1121,108,1218,108,1155,171,1187,131,1219,109" shape="poly">
    <area target="" alt="Cuddalore" title="Cuddalore" href="cuddalore.html" coords="1769,266,47" shape="circle">
    <area target="" alt="kedilam" title="kedilam" href="kedilam river.html" coords="1201,272,1437,380" shape="rect">
    <area target="" alt="lake" title="lake" href="veeranam.html" coords="1644,160,97" shape="circle">
</map>
             </map>

        </center>

    </body>
</html>

cuddalore.html
<html>
    <head>
    </head>
    <Body bgcolor="greenery">
        <h1 align="center">
            <font color="red"><b>Cuddalore</b></font>

        </h1>
        <h3 align="center"> 
            <font color="blue"><b>Cuddalore-My Home City</b></font>

        </h3>
        <hr size="3" color="red">
        <p align="justify">
        <font face="Georgia" size="5">

Cuddalore, located on the Coromandel Coast in Tamil Nadu, India,
is a city rich in history and culture. Known as "Kuttal-ur," meaning
"junction town," it lies at the confluence of the Ponnaiyar and Gadilam rivers.
Once a significant port during the British era, Cuddalore is now a hub 
for heavy industries while retaining its traditional charm. The city is 
home to ancient temples, serene beaches, and vibrant festivals, offering a 
blend of heritage and modernity that captivates visitors.








        </font>
        </p>
    </Body>
    
       </html> 

kedilam river.html
<html>
    <head>
    </head>
    <Body bgcolor="yellow">
        <h1 align="center">
            <font color="red"><b>Kedilam</b></font>

        </h1>
        <h3 align="center"> 
            <font color="blue"><b>Kedilam-My District river</b></font>

        </h3>
        <hr size="3" color="red">
        <p align="justify">
        <font face="Georgia" size="5">

The Gadilam River (sometimes pronounced Kedilam) flows
through the Cuddalore and Viluppuram districts of Tamil Nadu. 
[1] It has a small water flow, drainage area and sand deposit and 
is generally flooded during the monsoon season and raises the water 
table and feed tanks on its basin.





        </font>
        </p>
    </Body>
    
       </html> 


nellikkuppam.html
<html>
    <head>
    </head>
    <Body bgcolor="cyan">
        <h1 align="center">
            <font color="red"><b>Nellikkuppam</b></font>

        </h1>
        <h3 align="center"> 
            <font color="blue"><b>Nellikkuppam-My Home Village</b></font>

        </h3>
        <hr size="3" color="red">
        <p align="justify">
        <font face="Georgia" size="5">

Nellikuppam is a quaint town in Tamil Nadu, India, celebrated for 
its rich cultural heritage and scenic beauty. Nestled amidst lush greenery, 
it offers serene backwaters and picturesque surroundings, making it a 
haven for nature enthusiasts. The town is also known for its proximity to 
notable tourist spots like Vadalur Sathyagnana Sabai, Pichavaram mangroves, 
and Chidambaram. With a harmonious blend of tradition and natural charm, 
Nellikuppam is a delightful destination for those seeking tranquility and 
cultural exploration.





        </font>
        </p>
    </Body>
    
       </html> 


panruti.html
<html>
    <head>
    </head>
    <Body bgcolor="pink">
        <h1 align="center">
            <font color="red"><b>Panruti</b></font>

        </h1>
        <h3 align="center"> 
            <font color="blue"><b>Panruti-My Home Area</b></font>

        </h3>
        <hr size="3" color="red">
        <p align="justify">
        <font face="Georgia" size="5">


Panruti is a vibrant town in the Cuddalore district of Tamil Nadu, 
India, renowned for its rich cultural heritage and historical significance. 
Nestled between Cuddalore and Neyveli, it is celebrated for its agricultural 
produce, particularly jackfruit and cashews, which are widely exported. 
The town offers a harmonious blend of tradition and modernity, with its serene 
temples, bustling markets, and a warm, welcoming community. Its strategic 
location and unique charm make Panruti a noteworthy destination in Tamil Nadu.




        </font>
        </p>
    </Body>
    
       </html> 

veeranam.html
<html>
    <head>
    </head>
    <Body bgcolor="orange">
        <h1 align="center">
            <font color="red"><b>Veeranam</b></font>

        </h1>
        <h3 align="center"> 
            <font color="blue"><b>Veeranam lake</b></font>

        </h3>
        <hr size="3" color="red">
        <p align="justify">
        <font face="Georgia" size="5">

Veeranam Lake, located in the Cuddalore district of Tamil Nadu,
is a historic reservoir built during the 10th century by the Chola dynasty.
Spanning approximately 16 kilometers, it serves as a vital source of 
irrigation and drinking water for the region. This majestic lake not only 
showcases the engineering brilliance of ancient times but also offers a 
serene and picturesque environment, making it a popular spot for visitors. 
Its significance as both a lifeline for millions and a symbol of human 
ingenuity continues to endure through the ages.





        </font>
        </p>
    </Body>
    
       </html> 
```

## OUTPUT

![alt text](<Screenshot (13).png>)
![alt text](<Screenshot (14).png>)
![alt text](<Screenshot (15).png>)
![alt text](<Screenshot (16).png>)
![alt text](<Screenshot (17).png>)
![alt text](<Screenshot (18).png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
