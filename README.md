
# City Tour

CityTour is a Unity3D project that allows users to navigate and explore its environment. Utilizing intuitive mouse and keyboard controls, player can navigate throughout the city, interacting with buildings and landmarks along the way.




## Demo

click to watch the demo video:
https://clipchamp.com/watch/vT0kw7pOKy4
## Documentation


[Unity-Manual: Unity user manual](https://docs.unity3d.com/Manual/index.html)


## Features/Functionalities used

1. Character Controller: A CharacterController allows you to easily do movement constrained by collisions without having to deal with a rigidbody.
<img width="425" alt="Screenshot1" src="https://github.com/sriimalya/CityTour/assets/125035993/faeb0ca9-044c-411e-b264-5ea4f04d4b73">
2. PlayerController.cs script:
to control the movement speed of player in x(horizontal) and y(vertical) direction
to keep the player grounded, gravity variable is used using **Input Manager**
<img width="415" alt="Screenshot2" src="https://github.com/sriimalya/CityTour/assets/125035993/7f3a9d92-91ea-4237-9a67-faaa07bb612d">
3. Fixing position of **Main Camera same as the player** (also make it the child of player/object)
4. Colliders: to define the shape of game objects for the purposes of physical collision between player and other game objects
5. MouseHandler.cs script:
to control rotation of player in x and y- direction
<img width="416" alt="Screenshot3" src="https://github.com/sriimalya/CityTour/assets/125035993/bc8aa474-b41d-46c2-acd8-3b9f2dd20c75">







