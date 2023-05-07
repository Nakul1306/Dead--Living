# Dead Living
A Unity based First Person Shooter game with Normal and Zombie modes built with Unity terrain using raycasting for shooting and the core mechanics you'd expect in an FPS with available item pick-ups. Enemies use AI navigation and precise pathfinding to chase down the player.

Implemented my algorithms for AI pathfinding, navigation, raycasting, and other mechanics. Online free assets were mostly used excluding some which've been self-designed customly.


###### Note 
Developed with Unity 2020.3.24f1.

## Game Logic and Functionality

- Hunt down all the enemies in the terrain by finding them to win before timer ends.
- The Enemies patrols at  waypoints until it detects the player as a target.
- If the Player enters the enemies perspective, the enemies starts to chasing the player.
- The Enemy starts shooting when it close enough to attack while chasing.
- Enemies health will recharge after heeling time ..if left unattacked.
- Headshot or Eyeshot will give extra damage to enemies.
- Ammo pickups for guns and medikit pickup for the players health are available at certain places in the map.
- Two guns are available, Pistol, AK-47 (have different attack range) and grenades with some pre-loaded bullets. To change between guns, use the scroller of your mouse.

  

## Controls ##

| Action          | Desktop PC              |
| --------------- | ----------------------- |
| Move Forward    | W                       |
| Move Left       | A                       |
| Move Backward   | S                       |
| Move Right      | D                       |
| Jump            |  space                  |
| Run             | Left Shift(hold)        |
| Shoot           | Mouse Left Button       |
| Aim             | Mouse Right Button      |
| Previous Weapon | Q *or* Mouse Wheel Up   |
| Next Weapon     | Q *or* Mouse Wheel Down |
| Reload          | R (when near ammo box)  |
| Health Recharge |Capslock (near medikit)  |
|Throw Grenade    |  G                      |

