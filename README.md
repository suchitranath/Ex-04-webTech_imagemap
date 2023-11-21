# Places Around Me
Name: Suchitra Nath
Dept: IT
Ref No: 23000325
# Aim:
To develop a website to display details about the places around my house.

# Design Steps:
## Step 1
create a folder "static" under the project folder "bakkiya".
## Step 2
in static, create a file "map.html".
## Step 3
go to google maps and take screenshot of your home along with 5 places around it.
## Step 4
go to image-maps.com and make 5 locations on it using the shapes used in maps.
## Step 5
copy the code and add it into "map.html"
## Step 6
create the html documents to be displayed when clicked on the location in image map.
## Step 7
take screenshot of the output

# Code:
## map.html
```<html>
    <head>
        <title>My City</title>
    </head>
    <body>
        <h1 align="center">
        <font color="red"><b>Avadi</b></font> 
        </h1>
        <h3 align="center">   
        <font color="blue"><b>Suchitra Nath(23000325)</b></font> 
        </h3>
        <center>
            <img src="map.png" usemap="#MyCity" height="610" width="1450">
            <map name="#MyCity"
            <area target="_parent" alt="" title="MY HOME" href="home.html" coords="388,241,259,328" shape="rect"></map>
            <area target="" alt="Murugappa Polytechnic college" title="Murugappa Polytechnic college" href="college.html" coords="300,156,473,94" shape="rect"></map>
            <area target="" alt="Avadi Lake Green Park" title="Avadi Lake Green Park" href="park.html" coords="371,271,552,329" shape="rect"></map>
            <area target="" alt="Elite wood work " title="Elite wood work " href="elite.html" coords="621,476,455,418" shape="rect"></map>
            <area target="" alt="Pachaiamman Temple" title="Pachaiamman Temple" href="temple.html" coords="379,67,591,93" shape="rect"></map>
        </center>   
    </body>
</html>
```

## home.html
```<html>
    <head>
        <title>HOME SWEET HOME</title>
    </head>
    <body style="background-color: maroon; color: white; text-align: center;">
        <h1 style="font-size: 100px;"><b>my home</b></h1>
        <ul style="list-style-type: none; padding: 0;">
            <li style="margin-bottom: 10px;font-size: 25px;">&#9733; I live in my own home.</li>
            <li style="margin-bottom: 10px;font-size: 25px;">&#9733; In my home there are five members.</li>
            <li style="margin-bottom: 10px; font-size: 25px;">&#9733; Myself, Mom, Dad, Grandfather and Grandmother.</li>
        </ul>
    </body>
</html>
```

## college.html
```<html>
    <head>
        <title>Murugappa Polytechnic College</title>
    </head>
    <body style="background-color: yellowgreen; color: black; text-align: center;">
        <h1 style="font-size: 100px;"><b>Murugappa Polytechnic College</b></h1>
        <ul style="list-style-type: none; padding: 0;">
            <li style="margin-bottom: 10px;font-size: 25px;">&#9733; It is a government aided insitution established in the year 1957.</li>
            <li style="margin-bottom: 10px;font-size: 25px;">&#9733; The college is located in Avadi, Chennai.</li>
            <li style="margin-bottom: 10px; font-size: 25px;">&#9733; Offers diploma in civil, computer, ECE, mechanical engineering etc.</li>
        </ul>
    </body>
</html>
```

## park.html
```<html>
    <head>
        <title>Avadi lake park</title>
    </head>
    <body style="background-color: pink; color: rgb(0, 0, 0); text-align: center;">
        <h1 style="font-size: 100px;"><b>Avadi green lake park</b></h1>
        <ul style="list-style-type: none; padding: 0;">
            <li style="margin-bottom: 10px;font-size: 25px;">&#9733; The park was well-maintained with lush green lawns and beautiful flowers.</li>
            <li style="margin-bottom: 10px;font-size: 25px;">&#9733; This park which contains lake in it, It`s atmosphere is very quite and pleasant.</li>
            <li style="margin-bottom: 10px; font-size: 25px;">&#9733; Boat rides are fun when with friends.</li>
        </ul>
    </body>
</html>
```

## elite.html
```<html>
    <head>
        <title>Elite Woodwork</title>
    </head>
    <body style="background-color: red; color: wheat; text-align: center;">
        <h1 style="font-size: 100px;"><b>Elite Woodwork</b></h1>
        <ul style="list-style-type: none; padding: 0;">
            <li style="margin-bottom: 10px;font-size: 25px;">&#9733;  Elite Woodwork is an amazingly versatile Sarasota company specializing in custom kitchens, outdoor kitchens, cabinets, and furniture.</li>
            <li style="margin-bottom: 10px;font-size: 25px;">&#9733; The quality of the workmanship is phenomenal and the quality of the true customer service goes beyond what one can imagine and hope for.</li>
        </ul>
    </body>
</html>
```

## temple.html
```<html>
    <head>
        <title>Pachaiamman Temple</title>
    </head>
    <body style="background-color: blueviolet; color: whitesmoke; text-align: center;">
        <h1 style="font-size: 100px;"><b>Pachaiamman Temple</b></h1>
        <ul style="list-style-type: none; padding: 0;">
            <li style="margin-bottom: 10px;font-size: 25px;">&#9733; Hindu temple with an intricately carved gopura gate & brightly restored statues of deities & horses.</li>
            <li style="margin-bottom: 10px;font-size: 25px;">&#9733; The most unique feature of this temple is the pure water bodies that flow around it. </li>
            <li style="margin-bottom: 10px; font-size: 25px;">&#9733; The Goddess - Parvati is in the form of Pachaiamman - green coloured idol. </li>
        </ul>
    </body>
</html>
```

# Output:


![map](https://github.com/suchitranath/Ex-04-webTech_imagemap/assets/145742631/c1524ad3-c557-40ec-a9b0-729246178589)


![Screenshot 2023-11-21 180521](https://github.com/suchitranath/Ex-04-webTech_imagemap/assets/145742631/249f8254-42be-45d5-a627-9600656be0fc)


![Screenshot 2023-11-21 181345](https://github.com/suchitranath/Ex-04-webTech_imagemap/assets/145742631/8dabb92a-818d-4c53-af6d-787c8ff31bf7)


![Screenshot 2023-11-21 182139](https://github.com/suchitranath/Ex-04-webTech_imagemap/assets/145742631/c1473e4a-2037-44d4-9bb5-2945ccd7f85b)


![Screenshot 2023-11-21 182540](https://github.com/suchitranath/Ex-04-webTech_imagemap/assets/145742631/ead92088-9ca2-4d80-8100-3d3c7c36cc4b)


![Screenshot 2023-11-21 183007](https://github.com/suchitranath/Ex-04-webTech_imagemap/assets/145742631/5ff96778-56e4-4806-9728-bbacbe5f5be3)


# Result:
The output was verified successfully
