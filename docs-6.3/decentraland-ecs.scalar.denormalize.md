<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [decentraland-ecs](./decentraland-ecs.md) &gt; [Scalar](./decentraland-ecs.scalar.md) &gt; [Denormalize](./decentraland-ecs.scalar.denormalize.md)

## Scalar.Denormalize() method

Denormalize the value from 0.0 and 1.0 using min and max values

<b>Signature:</b>

```typescript
static Denormalize(normalized: number, min: number, max: number): number;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  normalized | <code>number</code> | value to denormalize |
|  min | <code>number</code> | max to denormalize between |
|  max | <code>number</code> | min to denormalize between |

<b>Returns:</b>

`number`

the denormalized value
