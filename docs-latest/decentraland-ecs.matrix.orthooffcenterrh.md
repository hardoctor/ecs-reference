<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [decentraland-ecs](./decentraland-ecs.md) &gt; [Matrix](./decentraland-ecs.matrix.md) &gt; [OrthoOffCenterRH](./decentraland-ecs.matrix.orthooffcenterrh.md)

## Matrix.OrthoOffCenterRH() method

Creates a right-handed orthographic projection matrix

<b>Signature:</b>

```typescript
static OrthoOffCenterRH(left: number, right: number, bottom: number, top: number, znear: number, zfar: number): Matrix;
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

<b>Returns:</b>

`Matrix`

a new matrix as a right-handed orthographic projection matrix

