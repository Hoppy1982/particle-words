# Plan

Canvas animation with circling particles which move to form text.
Particle positions and speeds saved as ratios.
Responsive canvas recalculates it's size on window resize.

## Controls

- Text to render (string)
- Particles count (int)
- Particles holding pattern spawns (array {coords, hsl})
- Particle holding pattern min speed (canvas width / ms)
- Particle holding pattern max speed (canvas width / ms)
- Particle holding pattern acceleration (canvas width / ms^2)
- Particle holding pattern reset speed & acceleration interval (ms)
- Particle holding pattern initial speed & acceleration interval spread (quadratic curve)
- Particle holding pattern color changers (array {hsl, speed(quadratic curve), bounce angle randomness})
