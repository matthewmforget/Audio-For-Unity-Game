**Unity Game with Enhanced Audio**

**Overview**
This project is part of EECS 4462: Digital Audio, Fall 2023 and focuses on adding sound to a Unity 3D game. The game integrates music, sound effects, and dialogue/narration, providing a comprehensive audio experience. The audio has been enhanced to demonstrate key digital audio concepts such as 3D and 2D sound, reverb, randomization, ducking, and dynamic state-based sound changes.

**Features**
Three Audio Aspects:
The project includes background music, various sound effects, and narration/dialogue recorded using my voice.
3D and 2D Sound:
3D sound is implemented so that audio volume changes based on the player's position relative to sound sources.
2D sound remains constant in volume regardless of position.
Dynamic Reverb Settings:
Reverb settings change dynamically when the player moves between different rooms. For instance, when entering a new area, the reverb changes to reflect the environment.
Randomization:
Repeated sound effects (e.g., laser shots) have randomized pitch shifts to avoid monotony and make each instance sound unique.
Background Music Transitions:
The background music changes smoothly when the player enters a new room using fade in/out transitions for a seamless experience.
Ducking:
"Ducking" is used to lower the volume of the background music during dialogue/narration to ensure the spoken content is clearly audible.
State-Based Sound Effects:
One sound effect changes based on the player's state. For instance, the footstep sound switches when the player walks on different surfaces, such as water.

**How to Run the Project**
Prerequisites:

Unity Editor: Download and install Unity Hub and the appropriate Unity version for this project.
A system capable of running Unity 3D games.
Steps to Run the Game:

Clone the Repository:
Download or clone the Unity project to your local machine:
bash:

git clone https://github.com/matthewmforget/Audio-For-Unity-Game.git
Open the Project in Unity:
Launch Unity Hub and select Open Project.
Navigate to the cloned project folder and open it in Unity.
Play the Game:
Once the project is loaded, press the Play button in Unity to run the game and experience the integrated audio.
Move through the different rooms in the game to hear the changes in reverb and background music.
Listen for randomized sound effects during repeated actions (e.g., laser shots).
Pay attention to "ducking" when dialogue occurs, and observe how footstep sounds change depending on the player's environment.
Key Controls:

Movement: Use the arrow keys or WASD to move around the scene.
Interact: Use the mouse to interact with objects or trigger certain actions (if applicable).
Audio Features in Detail
3D and 2D Sound:
3D Sound: As you move closer or farther from sound sources, the volume dynamically changes to reflect your proximity to the source.
2D Sound: Sound effects that are meant to be constant, such as background narration or non-diegetic sounds, maintain their volume regardless of player movement.
Dynamic Reverb:
The reverb settings adjust as the player enters different areas of the game. For example, moving from a small room to a larger hall will change the reverb to reflect a larger space.
Randomization:
To keep repetitive sounds interesting, sound effects such as laser shots from enemies have random pitch shifts, ensuring each shot sounds slightly different.
Music Transition:
When entering different rooms, the background music fades in and out smoothly, ensuring a seamless transition between different tracks or ambient sounds.
Ducking:
During dialogue, the background music is automatically lowered so that the narration or dialogue can be heard clearly without being overpowered by the music.
State-Based Sound Changes:
For example, when the player starts walking on water, the footstep sound changes from a standard "step" sound to a "splash" sound, enhancing immersion.
