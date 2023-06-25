# Unit in CSS

Relative Units 
---------------------------------------------------------------------------------------------------

1. Percentage ( % ) :- Size as relative to an element parent object 

If we have div(1) and div(2) , then if we set width:33% to div(2) then it taking 33% size of div(1).

2. em :- 

-> It takes the font-size releative to the parent size , if our parent size is of 10px and we 
put any of the child div with font-size: 2em , then it takes twice the size of the parent div1 
now size of div2 is 20px. [ 10px * 2rm = 20px ].

-> If we take the width to be 6em , then it take respective to font-size of the parent div1 which 
is 10px*6= 60px.


3. rem :-

-> On the basis of the root element , relative size is going to be fixed .

4. vh ( viewport height ) : Relative to 1% of viewport height.

5. vw ( viewport width ) : Relative to 1% of viewport width.
---------------------------------------------------------------------------------------------------



# Position 

Position CSS property sets how an element is positioned in a document.

position : static / relative / absolute / fixed / sticky 

1. static :- default position ( top ,right,bottom,left,z-index has no effect ).
2. relative :- Element is Relative to itself ( top , right , bottom , left , z-index will work )
3. absolute :- positioned relative to its closet positioned ancestor.
4. fixed :- positioned relative to its browser (remove from flow).
5. sticky :- positioned based on user scroll's position. ( once we reach to the right position 
during scroll then the box is going to be fixed. )


z-index 

It decide the stack level of element ( Overlapping element with a larger z-index cover those with smaller ones.)

z-index: auto(0)
z-index: 1/2/...
z-index: -1/-2/-3/....


#b1{
    position: static;
    background-color: green;
    /* Its the fixed , no change on left ,right , top and bottom is going to made */
}

#b2{
    position: relative;
    background-color: red;
    left:1000px;

}

#b3{
    background-color: pink;
    position: absolute;
    top: 20px;
}

#b4{
    position: fixed;
    bottom: 0px;
}

# Background Size

background-size: cover/contains/auto

1. cover :- Its cover the background area fully in fitted manner 
2. contains :- It insert the image fully , if space left-over then the space is shown to user.
3. auto :- It will overflow the size of the image inside the box.


# Background Image

#b1{
    background-image: url("bridge.jpg");
    background-size: cover;
}




