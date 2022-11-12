# Unity Portal Campsite Scene

This Unity project is a further iteration on the campsite scene that I built for the CMPM 121 course found [here](https://github.com/Gus700/UnityAdventureCampScene). This one expands the scene mainly by adding a portal object, lighting, and a day/night cycle.

#### [Video Submission](https://youtu.be/BXfJBLOnzM0)



#### 4 Lights

- An Area Light was used to illuminate the section in front of the portal.
- A Point Light was placed in the campfire game object.
- An Emissive Material was used on the portal object.
- Two dirrectional lights were used in the day and night cycle.

#### Lighting transition

- This was achieved by using the day and night cylce script that was discussed in class. This allows for the intensity and duration of the transition cycle.

#### Particle system 

- Two 2D particle systems were used for the campfire effect, one for the smoke and one for the fire particles
- A 3D mesh particle system was used in conjunction with the portal, while a 2D system was used at first, the spinning rotation worked better with the 3D particles.
