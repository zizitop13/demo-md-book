# Motion in space

A spacecraft does not need continuous thrust to maintain its velocity in an inertial frame. Gravity and other external forces can still change its trajectory.

## Acceleration

For constant acceleration along a straight line, starting at rest:

$$
v=at,\qquad s=\frac{1}{2}at^2
$$

At $1\,\mathrm{m/s^2}$ for ten seconds, the spacecraft gains 10 m/s and travels 50 m.

<!-- pagebreak -->

## A simple calculation

```typescript
function distance(acceleration: number, seconds: number): number {
  return 0.5 * acceleration * seconds ** 2;
}
```

This model ignores gravity and assumes constant acceleration.
