# Ex05-Rec-JaggedArray
## Aim:
To write a C# program to create a sample CPU usage on a network with 4 nodes using a jagged array.
## Algorithm:

### Step1:
Start

### Step2:
Create a jagged array of 4arrays.

### Step3:
Give the sample CPU usage in the jagged array.

### Step4:
Print the sample CPU usage in the jagged array.

### Step5:
stop

## Program:
```
using System;

class pr

{

    public static void Main(String[] args)

    {

        int[][] cpu = new int[4][];

        cpu[0] = new int[3];

        cpu[1] = new int[5];

        cpu[2] = new int[6];

        cpu[3] = new int[4];

        for (int i = 0; i < 4; i++)

        {

            for (int j = 0; j < cpu[i].Length; j++)

            {
                cpu[i][j] = i * j + 70;

            }

        }
        for (int i = 0; i < cpu.Length; i++)

        {

            for (int j = 0; j < cpu[i].Length; j++)

            {

                Console.WriteLine("CPU usage for node {0} is (1)" ,i , cpu[i][j]);

            }

            Console.WriteLine();

        }
    }
}

```

## Output:
![C# EX 5](https://user-images.githubusercontent.com/94165415/230872827-efd16491-a1c7-4c85-9467-074c9bca761c.png)

## Result:
Thus,C# program to create a sample CPU usage on a network with 4 nodes using a jagged array is executed successfully.
