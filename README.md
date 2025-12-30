Project Overview
A high-speed traversal and combat prototype built in Unreal Engine 5, recreating the core movement mechanics from Attack on Titan. This project focuses on physics-based player movement, enemy AI behavior, and rapid traversal systems.

🛠 Key Features Implemented
Grapple Hook Physics (ODM Gear):

Implemented a physics-based launch system using LaunchCharacter and Vector Math.

Dynamic targeting using Line Traces to identify grapple points on walls/Titans.

Verticality logic to boost player height during swings.

Titan AI Behavior:

Enemy AI that actively tracks the player's location.

"Chase and Kill" mechanic: The Titan follows the player and triggers a "Game Over" state upon collision.

High-Velocity Movement:

Customized character physics to support high-speed aerial maneuvering.

Logic to override standard mass/friction for instant velocity changes.

Camera System:

Dynamic camera positioning to handle high-speed vertical gameplay without clipping.

🎮 Controls
W, A, S, D: Movement

Space: Jump

Q: Fire Grapple / Launch (Hold to fly towards target)

Mouse: Aim

📂 Technical Details
Engine: Unreal Engine 5

Language: Blueprints (Visual Scripting)

Core Logic: Located in BP_ThirdPersonCharacter (Movement) and Titan_AI (Enemy Logic).
