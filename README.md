# Ex04 Places Around Me
## Date: 11/12/2025
## Ref.No:25016064

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
map.html
~~~
map.html

<html>
<head>
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="blue"><b>KRISHNAGIRI</b></font>
</h1>
<h3 align="center">
<font color="orange"><b>G SRI SAI SARAN(25016064)</b></font>
</h3>
<center>
<img src="map.png" usemap="#image-map">
<map name="image-map">
    <img src="map.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="Govt Medical college" title="Govt Medical college" href="college.html" coords="823,149,699,114" shape="rect">
    <area target="" alt="Pikkanapalli falls" title="Pikkanapalli falls" href="falls.html" coords="467,194,92" shape="circle">
    <area target="" alt="KRP dam" title="KRP dam" href="dam.html" coords="868,517,97" shape="circle">
    <area target="" alt="Perumal temple" title="Perumal temple" href="temple.html" coords="518,506,405,555" shape="rect">
    <area target="" alt="Krishnagiri Fort" title="Krishnagiri Fort" href="fort.html" coords="317,398,100" shape="circle">
</map>
</center>
</body>
</html>
~~~
dam,html
~~~
dam.html
<html>
    <head>
        <title>
            Krp Dam
        </title>
    </head>
    <body>
        <h1>KRP DAM
        
        </h1>
        <h3>Krishnagiri

        </h3>
        <p>
            The Krishnagiri Reservoir Project (KRP) Dam, built across the Thenpennai (South Pennar) River near Dhuduganahalli in Krishnagiri district, Tamil Nadu, is a major irrigation and water-supply structure completed in 1957 during the Kamaraj era. Stretching nearly one kilometre in length, the dam was designed to store over 68 million cubic metres of water, which supports the irrigation of thousands of acres of farmland in and around Krishnagiri and also provides drinking water to nearby towns and villages. With its spillway gates, scenic reservoir, and the popular KRP Dam Park adjoining it, the dam serves both practical and recreational purposes, making it an essential landmark for the region’s agriculture, water management, and tourism.
        </p>
    </body>
</html>
~~~
temple.html
~~~
temple.html
<html>
    <head>
        <title>
            perumal temple
        </title>
    </head>
    <body>
        <h1>PERUMAL TEMPLE

        </h1>
        <h3>krishnagiri

        </h3>
        <p>
            The Krishnagiri Perumal Temple, also known as the Kalinga Narthana Perumal Temple, is a well-known and ancient Hindu temple dedicated to Lord Vishnu, located near the Krishnagiri Fort and close to the town’s central area. The temple is admired for its serene atmosphere, traditional Dravidian architectural style, and beautifully carved mandapams. The main deity, Lord Perumal, is worshipped in a graceful standing posture, and devotees believe the temple brings peace, prosperity, and protection. Situated on a small hillock, the temple offers a calm spiritual setting with views of the surrounding town and hills, making it both a devotional and scenic destination for visitors and pilgrims throughout the year.
        </p>
    </body>
</html>
~~~

## OUTPUT

<img width="1917" height="968" alt="image" src="https://github.com/user-attachments/assets/6ae73767-f4f9-4bc8-bb60-965c49d337c9" />

<img width="1905" height="557" alt="image" src="https://github.com/user-attachments/assets/17da6e0b-97a3-4841-a8b3-eaadfe4e7bd6" />

<img width="1919" height="583" alt="image" src="https://github.com/user-attachments/assets/19993fc9-6307-411d-be10-f05b2b96dd1c" />










## RESULT
The program for implementing image maps using HTML is executed successfully.
