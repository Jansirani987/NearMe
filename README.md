# Ex04 Places Around Me
## Date: 23.11.2024

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
<font color="red"><b>Vellore</b></font>  
</h1>
<h3 align="center">
<font color="blue"><b>Jansi rani A A (24900239)</b></font>    
</h3>
<center>
    <img src="map.png" usemap="#image-map">

    <map name="image-map">
        <area target="" alt="vellore" title="vellore" href="home.html" coords="607,216,50" shape="circle">
        <area target="" alt="poigai" title="poigai" href="poigai.html" coords="462,224,47" shape="circle">
        <area target="" alt="adukkamparai" title="adukkamparai" href="hospital.html" coords="617,389,50" shape="circle">
        <area target="" alt="bagayam" title="bagayam" href="area.html" coords="591,306,40" shape="circle">
        <area target="" alt="ariyur" title="ariyur" href="village.html" coords="523,341,42" shape="circle">
    </map>  
</center>
</body>
</html>


home.html
<html>
<body bgcolor="sky blue">
<h1 align="center">
<font color="black"><b>vellore</b></font>    
</h1>
<h3 align="center">
<font color="green"><b>Home</b></font>    
</h3>
<hr size="3" color="green">
<p align="justify">
<front face="Georgia" size="S">
Vellore had the previlege of being the seat of the Pallava, Chola, Nayak,
Maratha, Arcot Nawabs and Bijapur Sultan Kingdoms. It was described as the
best and  strongest fortress in the Carnatic War in the 17th Century.
<p>
</body>
</html>


poigai.html
<html>
<body bgcolor="yellow">
<h1 align="center">
<font color="black"><b>vellore</b></font>    
</h1>
<h3 align="center">
<font color="red"><b>poigai</b></font>    
</h3>
<hr size="3" color="red">
<p align="justify">
<front face="Georgia" size="S">
Poigai village is administrated by a sarpanch who is elected representative of the
village by the local elections. As per 2019 stats, Poigai village comes under Anaikattu
Vidhan Sabha constituency & Vellore Lok Sabha constituency. Vellore is nearest town to 
poigai village for all major economic activities, which is approximately 7km away.
<p>
</body>
</html>


hospital.html
<html>
<body bgcolor="violet">
<h1 align="center">
<font color="black"><b>Vellore</b></font> 
</h1>
<h3 align="center">
<font color="black"><b>adukkamparai</b></font>    
</h3>
<hr size="3" color="black">
<p align="justify">
<front face="Georgia" size="S">
Adukkamparai is a small town in Vellore City. Vellore district,Tamil Nadu,
India. It is situated on the Vellore to Cuddalore highway(8.9 km) from Vellore.
There is a government hospital and medical college located at Adukkamparai.
<p>
</body>
</html>


area.html
<html>
<body bgcolor="red">
<h1 align="center">
<font color="black"><b>Vellore</b></font>    
</h1>
<h3 align="center">
<font color="black"><b>bagayam</b></font>    
</h3>
<hr size="3" color="black">
<p align="justify">
<front face="Georgia" size="S">
Bagayam is a Locality in Vellore City in Tamil Nadu State, India.
Bagayam Pin code is 632002 and postal head office is Virupakshipuram.
Edayansathu,Ramset Nagar,Aavai Nagar,Thiruvalluvar Nagar,Kurisilapattu 
are the nearby Localities to Bagayam.
<p>
</body>
</html>


village.html
<html>
<body bgcolor="brown">
<h1 align="center">
<font color="green"><b>Vellore</b></font>    
</h1>
<h3 align="center">
<font color="green"><b>ariyur</b></font>    
</h3>
<hr size="3" color="green">
<p align="justify">
<front face="Georgia" size="S">
According to Census 2011 information the location code or village
code of Ariyur village is 630826. Ariyur village is located in  Vellore 
taluka of Vellore district in Tamil Nadu, India. Vellore is the district &
sub-district headquarter of Ariyur village.
<p>
</body>
</html>


```
## OUTPUT
![alt text](<Screenshot (14).png>)
![alt text](<Screenshot (15).png>)
![alt text](<Screenshot (19).png>)
![alt text](<Screenshot (17).png>)
![alt text](<Screenshot (16).png>)
![alt text](<Screenshot (18).png>)







## RESULT
The program for implementing image maps using HTML is executed successfully.
