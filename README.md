# Rotating-the-Gaming-Object

## Aim:
To develop a 3D application for rotating the gaming objects in unity.
## Algorithm:
### Step1:
Start
### Start2:
Click File -> Scene -> Select the scene -> Save as-> New folder(Scenes)-> File name (Expno1)
### Start3:
Click Hierarchy -> 3DObject -> Cylinder
Hierarchy -> 3DObject -> Capsule
Hierarchy -> 3DObject -> Text
Hierarchy -> Effects -> Particle system
### Start4:
Create a folder in project and name as Materials
Material folder -> Create -> Material (Name: Cylinder)
Inspector ->Surface Inputs ->BaseMAp (Choose the color)
Drag the Cylinder to the plane and release the mouse

Create a folder in project and name as Materials
Material folder -> Create -> Material (Name: Capsule)
Inspector ->Surface Inputs ->BaseMAp (Choose the color)
Drag the Capsule to the plane and release the mouse

### Start5:
Click Hierarchy -> DirectionalLight
Inspector -> Change the color to white (255,255,255)

### Start6:
Create a folder name Coding and create a C# file to add the coding in it.

### Start7:
To add our C# Script file to our selected object, click on the C# Script file and drag it to our selected objects in the Hierarchy window nad run the application.

### Start8:
Stop

## Program:
```
Developed by:Shobika P
Register No:212221230096

using System.Collections;
using System.Collections.Generic;
using UnityEngine;

public class text : MonoBehaviour
{
    // Start is called before the first frame update
    void Start()
    {
        
    }

    // Update is called once per frame
    void Update()
    {

        transform.RotateAround(Vector3.right, Vector3.up, 40 * Time.deltaTime);

    }
}
```
## Output:
![sh ](https://github.com/Shobika187/Rotating-the-Gaming-Object/assets/94508142/42c10261-f3f1-4203-a351-e1fc36e3b385)
![sh2](https://github.com/Shobika187/Rotating-the-Gaming-Object/assets/94508142/606ea277-5a4a-4106-af1e-e168669e7e6a)
![sh3](https://github.com/Shobika187/Rotating-the-Gaming-Object/assets/94508142/c6f0e177-94c2-4b1d-8756-8e02989039c4)

## Result:
Thus the program to rotating an object in unity is verified successfully
