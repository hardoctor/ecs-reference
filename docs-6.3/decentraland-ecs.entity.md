<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [decentraland-ecs](./decentraland-ecs.md) &gt; [Entity](./decentraland-ecs.entity.md)

## Entity class


<b>Signature:</b>

```typescript
export declare class Entity implements IEntity 
```

## Constructors

|  Constructor | Modifiers | Description |
|  --- | --- | --- |
|  [(constructor)(name)](./decentraland-ecs.entity.(constructor).md) |  | Constructs a new instance of the <code>Entity</code> class |

## Properties

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [alive](./decentraland-ecs.entity.alive.md) |  | <code>boolean</code> |  |
|  [children](./decentraland-ecs.entity.children.md) |  | <code>Record&lt;string, IEntity&gt;</code> |  |
|  [components](./decentraland-ecs.entity.components.md) |  | <code>Record&lt;string, any&gt;</code> |  |
|  [eventManager](./decentraland-ecs.entity.eventmanager.md) |  | <code>EventManager &#124; null</code> |  |
|  [name](./decentraland-ecs.entity.name.md) |  | <code>string &#124; undefined</code> |  |
|  [uuid](./decentraland-ecs.entity.uuid.md) |  | <code>string</code> |  |

## Methods

|  Method | Modifiers | Description |
|  --- | --- | --- |
|  [addComponent(component)](./decentraland-ecs.entity.addcomponent.md) |  | Adds a component. If the component already exist, it throws an Error. |
|  [addComponentOrReplace(component)](./decentraland-ecs.entity.addcomponentorreplace.md) |  | Adds or replaces a component in the entity. |
|  [getComponent(component)](./decentraland-ecs.entity.getcomponent.md) |  | Gets a component, if it doesn't exist, it throws an Error. |
|  [getComponent(component)](./decentraland-ecs.entity.getcomponent_1.md) |  |  |
|  [getComponentOrCreate(component)](./decentraland-ecs.entity.getcomponentorcreate.md) |  | Gets a component, if it doesn't exist, it creates the component and returns it. |
|  [getComponentOrNull(component)](./decentraland-ecs.entity.getcomponentornull.md) |  | Gets a component, if it doesn't exist, it returns null. |
|  [getComponentOrNull(component)](./decentraland-ecs.entity.getcomponentornull_1.md) |  |  |
|  [getParent()](./decentraland-ecs.entity.getparent.md) |  | Gets the parent entity |
|  [hasComponent(component)](./decentraland-ecs.entity.hascomponent.md) |  | Returns a boolean indicating if a component is present in the entity. |
|  [hasComponent(component)](./decentraland-ecs.entity.hascomponent_1.md) |  |  |
|  [hasComponent(component)](./decentraland-ecs.entity.hascomponent_2.md) |  |  |
|  [isAddedToEngine()](./decentraland-ecs.entity.isaddedtoengine.md) |  | Returns true if the entity is already added to the engine. Returns false if no engine was defined. |
|  [removeComponent(component, triggerRemovedEvent)](./decentraland-ecs.entity.removecomponent.md) |  | Removes a component instance from the entity. |
|  [removeComponent(component, triggerRemovedEvent)](./decentraland-ecs.entity.removecomponent_1.md) |  |  |
|  [removeComponent(component, triggerRemovedEvent)](./decentraland-ecs.entity.removecomponent_2.md) |  |  |
|  [setParent(\_parent)](./decentraland-ecs.entity.setparent.md) |  | Sets the parent entity |
