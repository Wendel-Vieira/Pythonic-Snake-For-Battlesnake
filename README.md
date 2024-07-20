![349844627-bda4a40e-13c7-4557-ad30-21e2b7545c21](https://github.com/user-attachments/assets/a0f64758-c22a-4727-a6d7-2b4f48e584ac)  

This code is very important to me, since it was my introduction to the programming world.  
I worked heavily on it for two months and was able to get top 60 with this version.

Key Features:  
*A Star Pathfinding Algorithm  
*Flood Fill Algorithm  
*Collision Detection  
*Console Board Representation  

Here is an example of how the board is represented on the console;  
![snakey](https://github.com/user-attachments/assets/131bc56e-0ff1-40d0-a1fe-8dc4ef8ca703)  

Each snake has it own colors, with the player snake always being blue by default. 
The '@' represents the body of a snake, and the '3' it's head.  

Each free tile is represented as a dot, and it's color is determined by the snake whom can get to that tile first.  
White dots are tiles where no snake can get to them first, so no snake "has" it.  
'F' represents food available on the board, and as you can deduct, it's color is also dependent on whom can get to it before other snakes.  
All this is done using information gotten from the Flood Fill Algo.


