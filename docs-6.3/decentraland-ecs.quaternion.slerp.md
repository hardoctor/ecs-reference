<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [decentraland-ecs](./decentraland-ecs.md) &gt; [Quaternion](./decentraland-ecs.quaternion.md) &gt; [Slerp](./decentraland-ecs.quaternion.slerp.md)

## Quaternion.Slerp() method

Interpolates between two quaternions

<b>Signature:</b>

```typescript
static Slerp(left: ReadOnlyQuaternion, right: ReadOnlyQuaternion, amount: number): Quaternion;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  left | <code>ReadOnlyQuaternion</code> | defines first quaternion |
|  right | <code>ReadOnlyQuaternion</code> | defines second quaternion |
|  amount | <code>number</code> | defines the gradient to use |

<b>Returns:</b>

`Quaternion`

the new interpolated quaternion
