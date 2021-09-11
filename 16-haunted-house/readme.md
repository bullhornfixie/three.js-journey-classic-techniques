# 16 Haunted House 

## Key Learning Points 
- Constructing a house from shapes 
- THREE.js has a Fog class 
- Opaque edges of scene by using fog color in renderer 
- Adding brick texture to house 
- Adding grass 
- Using a for loop to create a circle of 3D objects
- Creating a rotating light

### Point Light 
- [Three.js class info](https://threejs.org/docs/#api/en/lights/PointLight)
- Use orange for a warm point light `'#ff7d46'`

### Door Texture 
- Import textures using `TextureLoader`
- Change `color:` to `map:` in MeshStandardMaterial 
- Need to use `transparent:` prop when using `alphaMap:`
- `aoMap` stands for ambient occlusion

### How Textures Work 
- The geometry defines a mesh's shape 
- The material defines various surface properties of the mesh - e.g. how it reacts to light 
- `geometry` and `material` control appearance of the mesh when we come to render scene 
- `wrapS` defines how texture is wrapped `horizantally` and responds to U in UV mapping
= `wrapT` defines how texture is wrapped `vertically` 

### Material 
- Materials have many paramters (color, roughness, metalness, opacity etc)
- These materials are applied uniformly over entire surface of the mesh 
- If we change `.roughness` whole material becomes rougher 
- `texture mapping` is where take an image and stretch it over surface of 3D object 
- UV mapping allows us to create a connection between points on the geometry


## Resources 
- [Guide to Textures](https://discoverthreejs.com/book/first-steps/textures-intro/)