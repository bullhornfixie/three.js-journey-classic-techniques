# Three.js Journey

## Key Learning Points 
- How to cast a Ray in a scene
- A ray is a line with an endpoint and goes indefinitely in one direction 
- Three has a Raycast Class `new THREE.Raycaster()`
- It requires an `origin` and `direction` which can be achieved by using `Vector3 class`
- Three has a Gridhelper Class `new THREE.GridHelper(9, 9)`

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