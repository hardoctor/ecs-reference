<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [decentraland-ecs](./decentraland-ecs.md)

## decentraland-ecs package

## Classes

|  Class | Description |
|  --- | --- |
|  [Angle](./decentraland-ecs.angle.md) | Defines angle representation |
|  [AnimationState](./decentraland-ecs.animationstate.md) |  |
|  [Animator](./decentraland-ecs.animator.md) |  |
|  [Arc2](./decentraland-ecs.arc2.md) | This represents an arc in a 2d space. |
|  [AudioClip](./decentraland-ecs.audioclip.md) |  |
|  [AudioSource](./decentraland-ecs.audiosource.md) |  |
|  [AvatarShape](./decentraland-ecs.avatarshape.md) |  |
|  [Axis](./decentraland-ecs.axis.md) | Defines the 3 main axes |
|  [BasicMaterial](./decentraland-ecs.basicmaterial.md) |  |
|  [BezierCurve](./decentraland-ecs.beziercurve.md) | Class used to represent a Bezier curve |
|  [Billboard](./decentraland-ecs.billboard.md) | Billboard defines a behavior that makes the entity face the camera in any moment. |
|  [BoxShape](./decentraland-ecs.boxshape.md) |  |
|  [Camera](./decentraland-ecs.camera.md) |  |
|  [CircleShape](./decentraland-ecs.circleshape.md) |  |
|  [Color3](./decentraland-ecs.color3.md) | Class used to hold a RBG color |
|  [Color4](./decentraland-ecs.color4.md) | Class used to hold a RBGA color |
|  [ComponentAdded](./decentraland-ecs.componentadded.md) |  |
|  [ComponentRemoved](./decentraland-ecs.componentremoved.md) |  |
|  [ConeShape](./decentraland-ecs.coneshape.md) |  |
|  [Curve3](./decentraland-ecs.curve3.md) | A Curve3 object is a logical object, so not a mesh, to handle curves in the 3D geometric space. A Curve3 is designed from a series of successive Vector3. [https://doc.babylonjs.com/how\_to/how\_to\_use\_curve3](https://doc.babylonjs.com/how_to/how_to_use_curve3) |
|  [CylinderShape](./decentraland-ecs.cylindershape.md) |  |
|  [DisposableComponentCreated](./decentraland-ecs.disposablecomponentcreated.md) |  |
|  [DisposableComponentRemoved](./decentraland-ecs.disposablecomponentremoved.md) |  |
|  [DisposableComponentUpdated](./decentraland-ecs.disposablecomponentupdated.md) |  |
|  [Engine](./decentraland-ecs.engine.md) |  |
|  [Entity](./decentraland-ecs.entity.md) |  |
|  [EventManager](./decentraland-ecs.eventmanager.md) |  |
|  [Eyes](./decentraland-ecs.eyes.md) |  |
|  [Face](./decentraland-ecs.face.md) |  |
|  [Frustum](./decentraland-ecs.frustum.md) | <b><i>(BETA)</i></b> Reprasents a camera frustum |
|  [Gizmos](./decentraland-ecs.gizmos.md) | <b><i>(BETA)</i></b> Enables gizmos in the entity. Gizmos only work in EDITOR, PREVIEW or DEBUG modes. |
|  [GlobalPointerDown](./decentraland-ecs.globalpointerdown.md) |  |
|  [GlobalPointerUp](./decentraland-ecs.globalpointerup.md) |  |
|  [GLTFShape](./decentraland-ecs.gltfshape.md) |  |
|  [Hair](./decentraland-ecs.hair.md) |  |
|  [Input](./decentraland-ecs.input.md) |  |
|  [Material](./decentraland-ecs.material.md) |  |
|  [Matrix](./decentraland-ecs.matrix.md) | Class used to store matrix data (4x4) |
|  [MessageBus](./decentraland-ecs.messagebus.md) |  |
|  [MultiObserver](./decentraland-ecs.multiobserver.md) | Represent a list of observers registered to multiple Observables object. |
|  [NFTShape](./decentraland-ecs.nftshape.md) |  |
|  [OBJShape](./decentraland-ecs.objshape.md) |  |
|  [Observable](./decentraland-ecs.observable.md) | The Observable class is a simple implementation of the Observable pattern.<!-- -->There's one slight particularity though: a given Observable can notify its observer using a particular mask value, only the Observers registered with this mask value will be notified. This enable a more fine grained execution without having to rely on multiple different Observable objects. For instance you may have a given Observable that have four different types of notifications: Move (mask = 0x01), Stop (mask = 0x02), Turn Right (mask = 0X04), Turn Left (mask = 0X08). A given observer can register itself with only Move and Stop (mask = 0x03), then it will only be notified when one of these two occurs and will never be for Turn Left/Right. |
|  [ObservableComponent](./decentraland-ecs.observablecomponent.md) |  |
|  [Observer](./decentraland-ecs.observer.md) | Represent an Observer registered to a given Observable object. |
|  [ObserverEventState](./decentraland-ecs.observereventstate.md) | A class serves as a medium between the observable and its observers |
|  [OnAnimationEnd](./decentraland-ecs.onanimationend.md) |  |
|  [OnBlur](./decentraland-ecs.onblur.md) |  |
|  [OnChanged](./decentraland-ecs.onchanged.md) |  |
|  [OnClick](./decentraland-ecs.onclick.md) |  |
|  [OnEnter](./decentraland-ecs.onenter.md) |  |
|  [OnFocus](./decentraland-ecs.onfocus.md) |  |
|  [OnGizmoEvent](./decentraland-ecs.ongizmoevent.md) | <b><i>(BETA)</i></b> This event is triggered after the user finalizes dragging a gizmo. |
|  [OnPointerDown](./decentraland-ecs.onpointerdown.md) |  |
|  [OnPointerUp](./decentraland-ecs.onpointerup.md) |  |
|  [OnTextSubmit](./decentraland-ecs.ontextsubmit.md) |  |
|  [OnUUIDEvent](./decentraland-ecs.onuuidevent.md) |  |
|  [ParentChanged](./decentraland-ecs.parentchanged.md) |  |
|  [Path2](./decentraland-ecs.path2.md) | Represents a 2D path made up of multiple 2D points |
|  [Path3D](./decentraland-ecs.path3d.md) | Represents a 3D path made up of multiple 3D points |
|  [Plane](./decentraland-ecs.plane.md) | Represens a plane by the equation ax + by + cz + d = 0 |
|  [PlaneShape](./decentraland-ecs.planeshape.md) |  |
|  [PointerEvent](./decentraland-ecs.pointerevent.md) |  |
|  [PointerEventComponent](./decentraland-ecs.pointereventcomponent.md) |  |
|  [PointerEventSystem](./decentraland-ecs.pointereventsystem.md) |  |
|  [Quaternion](./decentraland-ecs.quaternion.md) | Class used to store quaternion data [https://en.wikipedia.org/wiki/Quaternion](https://en.wikipedia.org/wiki/Quaternion) [http://doc.babylonjs.com/features/position,\_rotation,\_scaling](http://doc.babylonjs.com/features/position,_rotation,_scaling) |
|  [Scalar](./decentraland-ecs.scalar.md) | Scalar computation library |
|  [Shape](./decentraland-ecs.shape.md) |  |
|  [Size](./decentraland-ecs.size.md) | Size containing widht and height |
|  [Skin](./decentraland-ecs.skin.md) |  |
|  [SphereShape](./decentraland-ecs.sphereshape.md) |  |
|  [Subscription](./decentraland-ecs.subscription.md) |  |
|  [TextShape](./decentraland-ecs.textshape.md) |  |
|  [Texture](./decentraland-ecs.texture.md) |  |
|  [Transform](./decentraland-ecs.transform.md) |  |
|  [UIButton](./decentraland-ecs.uibutton.md) |  |
|  [UICanvas](./decentraland-ecs.uicanvas.md) |  |
|  [UIContainerRect](./decentraland-ecs.uicontainerrect.md) |  |
|  [UIContainerStack](./decentraland-ecs.uicontainerstack.md) |  |
|  [UIImage](./decentraland-ecs.uiimage.md) |  |
|  [UIInputText](./decentraland-ecs.uiinputtext.md) |  |
|  [UIScrollRect](./decentraland-ecs.uiscrollrect.md) |  |
|  [UIShape](./decentraland-ecs.uishape.md) |  |
|  [UIText](./decentraland-ecs.uitext.md) |  |
|  [UIValue](./decentraland-ecs.uivalue.md) |  |
|  [UUIDEvent](./decentraland-ecs.uuidevent.md) |  |
|  [UUIDEventSystem](./decentraland-ecs.uuideventsystem.md) |  |
|  [Vector2](./decentraland-ecs.vector2.md) | Class representing a vector containing 2 coordinates |
|  [Vector3](./decentraland-ecs.vector3.md) | Classed used to store (x,y,z) vector representation A Vector3 is the main object used in 3D geometry It can represent etiher the coordinates of a point the space, either a direction Reminder: Babylon.js uses a left handed forward facing system |
|  [Vector4](./decentraland-ecs.vector4.md) | Vector4 class created for EulerAngle class conversion to Quaternion |
|  [Wearable](./decentraland-ecs.wearable.md) |  |

## Enumerations

|  Enumeration | Description |
|  --- | --- |
|  [ActionButton](./decentraland-ecs.actionbutton.md) |  |
|  [Gizmo](./decentraland-ecs.gizmo.md) | <b><i>(BETA)</i></b> Gizmo identifiers |
|  [InputEventType](./decentraland-ecs.inputeventtype.md) |  |
|  [Orientation](./decentraland-ecs.orientation.md) | Defines potential orientation for back face culling |
|  [Space](./decentraland-ecs.space.md) | Defines supported spaces |
|  [UIStackOrientation](./decentraland-ecs.uistackorientation.md) |  |
|  [UIValueType](./decentraland-ecs.uivaluetype.md) |  |

## Functions

|  Function | Description |
|  --- | --- |
|  [Component(componentName, classId)](./decentraland-ecs.component.md) |  |
|  [DisposableComponent(componentName, classId)](./decentraland-ecs.disposablecomponent.md) |  |
|  [error(error, data)](./decentraland-ecs.error.md) | Error function. Prints a console error. Only works in debug mode, otherwise it does nothing. |
|  [EventConstructor()](./decentraland-ecs.eventconstructor.md) |  |
|  [executeTask(task)](./decentraland-ecs.executetask.md) | Executes an asynchronous task |
|  [getComponentClassId(component)](./decentraland-ecs.getcomponentclassid.md) |  |
|  [getComponentId(component)](./decentraland-ecs.getcomponentid.md) |  |
|  [getComponentName(component)](./decentraland-ecs.getcomponentname.md) |  |
|  [isDisposableComponent(component)](./decentraland-ecs.isdisposablecomponent.md) |  |
|  [log(args)](./decentraland-ecs.log.md) | Log function. Only works in debug mode, otherwise it does nothing. |
|  [newId(type)](./decentraland-ecs.newid.md) | <b><i>(BETA)</i></b> Generates a new prefixed id |

## Interfaces

|  Interface | Description |
|  --- | --- |
|  [ComponentConstructor](./decentraland-ecs.componentconstructor.md) |  |
|  [ComponentLike](./decentraland-ecs.componentlike.md) |  |
|  [DisposableComponentConstructor](./decentraland-ecs.disposablecomponentconstructor.md) |  |
|  [DisposableComponentLike](./decentraland-ecs.disposablecomponentlike.md) |  |
|  [IEngine](./decentraland-ecs.iengine.md) |  |
|  [IEntity](./decentraland-ecs.ientity.md) |  |
|  [IEventConstructor](./decentraland-ecs.ieventconstructor.md) |  |
|  [IEvents](./decentraland-ecs.ievents.md) |  |
|  [ISize](./decentraland-ecs.isize.md) | Interface for the size containing width and height |
|  [ISystem](./decentraland-ecs.isystem.md) |  |

## Variables

|  Variable | Description |
|  --- | --- |
|  [DEG2RAD](./decentraland-ecs.deg2rad.md) | Constant used to convert from Euler degrees to radians |
|  [engine](./decentraland-ecs.engine.md) |  |
|  [Epsilon](./decentraland-ecs.epsilon.md) | Constant used to define the minimal number value in Babylon.js |
|  [RAD2DEG](./decentraland-ecs.rad2deg.md) | Constant used to convert from radians to Euler degrees |
|  [ToGammaSpace](./decentraland-ecs.togammaspace.md) | Constant used to convert a value to gamma space |
|  [ToLinearSpace](./decentraland-ecs.tolinearspace.md) | Constant used to convert a value to linear space |

## Type Aliases

|  Type Alias | Description |
|  --- | --- |
|  [AnimationParams](./decentraland-ecs.animationparams.md) |  |
|  [DecentralandInterface](./decentraland-ecs.decentralandinterface.md) |  |
|  [double](./decentraland-ecs.double.md) |  |
|  [EngineEvent](./decentraland-ecs.engineevent.md) |  |
|  [float](./decentraland-ecs.float.md) |  |
|  [FloatArray](./decentraland-ecs.floatarray.md) |  |
|  [GizmoDragEndEvent](./decentraland-ecs.gizmodragendevent.md) |  |
|  [GizmoSelectedEvent](./decentraland-ecs.gizmoselectedevent.md) |  |
|  [GlobalInputEventResult](./decentraland-ecs.globalinputeventresult.md) |  |
|  [IEventNames](./decentraland-ecs.ieventnames.md) |  |
|  [InputEventKind](./decentraland-ecs.inputeventkind.md) |  |
|  [InputEventResult](./decentraland-ecs.inputeventresult.md) |  |
|  [InputState](./decentraland-ecs.inputstate.md) |  |
|  [LocalActionButtonEvent](./decentraland-ecs.localactionbuttonevent.md) |  |
|  [MethodDescriptor](./decentraland-ecs.methoddescriptor.md) |  |
|  [ModuleDescriptor](./decentraland-ecs.moduledescriptor.md) |  |
|  [Nullable](./decentraland-ecs.nullable.md) |  |
|  [ObservableComponentSubscription](./decentraland-ecs.observablecomponentsubscription.md) |  |
|  [ReadOnlyColor4](./decentraland-ecs.readonlycolor4.md) |  |
|  [ReadOnlyQuaternion](./decentraland-ecs.readonlyquaternion.md) |  |
|  [ReadOnlyVector2](./decentraland-ecs.readonlyvector2.md) |  |
|  [ReadOnlyVector3](./decentraland-ecs.readonlyvector3.md) |  |
|  [ReadOnlyVector4](./decentraland-ecs.readonlyvector4.md) |  |
|  [TaskResult](./decentraland-ecs.taskresult.md) |  |
|  [TranformConstructorArgs](./decentraland-ecs.tranformconstructorargs.md) |  |
