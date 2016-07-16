
Editor Used :

Visual Studio : For opencv c++ coding (Find the tumours and other parameter from images)
Eclipse : For java development (Using trained data &  using SVN , decision tree algorithm find the results)

Steps :

Install Visual Studio 2012 And Eclipse IDE.
Install Opencv on your machine.

--------------Visual Studio Project Setting---------------
Copy Segmentation folder under Visual studio projects folder & access it from Visual Studio IDE. **Do run the project with debug.

Below setting has been added in visual Studio project (To Check Again , Right click on project name in solution explorer of visual studio -> properties):
C\C++ :
C:\opencv\build\include

Linker :
C:\opencv\build\x86\vc11\lib


Libraries : 
opencv_ts300d.lib
opencv_world300d.lib

Do the project setting as per above.
Path to opencv will change accordingly.

-----------------------------------

Regarding Java :
Import Java projectn directly in eclipse.

------------------------------------------------------

How Project Works :

Image processing is done using c++ (opencv) : This code will read the Image and writes in output file with parameter like No of tumours , size of tumours , Maximum size of tumours.

Output file created by c++ code will be taken as input in java. 
Please change the path in java code accordingly.

Tumorfile.txt : Imput File
Input1.arff : Output File