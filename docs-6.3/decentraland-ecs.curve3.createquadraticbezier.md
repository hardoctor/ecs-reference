<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [decentraland-ecs](./decentraland-ecs.md) &gt; [Curve3](./decentraland-ecs.curve3.md) &gt; [CreateQuadraticBezier](./decentraland-ecs.curve3.createquadraticbezier.md)

## Curve3.CreateQuadraticBezier() method

Returns a Curve3 object along a Quadratic Bezier curve : http://doc.babylonjs.com/tutorials/How\_to\_use\_Curve3\#quadratic-bezier-curve

<b>Signature:</b>

```typescript
static CreateQuadraticBezier(v0: Vector3, v1: Vector3, v2: Vector3, nbPoints: number): Curve3;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  v0 | <code>Vector3</code> | (Vector3) the origin point of the Quadratic Bezier |
|  v1 | <code>Vector3</code> | (Vector3) the control point |
|  v2 | <code>Vector3</code> | (Vector3) the end point of the Quadratic Bezier |
|  nbPoints | <code>number</code> | (integer) the wanted number of points in the curve |

<b>Returns:</b>

`Curve3`

the created Curve3
