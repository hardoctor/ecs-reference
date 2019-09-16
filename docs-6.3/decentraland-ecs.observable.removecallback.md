<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [decentraland-ecs](./decentraland-ecs.md) &gt; [Observable](./decentraland-ecs.observable.md) &gt; [removeCallback](./decentraland-ecs.observable.removecallback.md)

## Observable.removeCallback() method

Remove a callback from the Observable object

<b>Signature:</b>

```typescript
removeCallback(callback: (eventData: T, eventState: ObserverEventState) => void, scope?: any): boolean;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  callback | <code>(eventData: T, eventState: ObserverEventState) =&gt; void</code> | the callback to remove |
|  scope | <code>any</code> | optional scope. If used only the callbacks with this scope will be removed |

<b>Returns:</b>

`boolean`

false if it doesn't belong to this Observable
