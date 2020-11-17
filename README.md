# game-task4-unvisible-bounds
 
![WhatsApp Image 2020-11-17 at 11 29 07](https://user-images.githubusercontent.com/57709369/99372115-6bacf780-28c8-11eb-810e-f514f76faf4a.jpeg)

You can see in the left side that the laser and enemies doesn't pass the frame of the camera.
 
 The game has 3 main objects:
 
   1. player- has collider and rigidbody. Player also has a scripts that made him move, killed when it hit enemy, and shoot laser.
      https://github.com/Noa-Amit/game-task4-unvisible-bounds/blob/main/Assets/Scripts/1-movers/KeyboardMover.cs
      
      https://github.com/Noa-Amit/game-task4-unvisible-bounds/blob/main/Assets/Scripts/3-collisions/DestroyOnTrigger2D.cs
      
      https://github.com/Noa-Amit/game-task4-unvisible-bounds/blob/main/Assets/Scripts/2-spawners/LaserShooter.cs
      
   
   2. enemySpawner- a prefab that spawn the enemies.
     https://github.com/Noa-Amit/game-task4-unvisible-bounds/blob/main/Assets/Prefabs/EnemySpawner.prefab
   
   3. Limit- a prefab that has collider and rigidbody. When a specific object trigger the limit, limit destroy it.
     https://github.com/Noa-Amit/game-task4-unvisible-bounds/blob/main/Assets/Prefabs/Limit.prefab
     The script https://github.com/Noa-Amit/game-task4-unvisible-bounds/blob/main/Assets/Scripts/3-collisions/DestroyOtherOnTrigger.cs
     
     we put 2 limites in the game. The up limit destroy laser and the down limit destroy enemy.
