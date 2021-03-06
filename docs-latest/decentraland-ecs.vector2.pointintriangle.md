<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [decentraland-ecs](./decentraland-ecs.md) &gt; [Vector2](./decentraland-ecs.vector2.md) &gt; [PointInTriangle](./decentraland-ecs.vector2.pointintriangle.md)

## Vector2.PointInTriangle() method

Determines if a given vector is included in a triangle

<b>Signature:</b>

```typescript
static PointInTriangle(p: ReadOnlyVector2, p0: ReadOnlyVector2, p1: ReadOnlyVector2, p2: ReadOnlyVector2): boolean;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  p | <code>ReadOnlyVector2</code> | defines the vector to test |
|  p0 | <code>ReadOnlyVector2</code> | defines 1st triangle point |
|  p1 | <code>ReadOnlyVector2</code> | defines 2nd triangle point |
|  p2 | <code>ReadOnlyVector2</code> | defines 3rd triangle point |

<b>Returns:</b>

`boolean`

true if the point "p" is in the triangle defined by the vertors "p0", "p1", "p2"

