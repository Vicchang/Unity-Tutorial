# Unity APIs 
---
## GetComponent
1. Library
* UnityEngine
2. Prototype
* T GetComponet<T>()
3. Usage
* Get specific object in the scene in order to access the public functions or variables
3. Example
  ```C#
  Transform target = GetComponet<Transform>();
  ```
## Log
1. Prototype
* void Debug.Log(object message) 
2. Usage
* Print debug log to console
3. Example
  ```C#
  Debug.Log("this is an example");
  ```
## RequireComponent
1. Prototype
* RequireComponent(Type requiredComponent)
2. Usage
* Use for declare which compenent must be reference to the class
3. Example
 ```C#
  [RequireComponent(typeof(Rigidbody2D))]
  class T{}
 ```
