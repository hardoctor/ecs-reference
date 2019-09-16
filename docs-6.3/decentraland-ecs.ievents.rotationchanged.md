<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [decentraland-ecs](./decentraland-ecs.md) &gt; [IEvents](./decentraland-ecs.ievents.md) &gt; [rotationChanged](./decentraland-ecs.ievents.rotationchanged.md)

## IEvents.rotationChanged property

`rotationChanged` is triggered when the rotation of the camera changes. This event is throttled to 10 times per second.

<b>Signature:</b>

```typescript
rotationChanged: {
        rotation: ReadOnlyVector3;
        quaternion: ReadOnlyQuaternion;
    };
```