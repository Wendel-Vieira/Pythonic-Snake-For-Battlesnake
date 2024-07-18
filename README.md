![pythonic snake gif](https://github.com/user-attachments/assets/bda4a40e-13c7-4557-ad30-21e2b7545c21)

This code is very important to me, as it was my introduction to the programming world.  
I worked heavily on it for two months and was able to get top 60 with this version.

Key Features:  
*A Star Pathfinding Algorithm  
*Flood Fill Algorithm  
*Collision Detection  
*Console Board Representation  

Here is an example of how the board is represented on the console;  

![board1](https://github.com/user-attachments/assets/d0acc1d9-22ca-42e5-a6a4-5d843a1a3dfc)  
Each snake has it own colors, with the player snake always being blue by default. 
The '@' represents the body of a snake, and the '3' it's head.  

Each free tile is represented as a dot, and it's color is determined by the snake whom can get to that tile first.  
White dots are tiles where no snake can get to them first, so no snake "has" it.  
'F' represents food available on the board, and as you can deduct, it's color is also dependent on whom can get to it before other snakes.  
All this is done using information gotten from the Flood Fill Algo.

