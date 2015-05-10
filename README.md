# EllipticOrbit

`EllipticOrbit` is a JavaScript library for animating objects along elliptic orbits. 

Here's an example of how to instantiate an animated object:

```javascript
var planet1 = new EllipticOrbit('planet1',200,77,20,0,0,0);
planet1.start();
```

#### Options
`EllipticOrbit()` takes the following options:

```javascript
divId               //Div Identifier
semiMajorAxis       //Long Axis of Ellipse
semiMinorAxis       //Short Axis of Ellipse
xOffset             // x offset of planet from orbital path
yOffset             // y offset of planet from orbital path
tiltAngle           //Orbit Tilt
degree              //where planet starts on orbital path
```

#### Credit
[requestAnimationFrame algorithm](http://www.paulirish.com/2011/requestanimationframe-for-smart-animating/) created by Paul Irish

