<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [decentraland-ecs](./decentraland-ecs.md) &gt; [Matrix](./decentraland-ecs.matrix.md) &gt; [OrthoOffCenterLHToRef](./decentraland-ecs.matrix.orthooffcenterlhtoref.md)

## Matrix.OrthoOffCenterLHToRef() method

Stores a left-handed orthographic projection into a given matrix

<b>Signature:</b>

```typescript
static OrthoOffCenterLHToRef(left: number, right: number, bottom: number, top: number, znear: number, zfar: number, result: Matrix): void;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  left | <code>number</code> | defines the viewport left coordinate |
|  right | <code>number</code> | defines the viewport right coordinate |
|  bottom | <code>number</code> | defines the viewport bottom coordinate |
|  top | <code>number</code> | defines the viewport top coordinate |
|  znear | <code>number</code> | defines the near clip plane |
|  zfar | <code>number</code> | defines the far clip plane |
|  result | <code>Matrix</code> | defines the target matrix |

<b>Returns:</b>

`void`
