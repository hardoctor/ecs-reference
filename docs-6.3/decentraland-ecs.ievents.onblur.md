<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [decentraland-ecs](./decentraland-ecs.md) &gt; [IEvents](./decentraland-ecs.ievents.md) &gt; [onBlur](./decentraland-ecs.ievents.onblur.md)

## IEvents.onBlur property

`onBlur` is triggered when an entity loses its focus. Dispatched by the `ui-input` and `ui-password` entities when the value is changed. It triggers a callback.

Notice: Only entities with ID will be listening for click events.

<b>Signature:</b>

```typescript
onBlur: {
        entityId: string;
        pointerId: number;
    };
```