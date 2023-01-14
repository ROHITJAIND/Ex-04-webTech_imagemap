# Places Around Me
# Aim:
To develop a website to display details about the places around my house.

# Design Steps:
## Step 1:
Clone the github repository into Theia IDE.
## Step 2:
Create a new Django project.
## Step 3:
Write the needed HTML code.
## Step 4:
Run the Django server and execute the HTML files.  

# Code:
- map.html
```
<!DOCTYPE html>
<html lang="en">
<head>
<title>My City</title>
</head>
<body bgcolor="lightblue">
<h1 align="center">
<font color="red"><b>MY AREA</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>ROHIT JAIN D (22005894)</b></font>
</h3>
<center>
<img src="/static/images/map.jpeg" usemap="#MyCity">
<map name="MyCity">
<area shape="rectangle" coords="32,126,188,296" href="/static/html/CELL.html" title="CELL CARE">
<area shape="rectangle" coords="329,6,477,308" href="/static/html/NUTS.html" title="FRUITS AND NUTS SHOP">
<area shape="rectangle" coords="757,428,901,653" href="/static/html/CLINIC.html" title="SK CLINIC">
<area shape="rectangle" coords="3,611,208,791" href="/static/html/IPS.html" title="IPS TRAINING CENTER">
<area shape="rectangle" coords="195,432,369,570" href="/static/html/STUDIO.html" title="LITTLE BIG STUDIO">
</map>
</center>
</body>
</html>

```
- CELL.html
```
<!DOCTYPE html>
<html lang="en">
<head>
<title>CELL CARE</title>
</head>
<body bgcolor="cyan">
<h1 align="center">
<font color="red"><b>CELL CARE</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>ELECTRONICS REPAIR</b></font>
</h3>
<hr size="3" color="red">
<hr size="3" color="red">
<p align="justify">
<font face="Courier New" size="5">
<b>
Here you can get your any electornics devices repaired within 42 hours of sevice.
They also have online orders.Free delivery at door step.Repair your mobile screen
at the lowest cost.All brands of mobile are availabe for service and sales. Also they can 
replace the battery,unlock your phone,apply new scratch card,repair water damage
and many more..
</b>
</font>
</p>
<hr size="3" color="red">
<h2 align="center">
<font><b>THANKYOU</b></font>
</h2>
</body>
</html>

```
- CLINIC.html
```
<!DOCTYPE html>
<html lang="en">
<head>
<title>SK CLINIC</title>
</head>
<body bgcolor="lightpink">
<h1 align="center">
<font color="red"><b>S.K CLINIC</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Dr. SELVAKUMAR CLINIC</b></font>
</h3>
<hr size="3" color="red">
<hr size="3" color="red">
<p align="justify">
<font face="Arial" size="5">
<b>
Dr. Selvakumar is a Doctor in Mogappair, Chennai and has an experience of 35 years in this field.
Dr. Selvakumar practices at Sri Kumaran Clinic in Mogappair, Chennai. He completed MBBS from
Madurai Medical College in 1988.He is a member of Tamilnadu Medical Council.You can even 
get online appoinments to meet him.He has a special interest in Pancreatic and Colorectal 
surgery and has many publications to his credit.
</b>
</font>
</p>
<hr size="3" color="red">
<h2 align="center">
<font><b>THANKYOU</b></font>
</h2>
</body>
</html>

```
- IPS.html
```
<!DOCTYPE html>
<html lang="en">
<head>
<title>IPS TRAINING CENTER</title>
</head>
<body bgcolor="lightgreen">
<h1 align="center">
<font color="red"><b>IPS TRAINING CENTER</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>TRAIN YOURSELF TO GET IPS POST</b></font>
</h3>
<hr size="3" color="red">
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
All over India, people aspiring to become IAS, IPS and other elite bureaucratic service officers 
and seeking to fine tune their preparation, flock to IPS TRAINING CENTER for Civil Service 
coaching.With branches in Chennai, Delhi, Bengaluru, Thiruvananthapuram, Trichy, Salem, 
Madurai and Coimbatore, it is the Academy of choice for Civil Service aspirants. 
</font>
</p>
<hr size="3" color="red">
<h2 align="center">
<font><b>THANKYOU</b></font>
</h2>
</body>
</html>

```
- NUTS.html
```
<!DOCTYPE html>
<html lang="en">
<head>
<title>FRUITS AND NUTS SHOP</title>
</head>
<body bgcolor="lightyellow">
<h1 align="center">
<font color="red"><b>FRUITS AND NUTS SHOP</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>BUY FRESH FRUITS AND NUTS</b></font>
</h3>
<hr size="3" color="red">
<hr size="3" color="red">
<p align="justify">
<font face="Tahoma" size="5">
Here you can get fresh fruits and tasty nuts ,spices. It is truely natural and good
for our health .They provide free delivery at our door step and also they take 
online orders .They have dry fruits , spices  , health food , organic food , diet
snacks , coffees and teas , juices and syrups , imported chocolates and biscuits ,
and many more.
</font>
</p>
<hr size="3" color="red">
<h2 align="center">
<font><b>THANKYOU</b></font>
</h2>
</body>
</html>

```
- STUDIO.html
```
<!DOCTYPE html>
<html lang="en">
<head>
<title>LITTLE BIG STUDIO</title>
</head>
<body bgcolor="lightblue">
<h1 align="center">
<font color="red"><b>LITTLE BIG STUDIO</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>BEST PHOTOGRAPHY CENTER</b></font>
</h3>
<hr size="3" color="red">
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
Little Big Studio offers you the best capturing of beautiful wedding films with their trained
professionals. They capture beautiful memories with beautiful shots. They offer you the best
wedding photography and videography .They have a beautiful idea of capturing the best 
moment of events of most beautiful memories to be shot at the best time.They have many 
branches across the country.
</font>
</p>
<hr size="3" color="red">
<h2 align="center">
<font><b>THANKYOU</b></font>
</h2>
</body>
</html>

```
# Output:

![MAP DISP](https://user-images.githubusercontent.com/118707073/212474643-99c25b24-427d-4032-9433-25f5d41f06ab.png)


![CELL](https://user-images.githubusercontent.com/118707073/212474297-2e609997-cc75-4b54-a3d1-71c00d937679.png)  
![CLINIC](https://user-images.githubusercontent.com/118707073/212474301-7525bc4e-24dd-4218-8d8b-f90e7989a245.png)  
![NUTS](https://user-images.githubusercontent.com/118707073/212474308-59acfb85-a810-4f2e-967e-4a9fbd0cd432.png)  
![STUDIO](https://user-images.githubusercontent.com/118707073/212474313-8960369d-7617-41b9-acdd-3eef441ce978.png)  
![IPS](https://user-images.githubusercontent.com/118707073/212474330-ab5869fb-384d-4267-a37f-50ffe5ab01fe.png)  
# HTML Validator:
![validator](https://user-images.githubusercontent.com/118707073/212474529-650a53d6-91a2-4bdd-aba5-3c9ed55ba880.png)  
# Result:
The program for implementing image map is executed successfully.

