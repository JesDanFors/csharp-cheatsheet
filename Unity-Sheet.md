:metal: :metal: :metal:
Keyword |                  Summary                   | Sample Code | Mentioned In
------- | ------------------------------------------ | ------------ | ------------
GameObject | Is something with a name and position. | IDK | [Components](https://github.com/marczaku/csharp-oop/blob/main/slides/007-unity-components.md#1-components)
Transform | Position, Rotation and scale of a gameobject. | x: y: z: | [Components](https://github.com/marczaku/unity-introduction/blob/main/slides/007-unity-components.md#1-components)
RectTransform | Child to Transform, helpful for UI elements. | `anchoredPosition` | [Unity docs](https://docs.unity3d.com/ScriptReference/RectTransform.html)
Entities | Alternative word for objects used in other frameworks. | Entity. | [Components](https://github.com/marczaku/unity-introduction/blob/main/slides/007-unity-components.md#1-components)
Event Functions | Functions called automatically by unity. | `Start()` | [Event Functions](https://github.com/marczaku/unity-introduction/blob/main/slides/008-unity-event-functions.md#1-event-functions)
Awake() | Called only once and is the first thing called. | `void Awake(){}` | [Awake](https://github.com/marczaku/unity-introduction/blob/main/slides/008-unity-event-functions.md#2-awake)
OnDestroy() | Called once when destroyed or unloaded. | `void OnDestroy(){}` | [Start/OnDestroy](https://github.com/marczaku/unity-introduction/blob/main/slides/008-unity-event-functions.md#3-start--ondestroy)
OnEnable/OnDisable() | Called everytime the GameObject or script is enabled/disabled. | `void OnEnable(){}` | [OnEnable/OnDestroy](https://github.com/marczaku/unity-introduction/blob/main/slides/008-unity-event-functions.md#4-onenable--ondisable)
LateUpdate | Called once every frame but after all other update methods. | `void LateUpdate(){}` | [LateUpdate](https://github.com/marczaku/unity-introduction/blob/main/slides/008-unity-event-functions.md#7-lateupdate)
Collision | There is functions for when objects colliders interact with eachother. | `void OnCollisionEnter(){}` | [Collision](https://github.com/marczaku/unity-introduction/blob/main/slides/008-unity-event-functions.md#8-collision-3d)
Trigger | Works same as collisions but without the physical colission. | `void OnTriggerEnter(){}` | [Triggers](https://github.com/marczaku/unity-introduction/blob/main/slides/008-unity-event-functions.md#9-trigger-3d)
2D | Collisions and trigger also exists for 2D. | `void OnTriggerEnter2D(){}` | [2D](https://github.com/marczaku/unity-introduction/blob/main/slides/008-unity-event-functions.md#10-same-for-2d)
MouseInput | There is also alot of useful methods for mouse inputs. | `void OnMouseDown(){}` | [Mouse input](https://github.com/marczaku/unity-introduction/blob/main/slides/008-unity-event-functions.md#11-mouse-input)
`Time.deltaTime` | Function used for finding the time passed between last frame and current frame. | `Time.deltaTime` | [Unity doc](https://docs.unity3d.com/ScriptReference/Time-deltaTime.html)
Serialization | To save something or convert data to text | IDK | [Discord](https://discord.com/channels/690251537926193166/881839312939917322/899985629503430727)
Direct Referencing | You can call a specific component in a field. | `public Script script;`  | [Direct Referencing](https://github.com/marczaku/unity-introduction/blob/main/slides/009-communicating-between-gameobjects.md#1-direct-referencing)
`GetComponent()` | If a needed component is in the same Gameobject this can be used to call it. | `GetComponent<RigidBody>().velocity += speed;` | [GetComponent](https://github.com/marczaku/unity-introduction/blob/main/slides/009-communicating-between-gameobjects.md#2-getcomponent)
`GetComponentInParent`/ `GetComponentInChildren` | ? | ? | ?
`GetComponents()` | ? | ? | ?
`FindObjectOfType()` | ? | ? | ?
`SendMessage` | ? | ? | ?
Canvas | The obejct that can render UI. | ? | ?
Rect Transform | The transform for UI | ? | ?
Unity Event | Events in unity that can be called invoked. | `private UnityEvent OnJump; OnJump.Invoke();` | [UnityEvents](https://docs.unity3d.com/ScriptReference/Events.UnityEvent.html)
Physics.CheckSphere | Checks for collissions in a sphere around the centerpoint. Usefull for audiotriggers, maybe even 3D sound? | `if(Physics.CheckSphere(transform.position, sphereRadius))` | [Unity documentation](https://docs.unity3d.com/ScriptReference/Physics.CheckSphere.html)
