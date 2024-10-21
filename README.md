# Ex04 Places Around Me
## Date: 13-10-2024

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
        <title>MAP APP</title>
    </head>
    <body>
        <h1 align="center" bgcolor="Violet">NELLORE</h1>
        <h2 align="center" bgcolor="Violet">Narra Nanditha(212221040111)</h2>
        <center>
        <img src="nellore.png" usemap="#image-map">

        <map name="image-map">
            <area target="" alt="Hotel Minerva Grand" title="Hotel Minerva Grand" href="minerva.html" coords="652,440,892,496" shape="rect">
            <area target="" alt="Narayana Medical College" title="Narayana Medical College" href="narayana.html" coords="1307,569,1153,573,1167,648,1312,648" shape="poly">
            <area target="" alt="Sri Raja Rajeswari Temple" title="Sri Raja Rajeswari Temple" href="temple.html" coords="544,676,374,645" shape="rect">
            <area target="" alt="Hotel Swagath" title="Hotel Swagath" href="swagath.html" coords="840,280,978,325" shape="rect">
            <area target="" alt="Reliance Digital" title="Reliance Digital" href="reliance.html" coords="758,375,80" shape="circle">
        </center>
        </map>
    </body>
</html>
```
```
reliance.html

<!DOCTYPE html>
<html>
<head>
<title>RELIANCE DIGITAL</title>
</head>
<body bgcolor="pink">
<h1 align="center"><b>NELLORE</b></h1>
<h3 align="center"><b>RELIANCE DIGITAL</b></h3>
<hr size="3" color="white">
<p align="center">
<font face="Georgia" size="5">
 1)Reliance Digital is located near Police Office Road, Opposite Reliance Mart, Brahmananda Puram, Nellore, Andhra Pradesh 524001<br>
2) Reliance Digital is India's largest electronics retailer, having 500+ large format stores across India. The brand offers 5,000+ products from 300+ international and national brands.<br>
</p>
</body>
</html>
```
```
Minerva.html

<!DOCTYPE html>
<html>
<head>
<title>HOTEL MINERVA GRAND</title>
</head>
<body bgcolor="cyan">
<h1 align="center"><b>NELLORE</b></h1>
<h3 align="center"><b>HOTEL MINERVA GRAND</b></h3>
<hr size="3" color="white">
<p align="center">
<font face="Georgia" size="5">
 1)Minerva Group of Hotels and Restaurants. Being a boutique business hotels & restaurants chain, it strides on to break new grounds with its state-of-the-art conveniences, distinct services and fine dining familiarities.<br>
2)Our Dining
Indulge in a culinary journey that delights the senses and captures the essence of BLUE FOX . Our expert chefs have meticulously crafted a menu that showcases the finest ingredients, innovative flavors, and exquisite presentations.<br>
3)It is located in Grand Trunk Road, Nellore - 0861 235 8888.<br>
</p>
</body>
</html>
```
```
Narayana.html

<!DOCTYPE html>
<html>
<head>
<title>NARAYANA MEDICAL COLLEGE AND HOSPITAL</title>
</head>
<body bgcolor="lavender">
<h1 align="center"><b>NELLORE</b></h1>
<h3 align="center"><b>NARAYANA MEDICAL COLLEGE AND HOSPITAL</b></h3>
<hr size="3" color="white">
<p align="center">
<font face="Georgia" size="5">
 1)Narayana Medical College is located in Muthukur Road, Chinthareddypalem, Nellore, Andhra Pradesh 524003<br>
2)Narayana Medical College & Hospital is in alliance with corporate partners in delivering health care to their employee. Narayana Medical College & Hospital provides health care to several large and small Public Sectors and Private Sectors. <br>
</p>
</body>
</html>
```
```
Swagath.html

<!DOCTYPE html>
<html>
<head>
<title>HOTEL SWAGATH</title>
</head>
<body bgcolor="blue">
<h1 align="center"><b>NELLORE</b></h1>
<h3 align="center"><b>HOTEL SWAGATH</b></h3>
<hr size="3" color="white">
<p align="center">
<font face="Georgia" size="5">
 1)Hotel Swagath is located near Nehru Mansions, Grand Trunk Road, Near Madras Bus Stand, Somasekara Puram, Nellore, Andhra Pradesh · 078422 33344<br>
2) HOtel swagath Being a boutique business hotels & restaurants chain, it strides on to break new grounds with its state-of-the-art conveniences, distinct services and fine dining familiarities. <br>
</p>
</body>
</html>
```
```
temple.html

<!DOCTYPE html>
<html>
<head>
<title>SRI RAJARAJESHWARI TEMPLE</title>
</head>
<body bgcolor="yellow">
<h1 align="center"><b>NELLORE</b></h1>
<h3 align="center"><b>SRI RAJARAJESHWARI TEMPLE</b></h3>
<hr size="3" color="white">
<p align="center">
<font face="Georgia" size="5">
 1)Sri Rajarajeswari Temple is located vedaypalem,nellore,andrapraddesh-524302<br>
2)Sri Raja Rajeshwari Temple in Durgamitta is a very famous Ammavari temple located at Durgamitta in Nellore district, Andhra Pradesh.  <br>
3)The presiding deity in this temple is Sri Rajarajeswari Ammavaru. Devi Navaratrulu (Dussera) is the most festival celebrated in this temple.<br>
</p>
</body>
</html>


```


## OUTPUT
![1](https://github.com/user-attachments/assets/e9a763c6-2d7d-45b4-ad03-9ad9d982f5f4)
![2](https://github.com/user-attachments/assets/77c10012-672e-473c-a860-8d76d91f120b)
![3](https://github.com/user-attachments/assets/64c104a5-2138-4a84-9ae9-c1f00c84d306)
![4](https://github.com/user-attachments/assets/7fb59304-1a6e-45f1-9e1a-fdc7584d09f5)
![5](https://github.com/user-attachments/assets/2bc04608-5bdb-4b36-8a63-8e622c1cb419)
![6](https://github.com/user-attachments/assets/9b0ba8cf-1daa-4e10-9c73-e6e972cd342d)


## RESULT
The program for implementing image maps using HTML is executed successfully.
