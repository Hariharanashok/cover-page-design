# cover-page-design
## AIM:
To develop a website to display the cover page design of a book

## Design Steps:

### Step 1:
Clone your git hub repository
### Step 2:
Make a change in settings.py
### Step 3:
Now build a html code and use CSS for colours and effects.
### Step 4:
Then, run the server and take a screenshot of your book cover page.

## Code:
```python
<!DOCTYPE html>
<html lang="en">
    <head>
         <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
         <style>

        .bookpage{
            width: 600px;
            height: 600px;
            background-color: #ffffff;
            color:rgb(140, 148, 143);
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(../images/Robot.jpg);
            background-size: cover;
        }
            

        .toptext{
            color:rgb(255, 254, 254);

        }

        
        .tophr{
            width:140px;
        }
        .author{
            color: white;
            display: inline;
            position: relative;
            color:lightblue;
            top:190px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            color: white;
            font-family: Arial, Helvetica, sans-serif;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
            font-size: 20px;
        
        }
        .id {
            width:400px;
            position: relative;
            top:180px;
            
        }
        .publisher{
            font-size: medium;
            position: relative;
            top:155px;
            left:330px;
        }
        .edition{
            color:wheat;
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:85px;

        }
        .subtitle{
            color: white;
            font-family:'Montserrat',sans-serif;
            font-weight: bold;
            text-align: center;
            font-size: 15px;
            position: relative;
            top:100px;
        }
        .photo{
            position: relative;
            top: 135px;
            left: 260px;
            width: 100px;
            height: 100px;
            background-size: cover;
        }
        </style>
        <title>Book Cover Page</title>
    </head>
    <body>
        <div class="bookpage">
            <div class="toptext">
                EXPERT INSIGHT
            </div>
            <div class="tophr">
                <hr style="color: rgb(0, 151, 164);">
            </div>
            <div class="booktitle">
                <h1>Responsive Web Design With HTML5 and CSS</h1></div>
            <div class="subtitle">
                A responsive web design is a clever method of programming a website using HTML,
                CSS and JavaScript to provide its users with the best possible viewing experience while also including features like scrolling,
              reading, and resizing across a wide range of devices, such as desktop computers, tablets or smartphones.
            </div>
            <div class="id">
                <hr style="color: rgb(8, 8, 8);">
            </div>
            <div class="author">
               <p><b>Hariharan A</b></p>
            </div>
            <div class="publisher">
                
            </div>
            <div class="edition">
                <b>Ninth Edition</b>
            </div>
            
        </div>
    </body>
</html>
```

## Server Output:
![Front page Server](https://github.com/Hariharanashok/cover-page-design/assets/120353431/fe27fdff-3da2-44bb-babf-e144816789e5)

## Output:
![Frontpage](https://github.com/Hariharanashok/cover-page-design/assets/120353431/3e4b15ac-6936-4567-afe2-590f95101b3f)

## Result:
The cover page design is successfully created.
