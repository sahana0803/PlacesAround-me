# Places Around Me

## AIM:
To develop a website to display details about the places around my house.

## Design Steps:

### Step 1: Create a new django project and app

### Step 2: Type code in views and urls.py

### Step 3: create HTML files according to your places

### Step 4: Give deatils about that places in html file

### Step 3: Run the server

## Code:
```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>MAT MAP</title>
    </head>
    <body>
        <img src="/static/images/matmap.jpg" width ="986" height="782" usemap="#matmap" alt>
        <MAP name="matmap">
             <AREA shape="RECT" coords="384,329,457,398"
                   href = "/meenakshitemple/" Title="meenakshitemple" alt>
             <AREA shape="RECT" coords="586,130,625,163"
                   href = "/thousandpillars/" Title="thousandpillars" alt>
             <AREA shape="RECT" coords="830,194,899,223"
                   href = "/puthumandapam/" Title="puthumandapam" alt>
             <AREA shape="RECT"  coords="411,615,506,628"
                   href = "/southtower/"   Title="southtower" alt>
             <AREA shape="RECT"  coords="324,116,379,129"
                   href = "/northtower/"  Title="northtower" alt>
         
        </MAP>

    </body>
</html>
```

## Output:
![output](./exp4web.png)
![output](./exp4web2.png)
## Result:
Thus a website is developed to display details about the places around my house.
