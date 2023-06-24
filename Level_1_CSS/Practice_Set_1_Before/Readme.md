# INLINE CSS

Syntax :- <h1 style="color: red">Hello From Level 1 from CSS</h1>

# INTERNAL CSS
use style tag under the head sections

Synatx:-

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        h2{
            color: blueviolet;
            font-size: medium;
        }
    </style>
</head>


# External CSS

use the css from the external file
<link rel="stylesheet" href="index.css">
h3{
    color: red;
}

# ForeGround 

color is used to set the foreground things ( button / text / link )

# Color System

1. RGB color ( red , green , blue ) (0,0,0) => range vary from [ 0 - 255 ]
2. HEXA-DECIMAL color ( digit from 0-15 ) => Expected value :- 0,1,2,3,4,5,6,7,8,9,a,b,c,d,e,f.

In Hexadecimal we are also setting the rgb color , starting with #{rgb}

  _ _ _ _ _ _ _
- # r r g g b b

red :- range => [ 00 -> ff ] -> #ff0000
green :- range => [ 00 -> ff ] -> #00ff00
blue :- range => [ 00 -> ff ] -> #0000ff


# Selector in CSS

Priority Order in CSS : If we want to make the change in element , id , class , what we write 
at the end , is having the highest priority.

1. Universal Selector -> *{} => (* -> asterisk || & -> ampersand )

When we want to change the effect on whole page then with the help of "*" we can change the things.

2. Element Selector -> h1 {}

When we want to bring the change to particular selector then we choose selector name.

3. Id Selector -> #myId{}

When we want to change the something for particular id , then we choose Id selector.

4. Class Selector -> .myclass{}

When we want to bring the change to the class then we choose the class Selector.

/*
    <h1 style="color: rgb(165, 82, 82)">Hello From Level 1 from CSS</h1>
    <h2>Avnish Kumar Singh</h2>
    <h3>Patna , Bihar </h3>
    <h1 id="id1">This for testing the property for the id </h1>
    <div class="nav-bar">
       <h1>This is for testing the class Name</h1>  
    </div>

*/

