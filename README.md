# in-class-activities-finished
## Devlogs
### W1
I managed to get familiar with basic Unity fundamentals. I learned to manipulate game objects and navigate the UI of unity itself. 
I also learned how to set up future builds for release on Itch.io. 
The resulting product is a cat on a new start platform, the cat game object can now move, with an increased turning speed. And finally, the camera has been shifted into the first person perspective.

### W2
r,g, and b are floats because they contain decimals. They're not whole numbers or true/false statements or dialogue text. 
_bounce is a whole number/int because it's counting total bounces. 
it was a compiler error, essentially noting that a semicolon was missing from the line. 

### W3
Table 7 Discussion
2. 
Y= Friendship level X=Boolean True/false 
output is a string
Continuing with the theme of food, A class is the recipe, a component is the cooked dish, the member variables are the ingredients and the flavor choices, and 
the methods are the cooking steps/actions.
The balls get bright because the multipler stacks on every bounce instead of resetting, compounding the color values beyond what's normal.


### W4
Table 7
Line 5 makes the movement speed editable in the unity inspector so you can tune it on the fly. 
Line 22 gets the player's vertical input and multiplies it by the move speed and time delta time so movement isn't effected by the framerate?
Line 25 idk tbh. I think this is for like moving a gameObject.

I chose to make the cat and the ball rigid bodies because they interact more with the world and each other. I gave the goal box a IsTrigger because I figured the goal would just 
be a lil threshold to detect the ball. 

### W5
Table 7
Activity 1
Q: How do vectors relate to the "Transform" component in Unity?
A: Vectors basically describe direction and distance in like a 3D space
Transform just stores a thing's position, rottion, and scale as vectors.
Activity 2
Planning Phase
Member Variables: _target _agent
Method: Start()
Start() opens and use getcomponent<NavMeshAgent>() then assign the agent. 
then use _agent.SetDestination(_Target.position) and HOPEFULLY the thing moves.
### W6
---

### W7
https://docs.google.com/document/d/1XzvvYQoA_vMfFCcPY22iyql93NnrTL6rIcFjK30dwm8/edit?usp=sharing
Role: Environment/Gameplay

The original code used Vector3.forward so no matter the orientation, the muskrat would move the same in 
world space rather than moving the direction it was rotated to face. Transform.forward makes it move relative to direction.

## Open-Source Assets
### W1
- Animals: https://assetstore.unity.com/packages/3d/characters/animals/animals-free-animated-low-poly-3d-models-260727 
- Low-poly environment: https://assetstore.unity.com/packages/3d/environments/landscapes/low-poly-simple-nature-pack-162153 