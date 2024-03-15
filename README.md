# Space Physics for Unity
A 2D physics engine that simulates the behavior of bodies in space. It is designed for use in video games and provides features to facilitate their creation. 
The engine does not support a large number of objects simulated simultaneously, but was designed to allow free deactivation and activation of objects at runtime, each time they do not affect the player.
The project was originally created for the game demo Invade Space. The package is under constant development, but it's current form is fully stable and functional.
# Components
- PhysicsProperty
  - should be attached to any object that will be subjected to physics interactions.
  - Inspector provides all the options needed to set body parameters.
- PhysicsController
  - It should always be present at the scene and remain active whenever physics interactions should occur.
  - Inspector provides access to variables to adjust global physics values.
# Examples
The folder contains a sample script for celestial body that uses the functions and signals of PhysicsProperty.
The methods of this class assume that the size of the object sprites is normalized to one unit.
Example structure of the Prefabricate for the script entity:
