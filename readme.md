## Description

2D-vector operations: addition, subtraction, normalization, rotation etc.

The vectors are immutable. Every operation returns new instance.

## Installation

```bash
npm i @minogin/vector
```

## Usage

Add the following line to your project:

```javascript
import Vector from '@minogin/vector'
```

## Example

##### Addition
```javascript
let a = new Vector(10, 20)  // Calculate
let b = new Vector(30, 40)
let c = a.add(b)

console.log('x: ' + c.x)    // Use
console.log('y: ' + c.y)
```

##### Rotation
```javascript
let a = new Vector(10, 20)
let b = a.rotate(Vector.rad(30))    // Degrees to radians conversion 
```

## License

[ISC](https://opensource.org/licenses/ISC)
