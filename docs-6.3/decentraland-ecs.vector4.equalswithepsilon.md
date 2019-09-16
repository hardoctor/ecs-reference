<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [decentraland-ecs](./decentraland-ecs.md) &gt; [Vector4](./decentraland-ecs.vector4.md) &gt; [equalsWithEpsilon](./decentraland-ecs.vector4.equalswithepsilon.md)

## Vector4.equalsWithEpsilon() method

Boolean : True if the current Vector4 coordinates are each beneath the distance "epsilon" from the given vector ones.

<b>Signature:</b>

```typescript
equalsWithEpsilon(otherVector: ReadOnlyVector4, epsilon?: number): boolean;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  otherVector | <code>ReadOnlyVector4</code> | vector to compare against |
|  epsilon | <code>number</code> | (Default: very small number) |

<b>Returns:</b>

`boolean`

true if they are equal
