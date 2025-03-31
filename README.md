# HW2_Q2 readme
## What you need
You need Visual Studio 2022 and window 11 OS.

And C/C++ should be available in VS2022.

## About
This project is about Gamma Correction.

To view the result image, open result.png, 
and if you want an explanation of the code, scroll down below.

## How to run

1. Click code and download as zip file.
![image](https://github.com/user-attachments/assets/a8ccf21f-3ae4-4523-a6fc-1f1b5ff4bc3d)

2. Unzip a download file
![image](https://github.com/user-attachments/assets/92fc4ee3-a21f-4425-bf3a-cad394b74483)

3. Open hw2_Q1-master. Double click hw2_Q1-master and opne OpenglViewer.sln
![image](https://github.com/user-attachments/assets/2ecc615a-eb26-4546-8c89-de8bda00f3d2)

4. click "F5" on your keybord. Then you will get the result.
![image](https://github.com/user-attachments/assets/45fdd966-f2ac-4a18-a77f-aa2122c2c011)

## Code explanation
To implement gamma correction, you just need to add the following code to the render function.


// Perform gamma correction with γ = 2.2

float gamma = 2.2f;

color = pow(color, vec3(1.0f / gamma));

The rest is same as Hw2_Q1 code.
