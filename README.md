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

```<html>
<head>
<title>My City - Thanjavur</title>
</head>
<body>
<h1 align="center">
<font color="violet"><b>Thanjavur</b></font>    
</h1>
<h3 align="center">
<font color="blue"><b>BALASUBRAMANIAM L (24901213) </b></font>    
</h3>
<center>
<img src="./MAP.png" usemap="#image-map" height="610" width="1450">

<map name="image-map">
    <area target="" alt="Thanjavur" title="Thanjavur" href="#thanjavur" coords="896,361,114" shape="circle">
    <area target="" alt="Kalyana Sundram School" title="Kalyana Sundram School" href="#kalyana_sundram" coords="161,490,414,646" shape="rect">
    <area target="" alt="Blake School" title="Blake School" href="#blake_school" coords="345,312,535,577" shape="rect">
    <area target="" alt="Temples" title="Temples" href="#temples" coords="1076,538,1037,667,806,661,795,546" shape="poly">
    <area target="" alt="Hostel" title="Hostel" href="#hostel" coords="1055,118,114" shape="circle">
</map>    
</center>

<!-- Thanjavur Section -->
<div id="thanjavur">
    <hr size="3" color="blue">
    <h2 align="center">
    <font color="violet"><b>Thanjavur</b></font>    
    </h2>
    <h3 align="center">
    <font color="blue"><b>My City</b></font>    
    </h3>
    <hr size="3" color="blue">
    <p align="justify">
    <font face="Georgia" size="S">
    Thanjavur is a city in the southern state of Tamil Nadu, India. It is known for its grand temples, including the Brihadeeswarar Temple, and rich cultural heritage. The city is famous for its art, architecture, and classical music. As of the latest census, the city has a population of approximately 2.3 lakh people.
    </p>
</div>

<!-- Kalyana Sundram HR Sec School Section -->
<div id="kalyana_sundram">
    <hr size="3" color="cyan">
    <h2 align="center">
    <font color="yellow"><b>Kalyana Sundram HR Sec School</b></font>    
    </h2>
    <h3 align="center">
    <font color="cyan"><b>Kalyana Sundram HR Sec School</b></font>    
    </h3>
    <img src="Screenshot from 2024-12-09 19-25-00.png" alt="">
    
    <hr size="3" color="cyan">
    <p align="justify">
    <font face="Georgia" size="S">
    School name: Kalyana Sundram Higher Secondary School.
    It is located in Thanjavur, Tamil Nadu. 
    The school offers grades 1 to 12 and is co-educational.
    This school focuses on academic excellence and character building.
    Contact number: 9875643787
    </p>
</div>

<!-- Blake HR Sec School Section -->
<div id="blake_school">
    <hr size="3" color="purple">
    <h2 align="center">
    <font color="yellow"><b>Blake HR Sec School</b></font>    
    </h2>
    <h3 align="center">
    <font color="purple"><b>Blake HR Sec School</b></font>    
    </h3>
    <img src="Screenshot from 2024-12-09 19-24-26.png" alt="">
    <hr size="3" color="purple">
    <p align="justify">
    <font face="Georgia" size="S">
    School name: Blake Higher Secondary School.
    Located in Thanjavur, Tamil Nadu, the school is known for its excellent academic performance.
    The school has grades from 1 to 12 and follows a co-educational format.
    The students of Blake School have consistently excelled in both academics and extracurricular activities.
    Contact number: 6789543765
    </p>
</div>

<!-- Temples in Thanjavur Section -->
<div id="temples">
    <hr size="3" color="red">
    <h2 align="center">
    <font color="green"><b>Temples</b></font>    
    </h2>
    <h3 align="center">
    <font color="red"><b>Temples in Thanjavur</b></font>    
    </h3>
    <img src="Screenshot from 2024-12-09 19-22-14.png" alt="">
    <hr size="3" color="red">
    <p align="justify">
    <font face="Georgia" size="S">
    Thanjavur is home to many historical temples, including the famous Brihadeeswarar Temple, which is a UNESCO World Heritage Site. The temples in Thanjavur showcase Tamil architecture and are known for their grandeur and historical significance.
    Contact number: 6789543765
    </p>
</div>

<!-- Hostel Section -->
<div id="hostel">
    <hr size="3" color="red">
    <h2 align="center">
    <font color="green"><b>Hostel</b></font>    
    </h2>
    <h3 align="center">
    <font color="red"><b>Hostel</b></font>    
    </h3>
    <hr size="3" color="red">
    <p align="justify">
    <font face="Georgia" size="S">
    The hostel in Thanjavur provides comfortable accommodations for students and visitors. It offers both vegetarian and non-vegetarian food options. The rooms are well-equipped with all basic amenities to ensure a comfortable stay.
    Contact number: 6789543765
    </p>
</div>

</body>
</html>

```


## OUTPUT

![alt text](<images/Screenshot from 2024-12-09 19-34-27.png>)

![alt text](<images/Screenshot from 2024-12-09 19-34-37.png>)

![alt text](<images/Screenshot from 2024-12-09 19-34-51.png>)

![alt text](<images/Screenshot from 2024-12-09 19-35-02.png>)


## RESULT
The program for implementing image maps using HTML is executed successfully.
