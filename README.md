# Ex04 Places Around Me
## Date: 21-10-2024

Name: ETTA SUPRAJA

Reg No: 212223220022

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
Nearme.html:
```
<html>
    <head>
        <title>
            KADAPA
        </title>
    </head>
    <body>
        <h1 align="center">KADAPA(ETTA SUPRAJA)</h1>
        <center>
            <img src="c:\Users\admin\AppData\Local\Packages\5319275A.WhatsAppDesktop_cv1g1gvanyjgm\TempState\5833F44355C400AD3EFD00141ECCA9A7\WhatsApp Image 2024-10-21 at 15.32.58_52313b06.jpg" usemap="#mapnew">
            <map name="mapnew">
                <area target="" alt="RIMS Hospital" title="RIMS_Hospital" href="RIMS.html" coords="263,71,61" shape="rec">
                <area target="" alt="Joyalukkas Jewellery" title="GANDIKOTA" href="Joyalukkas.html" coords="63,481,107,457,179,485,167,521,60,524" shape="poly">
                <area target="" alt="Devuni Kadapa" title="Devuni kaadapa" href="Devuni.html" coords="589,179,41" shape="square">
                <area target="" alt="Hotel Mayura Gardenia" title="Hotel_Mayura_Gardenia" href="Mayura.html" coords="256,405,326,436,289,488,204,473,183,422" shape="poly">
            </map>
        </center>
    </body>
</html>
```

Rims.html:
```
<html>
    <head>
        <title>
            RIMS Hospital
        </title>
        <style>
            p{
                font-size: xx-large;
                color: black;
                
            }
            body{
                background-color:bisque;
            }
        </style>
    </head>
    <body>
        <h1 align="center">RIMS Hospital</h1>
        <p>
            The RIMS Hospital is  located in Kadapa. It is the famous hospital in kadapa.It is one of the best government institues in the country.It was founded in 2006 by the state of Andhra Pradesh with the goal of improving quality medical care in this underserved area and receiving clinical instruction from all trained students.
            It was inaugurated on 27 September 2006 by the then UPA Chair Person Smt.Sonia Gandhi.
        </p>
        <center>
            <img src="c:\Users\admin\AppData\Local\Packages\5319275A.WhatsAppDesktop_cv1g1gvanyjgm\TempState\AADECCF20333FE8CB7946318389D4555\WhatsApp Image 2024-10-20 at 13.57.24_bc0ce942.jpg" width="600" height="300">
        </center>
    </body>
</html>
```

Devuni Kadapa.html:
```
<html>
    <head>
        <title>
            Devuni kadapa
        </title>
        <style>
            p{
                font-size: xx-large;
                color: black;
                
            }
            body{
                background-color:beige;
            }
        </style>
    </head>
    <body>
        <h1 align="center">Devuni Kadapa</h1>
        <p>
            Devuni Kadapa is also known as Tirumala Thol Gadapa Devuni Kadapa-Shri Venkatesara Swamy Devasthanam.The place Kadapa is named after the word "Devuni Gadapa" meaning "entrance for Lord Venkateswara Swamy".The idol of the Lord Venkateswara has been established by Kripicharya,hence the ancient name of devuni kadapa is aslo mentioned in puranas as "Kripavathi Kshetram".Pilgrims visit Lord Venkaeswara here because first they have to pray Annamacharya and Potuluri Veerabramhendra Swamy.This temple is very famous in kadapa district.
        <center>
            <img src="c:\Users\admin\AppData\Local\Packages\5319275A.WhatsAppDesktop_cv1g1gvanyjgm\TempState\C50052E56093469D15D7CA0ED7C85E43\WhatsApp Image 2024-10-21 at 14.08.49_21a2207e.jpg" width="600" height="300">
        </center>
    </body>
</html>
```
Mayura.html:
```
<html>
    <head>
        <title>
            Hotel Mayura Gardenia
        </title>
        <style>
            p{
                font-size: xx-large;
                color: black;
                
            }
            body{
                background-color:bisque;
            }
        </style>
    </head>
    <body>
        <h1 align="center">Hotel Mayura Gardenia</h1>
        <p>
            Mayura Gradenia Group of Hotels and Restaurants. Being a boutique business hotels & restaurants chain, it strides on to break new grounds with its state-of-the-art conveniences, distinct services and fine dining familiarities.Our Dining
            Indulge in a culinary journey that delights the senses and captures the essence of BLUE FOX . Our expert chefs have meticulously crafted a menu that showcases the finest ingredients, innovative flavors, and exquisite presentations.It is located in Nehru Park,Co-operative Colony, Kadapa - 0861 235 8888.It has 106 Elite Rooms & Suites catering to every class of traveler be it business or leisure from India & abroad. 
            The Lunch food quality was very good and the service in the Restaurant was very fast. The Breakfast was hot and tasty.Location is very good .
        </p>
        <center>
            <img src="c:\Users\admin\AppData\Local\Packages\5319275A.WhatsAppDesktop_cv1g1gvanyjgm\TempState\AA0792521918C87688E46598DD2171CC\WhatsApp Image 2024-10-20 at 12.50.13_3a68adfd.jpg" width="600" height="300">
        </center>
    </body>
</html>
```
Joyalukkas.html:
```
<html>
    <head>
        <title>
            Joyalukkas Jewellery
        </title>
        <style>
            p{
                font-size: xx-large;
                color: black;
                
            }
            body{
                background-color:blanchedalmond;
            }
        </style>
    </head>
    <body>
        <h1 align="center">Joyalukkas Jewellery</h1>
        <p>
          Joy Alukkas Jewellery is located in kadapa.Joy Alukkas is an Indian bussinessman from Kerala.he is the chairman and managing director of Joyalukkas Group.According to a 2023 Forbes report,he has a net worth of $4.4billion.The location of the Joyalukkas Jewellery store is Near R.T.C. bus stand,kadapa.   
        </p>
        <center>
            <img src="c:\Users\admin\AppData\Local\Packages\5319275A.WhatsAppDesktop_cv1g1gvanyjgm\TempState\E735C2E2F0EDA0A7EDDC67A21CBEBEA6\WhatsApp Image 2024-10-21 at 14.18.44_3cae2a89.jpg" width="600" height="300">
        </center>
    </body>
</html>
```

## OUTPUT
Imagemap

![WhatsApp Image 2024-10-21 at 15 34 17_4900881c](https://github.com/user-attachments/assets/048e87d4-ce9a-45e4-a2ae-1eac50a1cf9e)


Rims

![WhatsApp Image 2024-10-21 at 15 35 20_a6132288](https://github.com/user-attachments/assets/2633a043-d95d-42bc-9e8a-0012d4bba584)


Joyalukkas

![WhatsApp Image 2024-10-21 at 15 37 30_4eba1e2d](https://github.com/user-attachments/assets/a04d3c71-56ad-438c-b4f8-5d74722bb531)

Dveuni Kadapa

![WhatsApp Image 2024-10-21 at 15 36 49_883ee8e9](https://github.com/user-attachments/assets/1eda984f-721e-47cf-92be-05059db1cf7c)

Mayura Gardenia

![WhatsApp Image 2024-10-21 at 15 35 52_e89f9089](https://github.com/user-attachments/assets/2b9de566-fa99-4917-a250-dc78d06817eb)


## RESULT
The program for implementing image maps using HTML is executed successfully.
