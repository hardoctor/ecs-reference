<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [decentraland-ecs](./decentraland-ecs.md) &gt; [Observable](./decentraland-ecs.observable.md) &gt; [add](./decentraland-ecs.observable.add.md)

## Observable.add() method

Create a new Observer with the specified callback

<b>Signature:</b>

```typescript
add(callback: (eventData: T, eventState: ObserverEventState) => void, mask?: number, insertFirst?: boolean, scope?: any, unregisterOnFirstCall?: boolean): null | Observer<T>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  callback | <code>(eventData: T, eventState: ObserverEventState) =&gt; void</code> | the callback that will be executed for that Observer |
|  mask | <code>number</code> | the mask used to filter observers |
|  insertFirst | <code>boolean</code> | if true the callback will be inserted at the first position, hence executed before the others ones. If false (default behavior) the callback will be inserted at the last position, executed after all the others already present. |
|  scope | <code>any</code> | optional scope for the callback to be called from |
|  unregisterOnFirstCall | <code>boolean</code> | defines if the observer as to be unregistered after the next notification |

<b>Returns:</b>

`null | Observer<T>`

the new observer created for the callback
