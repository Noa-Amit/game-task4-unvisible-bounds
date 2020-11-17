# game-task4-unvisible-bounds
 
![WhatsApp Image 2020-11-17 at 11 29 07](https://user-images.githubusercontent.com/57709369/99372115-6bacf780-28c8-11eb-810e-f514f76faf4a.jpeg)

You can see in the left side that the laser and enemies doesn't pass the frame of the camera.
 
For this game we used a scene from class. We added prefab named "Limit" 

https://github.com/Noa-Amit/game-task4-unvisible-bounds/blob/main/Assets/Prefabs/Limit.prefab

Limit has collider, rigidbody and script "DestroyOtherOnTrigger" that destroy the object that hit him (the limit itself doesnt destroyed).

https://github.com/Noa-Amit/game-task4-unvisible-bounds/blob/main/Assets/Scripts/3-collisions/DestroyOtherOnTrigger.cs

In the game we put 2 Limits, upLimit that destroy laser and downLimit that distroy enemies.
