# Super-Mario-Game

Uploading video editing 2.mp4

### [To Watch the full video](https://drive.google.com/drive/folders/1ioNYgcXxv9G3Xt1A2pc9F6td4rwH9zJ9?usp=sharing)

# Playing The Game:
- The game consists of 3 levels with 4 lives, which are  in three different worlds.
- If you lost all your lives or exceed the time, you will lose the game .

- You can play the game manually using Keyboard:
  Controlling mario  --->>> Press 'right key' to move RIGHT and Press 'left key' to move LEFT and Press 'z' or 'Z' key to jump.
- You can also play the game using AI model as their will be a camera to detect your movements and apply it to the game.

- You can jump to avoid or kill enemies and to take coins, The more coins you claim, the higher the score you get.

- It can be played by only one player.

# Controls:
<img width="474" alt="controls" src="https://github.com/Mennatullah-Elsahy/Super-Mario-Game/assets/83369752/860c8c78-f233-4615-983e-6b2550d2e790">


## Key Sounds:
- Press 's' or 'S' key for sounds OFF.
- Press 'p' or 'P' key for sounds ON.

## Quitting The Game:
- Press 'Esc' key to exit the game.

# Important Files:
## gamelib:
- The main code of the game which contain main functions:
-  clamp_off: adjust the position of the sprite based on which side it collided with another sprit.
-  Collidable: simulation to detect and handle collisions between objects.
-  update: updating the player's animation, movement, and various timers and attributes.
-  class Platform: represents a basic platform and has the images.
## data:
- contain the images,sounds and background used in the game.
## main:
- importing the libraries
- setting up the mediapipe instance
- extracting the landmarks:
        - if x coordinate passes left threshold move left
        - if x coordinate passes right threshold move right
        - if y coordinate passes aboe the top threshold move up



