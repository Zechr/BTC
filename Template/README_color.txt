Colors Used:
Off-White 253 246 227 #fdf6e3 
Dark-White 239 231 212 #efe7d4 
Mid-Gray2 98 123 131 #627b83
Mid-Gray3 129 148 150 #819496
Shade Gray 86 98 99 #566263
Off-Black 0 43 55 #002b37
Black 0 0 0 #000000
Magenta 219 67 130 #db4382
Red 226 58 40 #e23a28
Dark Red 176 44 31 #b02c1f
Green 68 155 76 #449b4c
Dark Green 57 130 64 #398240
Orange 211 79 2 #d34f02
Dark Orange 161 60 2 #a13c02
Yellow 233 193 0 #e9c100
Brown 180 101 15 #b4650f
Dark Brown 130 73 11 #82490b
Gold 157 145 0 #9d9100
Dark Gold 107 99 0 #6b6300
Blue 0 141 212 #008dd4
Dark Blue 0 107 161 #006ba1
Cyan 0 159 152 #009f98
Violet 102 117 197 #6675c5
Dark Violet 76 86 145 #4b5691


Title Bar:
Group Name: Off-White
Card Name: Off-White
Stat Circle Outline: Dark-White
Stat Circle Filling: Off-Black
Power Circle Bronze: Brown/Dark Brown 3 fold gradient
Power Circle Silver: Mid-Gray3/Shade Gray 3 fold gradient
Power Circle Gold: Gold/Dark Gold 3 fold gradient
Power Circle Text: Off-White
Range Icons Normal: Magenta
Range Icons Special: Cyan
Element Fire: Red
Element Wind: Green
Element Earth: Orange
Element Elec: Yellow
Element Water: Blue
Element Dark: Off-Black
Element Light: Off-White (switch Group Name and Card Name to Off-Black)
Element Mind: Violet
Element Null: Mid-Gray2
Effect Cards: Mid-Gray2 (unless they're colored Effect Cards, which are not yet in the game)
Drop Shadow: Black, X: 0, Y: 10, Blur Radius: 20

Essence Area:
Card: Off-White
Text: Black
Drop Shadow: Black, X: 0, Y: 10, Blur Radius: 20

Effect Area:
Card: Off-White
Text: Black
Drop Shadow: Black, X: 0, Y: 10, Blur Radius: 20

Both:
(S): Dark Red
(P): Dark Orange
(EP)/(RP)/(REP): Dark Gold
(T)/(OPT)/(OPYT)/(OPTiT)/(OPYTiT): Dark Green
(C): Dark Blue
(E): Dark Violet
Opacity: Default 50%, but if the text looks really bad due to the color of the image background, change it in increments of 10, such that it's between 30% and 70% inclusive. Try to make the opacity "look" the same as other cards with 50 taking into account the background color.

Notes:
Square icons in the range mean rook, diamond is bishop, circle is queen, and star is free.
Cyan means Jump for movement, and Projectile for attack range



Dual, Tri, etc, elements:
Formula where n is the number of elements, how to set up the gradient.
b is the solid color block size, g is the gradient color block size.
For example: A dual color would look like b-gg-b, and tri would be b-gg-b-gg-b.
There are n-1 gradient areas, and 2 gradient blocks per area.
So nb + 2*(n-1)g = 100 in terms of percent
We also want each gradient block to be 1/4 the size of the solid color block.
So b = 4g.
Solve this system of equations to get your gradient percents.
For now, I'll list up to n = 3.
n = 2
b = 40, g = 10, so do 40-20-40 solid-gradient-solid.
n = 3
b = 25, g = 6.25, so do 25-12.5-25-12.5 solid-gradient-solid-gradient-solid
