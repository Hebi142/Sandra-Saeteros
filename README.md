# Sandra-Saeteros
Written Quiz
using System.Collections;
using System.Collections.Generic;
using UnityEngine;

public class Leslie : MonoBehaviour
        
{
    float moveX;
    float moveY;
    float moveZ;
   
    string variable1;
    string variable2;
    string variable3;
    string variable4;

    // Start is called before the first frame update
    void Start()
    {
    
        moveX = 3;
        moveY = 0;
        moveZ = 0;

        variable1 = "I";
        varianle2 = "want";
        variable3 = "100";
        variable4 = "pancakes";

        Debug.log(variable1);
        Debug.log(variable2);
        Debug.log(variable3);
        Debug.log(variable4);

    }

    // Update is called once per frame
    void Update()
    
        transform.Translate(-moveX, -moveY, moveZ);
        transform.Translate(moveX, -moveY, moveZ);
    }
}
