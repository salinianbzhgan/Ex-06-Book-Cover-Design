# Ex-06-Book-Cover-Design
NAME: SALINI
REF ID: 212223220091
DEPT: IT

AIM
To Design a book cover page using HTML and CSS.

DESIGN PROCEDURE

Step 1:
Create a html file .

Step 2:
Choose background image and photo to be used and save it to the repository. position the elements appropriately

Step 3:
Use html and css code to design the book cover.

CODE
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta name="viewport"
        content="width=device-width,initial-scale=1.0">
        <style>

        
        .bookpage{
            width: 400px;
            height: 600px;
            color:white;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium','Arial Narrow',Arial,sans-serif;
            background-image:url(verity.jpeg);
            background-size: cover;
        }

        .insigth{
            color:rgb(246, 239, 239);
        }

        .hrstyle{
            width:100px;
        }

        .author{
            color:white;
            display:inline;
            position:relative;
            color:white;
            top:190px;

            font-family:Georgia;
            font-size:medium;
            
        }

        .booktitle{
            font-family:'Courier New',Courier,monospace;
            font-size: larger;
            text-align:center;
            position:relative;
            top:30px;

        }

        .id{
            width:400px;
            position:relative;
            top:180px;

        }

        .pub{
            font-size:medium;
            position: relative;
            top:155px;
            left:330px;

        }

        .ed{
            color: white;
            font-size:medium;
            font-family:Verdana;
            position:relative;
            top:85px;
        }

        .subtitle{
            font-family:Tahoma;
            font-size: large;
            position:relative;
            top:40px;

        }
         .mypic{
             position:relative;
             top:135px;
             left:260px;
             width:100px;
             height:100px;
             background-size:cover;
         }
        </style>
        <title>Book Cover Page</title>
    </head>
    <body> 
        <div class="bookpage">
            <div class="insigth">
                A NOVEL
            </div>
            <div class="hrstyle">
                <hr style="color:whitesmoke;">
            </div>
            <div class="booktitle">
                <h1>Verity</h1></div>
            <div class="subtitle">
                'an astonishing novel which will let you dumbstruck'
            </div>
            <div class="mypic">
                <img src="author image.jpeg" width="130" height="145" alt="">
            </div>
            <div class="id">
                <hr style="color:white;">
            </div>
            <div class="author">
                <p><b>Colleen Hoover</b></p>
            </div>
            <div class="pub">
                phase
            </div>
            <div class="ed">
                <b>old Edition</b>
            </div>
        </div>
    </body>
</html>
```
OUTPUT
![Screenshot 2023-12-20 103014](https://github.com/salinianbzhgan/Ex-06-Book-Cover-Design/assets/145742862/e00ebfa1-fbbc-4803-9f44-988599b69b1a)

