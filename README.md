# Ex04 Places Around Me
## Date: 

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
...
<html>
    <head>
        <title>MY CITY</title>        
    </head>
    <body>
        <h1 align="center">
          <font color="green"><b>KALLAKURICHI</b></font>  
        </h1>
        <h3 align="center">
            <font color="green"><b>DIVAKARAN L (24901311)</b></font>
        </h3>
        <center>
            <img src="c:\Users\admin\Pictures\mycity.png" usemap="#mycity" height="650" width="1450">
            <map name ="mycity">
            <area shape="rect" coords="50,50,100,100" href="home.html" title="MY HOME TOWN">
            <area shape="rect" coords="50,50,100,100" href="location1.html" alt="Gomukhi Dam">
            <area shape="circle" coords="200,150,30" href="location2.html" alt="Kallakurichi Collectorate">
            <area shape="circle" coords="300,300,350,350,400,300" href="location3.html" alt="Kachirayapalayam">
            <area shape="rect" coords="450,100,500,150" href="location4.html" alt="Kalvarayan Hills">
            </map>
        </center>
    </body>
</html>

home.html
<html>
<head>
<title>My Home Town</title>
</head>
<body >
<h1 align="center">
<font color="red"><b>KALLAKURICHI</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>THE HOME TOWN</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
    Kallakurichi is a prominent town in the southern Indian state of Tamil Nadu, known for its rich cultural heritage, 
    agriculture, and rapid development. It serves as the administrative headquarters of the Kallakurichi district, 
    which was carved out in 2019 to streamline governance. The town is often referred to as the "Sugarcane City" due to its
    extensive sugarcane farming, supported by its fertile soil and favorable climate. Agriculture is the backbone of the region,
    with paddy, maize, and cotton also being widely cultivated. Kallakurichi boasts a mix of urban and rural lifestyles, 
    with well-connected transport networks and a growing number of educational institutions. The town is also gaining recognition 
    for its efforts in promoting industries and small-scale enterprises, contributing to its economic growth. With its scenic landscapes, 
    historical temples, and bustling marketplaces, Kallakurichi represents a blend of tradition and modernity.
</p>
</body>
</html>

location1.html
<html>
<head>
<title>TEMPLE</title>
</head>
<body bgcolor="blue">
<h1 align="center">
<font color="yellow"><b>GUMUKHI DAM</b></font>
</h1>
<hr size="3" color="yellow">
<p align="justify">
<font face="Georgia" size="5">
    The Gomukhi Damthe Gomukhinadhi Reservoir, is a significant man-made lake situated in the Kalrayan Hills near Kallakurichi in Tamil Nadu, India. 
    During the monsoon season, the reservoir spans approximately 10,800 acres, with a maximum storage height of 46 feet. 
    This reservoir serves as a crucial water source for 47 villages in the region, including Vadakkanandal, Mathur, Mannmalai,
    Madhavacheri, Palrampattu, Karadichithur, and Thevadipattu. It supports local agriculture, particularly the cultivation of water-intensive crops 
    like rice and sugarcane, which have been farmed by generations of local farmers. 
    The dam is located in the Kalrayan Hills, a part of the Eastern Ghats, offering picturesque landscapes and a serene environment. 
    It is a popular destination for travelers seeking natural beauty and tranquility. 
    For those interested in visiting, the Gomukhi Dam is accessible from Kallakurichi, which is well-connected by road. 
    The area provides opportunities for sightseeing and experiencing the natural splendor of the Kalrayan Hills.
</p>
</body>
</html>

location2.html
<html>
<head>
<title>ADMINISTRATIVE HEADQUARTERS</title>
</head>
<body bgcolor="cyan">
<h1 align="center">
<font color="BLACK"><b>KALLAKURICHI Collectorate</b></font>
</h1>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
    The Kallakurichi Collectorate serves as the administrative headquarters for Kallakurichi District in Tamil Nadu, India.
    Established on November 26, 2019, when the district was officially inaugurated, the Collectorate plays a pivotal role in district administration.
    The District Collector, an Indian Administrative Service (IAS) officer, leads the Collectorate, overseeing law and order,
     planning and development, and general administration. Supporting the Collector are the District Revenue Officer (DRO) and 
     Deputy Collectors, who manage revenue administration, civil supplies, land matters, and other essential functions. 
</body>
</html>

location3.html
<html>
<head>
<title>VILLAGE</title>
</head>
<body bgcolor="green">
<h1 align="center">
<font color="red"><b>Kachirayapalayam</b></font>
</h1>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
    Kachirayapalayam is a village situated in the Kallakurichi district of Tamil Nadu, India.
    It lies approximately 12 kilometers from the district headquarters, Kallakurichi, 
    and about 242 kilometers from the state capital, Chennai.
</p>
</body>
</html>

location4.html
<html>
<head>
<title>HILLS</title>
</head>
<body bgcolor="black">
<h1 align="center">
<font color="white"><b>KALVARAYAN HILLS</b></font>
</h1>
<hr size="3" color="white">
<p align="justify">
<font face="Georgia" size="5" color="white">
    The Kalvarayan Hills, part of the Eastern Ghats in Tamil Nadu, India, 
    span approximately 1,095 square kilometers with elevations ranging from 2,000 to 3,000 feet. 
    They act as a natural divide between the Kaveri and Palar river basins.
    The hills are divided into two sections: the Chinna (Little) Kalrayans in the north,
     averaging 2,700 feet, and the Periya (Big) Kalrayans in the south, averaging 4,000 feet. 
     The terrain supports diverse vegetation, including scrub jungles up to 400 meters, deciduous 
     forests above 800 meters, and high-altitude stunted evergreen forests known as 'sholas' on isolated plateaus.
</p>
</body>
</html>
...

## OUTPUT

![alt text](<Screenshot 2024-12-23 005932-1.png>)
![alt text](<Screenshot 2024-12-23 010114-1.png>)
![alt text](<Screenshot 2024-12-23 010151-1.png>)
![alt text](<Screenshot 2024-12-23 010219-1.png>)
![alt text](<Screenshot 2024-12-23 010257-1.png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
