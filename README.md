# Ex04 Places Around Me
## Date: 31-03-20204

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
<html>
<head>
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="green"><b>PALLAVADA</b><font>
</h1>
<h2 align="center">
<font color="red"><b> DHANUSHA K(212223040034)</b><font>
</h2>
<center>

<img src="map (2).png" usemap="#MyCity" height="610" width="1450">
<map name="MyCity">
<area shape="circle" coords="950,120,1100,140" href="home.html" title="My Home Town">
<area shape="rect" coords="700,250,850,400" href="road.html" title="pallavada village Road">
<area shape="circle" coords="570,230,45" href="temple.html" title="Dharma-raja-swami Temple">
<area shape="circle" coords="640,200,30" href="ground.html" title="pallavada cricket ground">
<area shape="circle" coords="1120,360,25" href="lake.html" title="pallavada lake">
</map>
</center>
</body>
</html>
```
## Home.html
```
<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="pink">
<h1 align="center">
<font color="red"><b>PALLAVADA</b><font>
</h1>
<h2 align="center">
<font color="blue"><b> pallavada - My Home Town</b><font>
</h2>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5" color="green">
Pallavada village is famous for festivals and celebrations.The village is home to the Dharamaraja Swami temple. 
The 11-day annual festival of the temple attracts around 25,000 people. The village celebrates Vinayaka Chaturthi festival with music and kuttu dance. Another major festival is Pongal. Girls sing folk songs called bathukamma. 
The economy of the village is driven by agricultural activities.</font>
</p>
</body>
</html>
```
## Road.html
```
<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="cyan">
<h1 align="center">
<font color="purple"><b>PALLAVADA</b></font>
</h1>
<h2 align="center">
<font color="violet"><b> pallavada village road</b><font>
</h2>
<hr size="3" color="purple">
<p align="justify">
<font face="Georgia" size="5" color="brown">
The village is connected to near by towns by bus. The Tamil Nadu government runs one bus services reaching this village. The Andhra Pradesh Government also runs one bus connecting the village to Uthukottai and Sullurupattai.</font>
</p>
</body>
</html>
```
## Temple.html
```
<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="sky blue">
<h1 align="center">
<font color="blue"><b>PALLAVADA</b></font>
</h1>
<h2 align="center">
<font color="orange"><b>Dharma-raja-swami temple</b><font>
</h2>
<hr size="3" color="blue">
<p align="justify">
<font face="Georgia" size="5" color="yellow">
11-day festival for lord Dharma-raja-swami temple.2-day festival for lord Venkateswara temple which happens every year in the month of June.Vinayaka Chaturthi with kuttu dance and some other activities.
Pongal: Girls together and enjoyed in the name of 'gobbi'. Men together and enjoyed in the name of 'kolatam'.Karthika deepam is celebrated in lord Siva temple.</p>
</body>
</html>
```
## Ground.html
```
<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="yellow">
<h1 align="center">
<font color="green"><b>PALLAVADA</b></font>
</h1>
<h2 align="center">
<font color="red"><b>pallavada cricket ground</b><font>
</h2>
<hr size="3" color="green">
<p align="justify">
<font face="Georgia" size="5" color="blue">
The village cricket ground is like the heart of a small community. It's where friends and families gather to enjoy the sport, cheer on the local team, and create lasting memories. The sounds of the bat hitting the ball, the cheers from the spectators, and the smell of freshly cut grass make the village cricket ground a special place. It's not just about the game. it's about coming together as a community.</font>
</p>
</body>
</html>
```
## Lake.html
```
<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="gray">
<h1 align="center">
<font color="blue"><b>PALLAVADA</b></font>
</h1>
<h2 align="center">
<font color="orange"><b>Pallavada Lake</b><font>
</h2>
<hr size="3" color="blue">
<p align="justify">
<font face="Georgia" size="5" color="yellow">
The Pallavada village lake is a serene and picturesque spot in the heart of the village. It's a place where people gather to enjoy the beauty of nature, relax by the water, and sometimes even engage in fishing or boating activities. The lake serves as a peaceful retreat for the villagers, offering a sense of tranquility and connection to the natural world. Just like the village cricket ground, the Pallavada village lake plays a vital role in bringing the community together and fostering a sense of unity and belonging</font>
</p>
</body>
</html>
```
## OUTPUT
## Home.html
![Screenshot 2024-03-31 231526](https://github.com/Dhanusha17/NearMe/assets/151549957/540bd0f4-623d-487a-b7e3-f1bf1777a55b)

## Road.html
![Screenshot 2024-03-31 231707](https://github.com/Dhanusha17/NearMe/assets/151549957/c0ffc518-2da3-4ef8-82b2-ae5615d01da5)

## Temple.html
![Screenshot 2024-03-31 231553](https://github.com/Dhanusha17/NearMe/assets/151549957/92cc86fe-5ce9-44fc-8e23-a533fa900384)

## Ground.html
![Screenshot 2024-03-31 231646](https://github.com/Dhanusha17/NearMe/assets/151549957/55fbaa40-c706-4a30-8cf1-8d99910d50f8)

## Lake.html
![Screenshot 2024-03-31 231615](https://github.com/Dhanusha17/NearMe/assets/151549957/bc19e6fb-220f-4bb9-9af8-40ce358a4c08)



## RESULT
The program for implementing image maps using HTML is executed successfully.
