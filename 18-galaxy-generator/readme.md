# 18 Galaxy Generator 

## Key Learning Points 
- `.onFinishChange()`
- use const when the variable does not change 
- use let when the varibale is going to change 
- `dispose()` disposes the object memory - call this when you want `BufferGeometry` removed while app is running 
- in classic geometry, `radius` is center of a circle to its perimiter 
- use () in calculations for calculation priority 
- a full circle is pi * 2 
- `Math.random() - 0.5` gives a range from -0.5 to +0.5
- `.lerp` is used to blend colors

### Let vs Const 
Turns out, const is almost exactly the same as let . However, the only difference is that once you've assigned a value to a variable using const , you can't reassign it to a new value. ... The take away above is that variables declared with let can be re-assigned, but variables declared with const can't be.