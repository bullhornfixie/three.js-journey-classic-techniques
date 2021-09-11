# 16 Haunted House 

## Key Learning Points 
- Constructing a house from shapes 
- THREE.js has a Fog class 
- Opaque edges of scene by using fog color in renderer 
- Adding brick texture to house 

### Point Light 
- [Three.js class info](https://threejs.org/docs/#api/en/lights/PointLight)
- Use orange for a warm point light `'#ff7d46'`

### Door Texture 
- Import textures using `TextureLoader`
- Change `color:` to `map:` in MeshStandardMaterial 
- Need to use `transparent:` prop when using `alphaMap:`
- `aoMap` stands for ambient occlusion

## Resources 