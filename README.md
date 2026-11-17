# Teaching Demo

## What We Will Be Going Over
    1. How to Start with HTML
    2. Coding Images
    3. Making Buttons!

## How to Start with HTML
MUST Start with 
    !DOCTYPE html
THEN,
    html> </html
(I have removed the <> from the beginning and end so
the page's code won't break)

## Coding Images
Make sure to check that your image follows these guidelines:
    1. PNG format 
    2. Lowercase 
    3. No spaces/Uses - _

Typical image code will look like:

    <img src="image.png"   alt="image" />

However, if in a class, the code will look like:

    url(“background_image.png”);

## Making Buttons
There are multiple ways to approach making a button,
However, the base code is listed below:

    <button onclick="">
    </button>

Now we will learn how to code a button to send an alert.
Use this as a base. 

    <html>
        <body>
        
        
        </body>
    </html>

Next, we will learn how to code a button to redirect
you to another page. Use this as a base. 

    <html>
      <head>
        <style>
          body {
            background-image: url("background.png");
            background-repeat: no-repeat;
            background-position: center center;
            background-size: cover;
            background-attachment: fixed;
            margin: 0;
            padding: 0;
            position: relative;
            min-height: 100vh;
          }

          .button-class {
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      border: none;
      padding: 0;
      background: transparent;
      cursor: pointer;
      border-radius: 4px;
    }

    .button-class img {
      width: 120px;  
      height: auto;
      display: block;
    }
        </style>
      </head>

      <body>
    #button code goes here
      </body>
    </html>




Enjoy your new button-mashing website!







