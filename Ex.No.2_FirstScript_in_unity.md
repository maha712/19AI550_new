# Script-in-Unity


REGISTER NUMBER :212222240057

## AIM:

To learn the basic scripting in Unity and print welcome message in Console window.

## Procedure:

Start the program

Open the Unity hub and Create a new 3D project

In Assets window, create the new folder and name it as Scripts

Create a new script with file name as FirstScript

Open the Script and print message "Welcome to Unity" inside the start function

Save the script

Create a new 3D game object in Hierarchy window and name it as 3DObject.

Add the component Firstscript in inspector window of 3Dobject.

Run the program

Stop the program.

## Program:
```
using System.Collections;
using System.Collections.Generic;
using UnityEngine;
public class FirstScript : MonoBehaviour
{
    // Start is called before the first frame update
    void Start()
    {
        print("Welcome to Unity");
    }

    // Update is called once per frame
    void Update()
    {
        
    }
}
```
## output:


<img width="647" height="521" alt="Screenshot (23)" src="https://github.com/user-attachments/assets/7d74d441-ac3d-4d85-9615-89aa4f8fce15" />



## Result:

Thus the welcome script was printed on Console Window sucessfully.


