background size are of 3 types


There are 4 type to give color in css 
1)normal way
     eg: red yellow pink

2)hex code 

3)rgb

4)hsl




### Hex code:- Now we will study about Hex code 

hex code 
we will take # tag
we have 3 fields #__ __ __ (they actually donot have gaps but i have given)
inside every field we have value from eiter 0-9 or A to F (value exisits from 00 to ff)
case 1: if you want red color in hex code 
        color:#ff0000
#thing is it accept rgb format 
same for green you can color :#00ff00 and for blue you can #0000ff

case 2 : getting black color 
color :#000000

case 3:for white
color :#ffffff



## remeber there is one more field in this which controls your colors opacity

opacity kee value bhee 00 to ff (by default it is ff so visible if in the 4tgh field you will add 00 then it will not be visible)


## rgb code 

red green blue 
->In rgb we have 3 fields 
->rgb(__,__,__)
all this 3 fields values varies from 0-255 just this much thing 
rgb(0, 0, 0) ----------> black
rgb(255,255,255) ----------> white

 color:rgba(0, 0, 0, 0)
 in this example the last digit value lies between 0 and 1
 # in rgba  (a denotes to brightness whose value lies between 0 and 1)
 example for this one is rgba(176,23,23,0.632)



 ---------------------------------------------------------------------------------------------------------

 ## hsl last mesthod to give the color 

 ## hsl (hue, saturation, lightness)
 hue value goes from 0-360
 saturation value goes from 0-100 %
 lightness value also goes from frpm 0-100 %

 eg: color : hsl(68,20% ,50%)
 if you want to add opacity its value lies between 
 you have to write 
 hsla(68, 20.00%, 50.00%, 0.69)
 if we will make the last one as 0  then it will show us nothing on the screen
 color: hsla(68, 20%, 50%, 0);


 ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


 GRADIENT : Combination of more than one color can be callled as Gradient 
 we have  3 type of gradient 
 1)linear gradient
 2)radial gradient 
 3)conic gradient 


 ## linear gradient

 body{
    background: linear-gradient(red,yellow);
    background-repeat:no-repeat ;

}

## important in the above one please check difference in the part of background attachement for scroll  and fixed one 


 