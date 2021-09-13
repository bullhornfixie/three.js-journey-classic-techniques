# 17 Particles 

## Key Learning Points 
- Custom geometry using `BufferGeometry()`
- `alphaTest` value between 0 and 1, enables WebGL to know when not to render the pixel 
- `additiveBlending` color of two objects are added to each other - e.g. becomes brighter 
- Trigonometry branch of maths that studies relationships between side lengths and angles of triangles
- `ElpasedTime / 2` reduces speed of animation by half
- Each Vertex has 3 values - x, y, z 

### Creating Random Colors 
- A color is composed of RGB
- Using a `for loop` to create random colors 
- R has a range of 0-1
- G has a range of 0-1
- B has a range of 0-1
- When each element has a different range, it creates a different color
- Turn off base color when using random colors

### Attributes 
- `setAttribute()` 
- On particlesGeometry we have set two new attributes `color` and `position`
- Attributes can be checked by `console.log(particlesGeometry.attributes`)

## Resources 
[Particle Pack](https://www.kenney.nl/assets/particle-pack)