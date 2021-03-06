<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [decentraland-ecs](./decentraland-ecs.md) &gt; [Vector4](./decentraland-ecs.vector4.md) &gt; [TransformNormalFromFloatsToRef](./decentraland-ecs.vector4.transformnormalfromfloatstoref.md)

## Vector4.TransformNormalFromFloatsToRef() method

Sets the given vector "result" with the result of the normal transformation by the given matrix of the given floats (x, y, z, w). This methods computes transformed normalized direction vectors only.

<b>Signature:</b>

```typescript
static TransformNormalFromFloatsToRef(x: number, y: number, z: number, w: number, transformation: Matrix, result: Vector4): void;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  x | <code>number</code> | value to transform |
|  y | <code>number</code> | value to transform |
|  z | <code>number</code> | value to transform |
|  w | <code>number</code> | value to transform |
|  transformation | <code>Matrix</code> | the transformation matrix to apply |
|  result | <code>Vector4</code> | the vector to store the results in |

<b>Returns:</b>

`void`

