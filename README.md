# 3dPersonController

Final scripts and object setup of my PlayerMovementUnity project.

It was meant to be a practise and research project (it still kind off is), but it got a little out of hand, so I thought I would share it so you can learn from it too.
If you have any Tips, tops, commentary or request you can contact me via Discord (Grote Smurf#9571) or adress an issue.
Here is the link to the full unity project. You are able to find these files in Assets/Scene3.
	https://github.com/ToonSti/PlayerMovementUnity

---
Best Features:
  - 3d Person controller
  - 3d Person following and camera that does not clip

---
Containing:
  - A file containing all used sources with links called "Sources.txt"
  - A file containing how to setup the Player and Camera and hwo to configure the Inspector called "Setup.txt".
  - Commentary on the code explaining what it does or what its function is
  
---
Functions:
  - SmoothDamp and normalized 3d person player movement
  - Aircontrol option
  - Advanced Ground Check
  - Player animations
  - Character Controller
  - Controllable and following Camera without Cinemachine
  - Groundcheck working on ledges and slopelimit
  - Sprinting and Crouching
  
---
Note:
  - Crouching changes the transformheight, I could change it so it only changes the collider, but this works best for me. If I ever decide to change this, I will apply it to this controller.