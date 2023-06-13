In the Project window, navigate to the Scripts folder. 

Create a new Script called `Spin`.

Open the new Script and enter the following code:

--- code ---
---
language: cs
filename: Spin.cs
line_numbers: true
line_number_start: 1
line_highlights:
---

using System.Collections;
using System.Collections.Generic;
using UnityEngine;

public class Spin : MonoBehaviour
{
    public Vector3 rotation;

    // Start is called before the first frame update
    void Start()
    {
       
    }

    // Update is called once per frame
    void Update()
    {
        transform.Rotate(rotation * Time.deltaTime); 
    }
}

--- /code ---

Save the script and return to Unity. 

Add the `Spin` script to any GameObject that you would like to spin. 

**Choose** the direction of the spin.

+ Change the `X`, `Y` and `Z` values in `Spin` script variables in the Inspector window to make your GameObject spin in the direction that you have chosen. 
