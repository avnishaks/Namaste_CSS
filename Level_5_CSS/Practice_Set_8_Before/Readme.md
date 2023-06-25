Level 5 starting 
Start Time :-> 4:47:48
https://youtu.be/ESnrn1kAD4E

# A. Transitions 
--------------------------------------------------
Transitions enable you to define the transition between two state of element

* transition-property :- property you want to transition (font-size,width,etc)
* transition-duration :- 2s/4ms..
* transition-timing-functions :- ease-in/ease-out/linear/steps..
* transition-dealy :- 2s/4ms..

div{
    height: 400px;
    width: 400px;
    background-color: red;
    border: 5px solid green;
    transition-property: all;
    transition-duration: 4s;
    transition-timing-function: steps(10);
    transition-delay: 5s;
}


short-hand for the Transition Property:- 

transition : property name | duration | timing-function | dealy
transition: all 4s 10 5s



# B. CSS Transform 
--------------------------------------------------
# 1. rotate
Used to apply 2D & 3D transformation to an element

transform: rotate(45deg)

rotate:45deg
rotateX:45deg
rotateY:45deg
rotateZ:45deg

# 2. scale

It is used to increase or decrease the size of the text.

transform:scale(1,2) :-> remain same in X axis and double in Y axis

transform:scale(2) :-> double in whole direction x,y axis

scaleX(2) / scaleY(2) :-> width of X and Y axis changes 

# 3. translate

Move in the direction of axis for X and Y or in XY directions.

translate(20px,50px)
translateX(20px)
translateY(40px)

# 4. Skew 

To bring the representation of the image in the rohmbous form.
transform:skew(30deg)


# C. Animations
--------------------------------------------------

To Animate the CSS elements

Syntax :- 

@keyframes colorAnimate {
    from {background-color: red}
    to {background-color: aquamarine}    
}

Animated Properties :- 

1. animation-name
2. animation-duration
3. animation-timing-function
4. animation-delay
5. animation-iteration-count
6. animation-direction

Animation Directions:-

animation-direction: normal [ Normal Animation goes in define directions ]
animation-direction: reverse [ Animation goes in opposite of define directions ]
animation-direction: alternate [ SHM motion is performing for the Animation ]
animation-direction: alternate-re [ Repeat mode for the Animation is ON ]


Animation Short Hand

animation: name | duration | timing-functions | delay | iteration-count | directions

animation: colorAnimate 1s ease-in 1s infinite alternate-reverse;


% in Animation


@keyframes colorAnimate {
    from {transform:translateX(40px)}
    to {transform:translateX(-100px)}
    0% {
        background-color: greenyellow;
    }    
    50%{
        background-color: orange;
    }
    100%{
        background-color: brown;
    }
}