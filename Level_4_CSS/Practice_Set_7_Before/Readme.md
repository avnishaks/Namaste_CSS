# Media Queries

It helps to create the responsive website.

-> change shown at exact 600px
@media(width:600px){
    div{
        background-color:red;
    }
}

-> change shown b/w the range of 200px to 300px
@media (min-width:200px) and (max-width:300px){
    div{
        background-color: brown;
    }
}

-> change shown b/w the range of 0 - max_range
@media(max-width:400px){
    div{
        background-color: red;
    }
}

-> change shown b/w the range of min_range - infinity
@media(min-width:600px){
    div{
        background-color: green;
    }
}

