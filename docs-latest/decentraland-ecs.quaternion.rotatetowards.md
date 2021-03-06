<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [decentraland-ecs](./decentraland-ecs.md) &gt; [Quaternion](./decentraland-ecs.quaternion.md) &gt; [RotateTowards](./decentraland-ecs.quaternion.rotatetowards.md)

## Quaternion.RotateTowards() method

The from quaternion is rotated towards to by an angular step of maxDegreesDelta.

<b>Signature:</b>

```typescript
static RotateTowards(from: ReadOnlyQuaternion, to: Quaternion, maxDegreesDelta: number): Quaternion;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  from | <code>ReadOnlyQuaternion</code> | defines the first quaternion |
|  to | <code>Quaternion</code> | defines the second quaternion |
|  maxDegreesDelta | <code>number</code> | the interval step |

<b>Returns:</b>

`Quaternion`

