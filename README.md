Lab3
====
##Schematic
![alt text][logo11]

[logo11]: /schematic.jpg

##Bad Code
```if clk'event and clk='1' then```

This code is unneccesary to look for a rising edge because there is already a function built in.
##Good Code
```if rising_edge((clk)) then```

Rising_egde is the same as the bad code above just much cleaner. It is better to use a pre defined word rather than creating code to do the same thing.

##Full B Fuctionality
<a href="https://www.youtube.com/watch?v=DMD15DSQARE" target="_blank"><img src="http://img.youtube.com/vi/MZO9sBdiirI/0.jpg" 
alt="8 bit 2s complement" width="240" height="180" border="10" /></a>


As seen in the video, I am demonstrating both more floors and inputting which floor to go to. This code is correct because I input values such as 2,3, and 7, all which are reach sequentially with the previous floors displayed. When returning to 0, the display shows each floor on its way down.
