# Ex04 Places Around Me
## Date: 02/04/2024

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
## mapp.html

<html>
    <head>
        <h2><center>Vellore</center></h2>
        <h3><center>Karthickraja-212221040073</center></h3>
    <hr>
    </head>
    <body bgcolor="brown">
        <img src="Screenshot 2024-04-02 204734.png" usemap="#image-map">

        <map name="image-map">
            <area target="" alt="sadjaker" title="sadjaker" href="sad.html" coords="299,286,403,335" shape="rect">
            <area target="" alt="bagayam" title="bagayam" href="baga.html" coords="522,349,623,349,622,405,520,408" shape="poly">
            <area target="" alt="ayllam" title="ayllam" href="ayl.html" coords="922,377,54" shape="circle">
            <area target="" alt="ratnagiri" title="ratnagiri" href="rat.html" coords="910,98,1026,173" shape="rect">
            <area target="" alt="kaakhidhapet" title="kaakhidhapet" href="pet.html" coords="612,176,66" shape="circle">
        </map>
</body>
</html>

## baga.html
<html>
    <head>
        <h2><center>Vellore</center></h2>
        <h3><center>Bagayam</center></h3>
    <hr>
    </head>
    <body bgcolor="light blue">
        <p>
            Bagayam is the village which consists majority pepole of MBC community.
            It is famous for the ponds in this village
            And then the pepole of the village
        </p>
    
</body>
</html>
## pet.html
<html>
    <head>
        <h2><center>Vellore</center></h2>
        <h3><center>Kaakhidhapet</center></h3>
    <hr>
    </head>
    <body bgcolor="red">
        <p>
            Kaakhidhapet is the village which consists majority pepole of BC community.
            It is famous for the temple in this village
            And then the pepole of the village
        </p>
    
</body>
</html>
## ayl.html
<html>
    <head>
        <h2><center>Vellore</center></h2>
        <h3><center>Ayllam</center></h3>
    <hr>
    </head>
    <body bgcolor="violet">
        <p>
            Ayllam is the village which consists majority pepole of BC/OC community.
            It is famous for the windmill in this village
            And then the pepole of the village
        </p>
    
</body>
</html>
## rat.html
<html>
    <head>
        <h2><center>Vellore</center></h2>
        <h3><center>ratnagiri</center></h3>
    <hr>
    </head>
    <body bgcolor="white">
        <p>
            Ratnagiri is the village which consists majority pepole of BC/OC community.
            It is famous for the natural scenario in this village
            And then the pepole of the village
        </p>
    
</body>
</html>
## sad.html
<html>
    <head>
        <h2><center>Vellore</center></h2>
        <h3><center>Sadjaker</center></h3>
    <hr>
    </head>
    <body bgcolor="green">
        <p>
            Sadjaker is the village which consists majority pepole of BC/OC community.
            It is famous for their foodstuffs in this village
            And then the pepole of the village
        </p>
    
</body>
</html>

```


## OUTPUT
![alt text](<raj/Screenshot 2024-04-02 210412.png>)
![alt text](<raj/Screenshot 2024-04-02 210510.png>)
![alt text](<raj/Screenshot 2024-04-02 210611.png>)
![alt text](<raj/Screenshot 2024-04-02 210620.png>)
![alt text](<raj/Screenshot 2024-04-02 210716.png>)
![alt text](<raj/Screenshot 2024-04-02 210724.png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
