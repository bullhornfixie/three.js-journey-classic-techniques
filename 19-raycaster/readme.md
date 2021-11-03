# Three.js Journey

## Key Learning Points 

### What is Raycasting?
Raycasting means throwing a ray from the mouse position on the screen to 
the scene, this determines what object you want to click on if you have implemented it. 

### What is the Raycaster class in Three.js?
`new THREE.Raycaster()`


## Intersect Objects
- In geometry intersect is where two or more things pass or lie across eachother 
- Think of intersecting roads 
- `raycaster.intersectObject(object2)` means we want the ray to pass through this object 

Each item contains useful information 
- `distance` - distance between the origin of the ray and collision point 
- `face` - what face of the geometry was hit by the ray 
- `faceIndex` - the index of that face 
- `object` - what object is concerned by the collision 
- `point` - a Vector3 of the exact position of the collision 
- `uv` - the UV coordinates in that geometry 

## Uses of a Ray 
- Possibly a game where the player is shooting a laser and if objects intersect with laser, there is an event. 