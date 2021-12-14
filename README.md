# Getting started with Visual Studio Code using C#!
Author: Alexander McNulty

## Purpose
This tutorial serves the purpose of teaching the user,
  <li>Where to access and dowload Visual Studio Code (VSc)</li>
  <li>How to Install C# extension within VSc </li>
  <li>How to Get started with creating a new project file and workspace</li>
  <li>How to Save and run their new code</li>

</ol>

## This tutorial is intended for any user(s) who are unfamiliar or are new to working with the Visual Studio Code software application. 
### Getting Started
Navigate to [VisualStudioCode.com](https://code.visualstudio.com/). Download the application for your specfic oprating system. For this tutorial I will be using **Windowsx64**.

![VSCWeb](https://user-images.githubusercontent.com/70073694/145650437-420e8d72-c4c5-4020-9355-25576bfc9d4c.png)

Once the download has completed open the application. It will look like similar to the image below.

![Visualcode](https://user-images.githubusercontent.com/70073694/145652591-27617214-3ca9-431c-b500-928958847a80.png)

### Downloading Extentions in Visual Studio Code.
In order to work within Visual Studio Code we will need to install extentions specfic to the coding language we wish to work within. In the case of this tutorial we will download and use **C#**.
  Naviagte to the left-hand side of the screen and select the four square icon for the extentions repository. A search bar will appear, search **C#**. Select the top result published by *Microsoft*  and install the extention.
  
  ### **Note that .NET may be required for proper function of C# in Visual Studio Code. This can be found [here](https://dotnet.microsoft.com/en-us/download).
  
  ![C# downlaod](https://user-images.githubusercontent.com/70073694/145652376-e5a594a2-fc13-4526-beda-d5d85f486197.png)
  
  ### New Project
  Once the extention has fully installed create a folder that will contain our workspace. Open your file explorer and create a new file where ever you store your files. In this example the file is stored on the desktop in the C:// drive. Name the folder something you will remember, we will need to find it in a few moments.
  
  ![Folder](https://user-images.githubusercontent.com/70073694/145652442-5f977627-3795-4a2b-aa1f-c23a2a85fb49.png)


  Back to Visual Studio Code. We will open the file we created moments ago by navigating to the *file* tab on the top left-hand of the screen. Find *Open Folder* and click it.
  
  ![Open Project](https://user-images.githubusercontent.com/70073694/145652696-40b0a9a8-4803-4bd2-9104-a263c76b6e5d.png)
  
  Find the folder you created and open it.
  
  ### Create New Console
  After opening the folder we need to create the files that will be stored in this folder. First we need to open the terminal. To do this navigate to the top of the screen and find *View*. Within *View* find *Terminal* and click it. This will open a terminal window at the bottom of the screen.
  
  ![Terminal](https://user-images.githubusercontent.com/70073694/145652553-e5f83615-f166-4b1c-8c63-cc14fb4ad57a.png)
  
  Within the terminal type out the following command, *dotnet new console* and hit enter to run the command. If done correctly it will load files into the workspace and a block of code will become visible. If this does not happen try the command again.
  
  ![New Console 2](https://user-images.githubusercontent.com/70073694/145652526-2ac491a1-a755-4d65-b5ff-c611e9e4f2f2.png)
  
  ### Running the program
  This program is called, ***Hello World*** and it is most commonly the first program any new programmer will write. Here it is written for us. We will add a line of code below line 9 to print a string *Visual Studio Code with C#!*.
  
  ![Screenshot (196)](https://user-images.githubusercontent.com/70073694/145655731-1b01df03-402e-4695-a145-3f0a2f64d20c.png)
  
  Now we will save our work! When code has been altered in this workspace it cannot be properlly ran unless it has been saved. So be sure to always save your work prior to running your code!
  
  Navigate to the file tab once more at the top left-hand side of the screen and find *save*, click it. Ths will save the line we just wrote.
  
  ![Screenshot (193)](https://user-images.githubusercontent.com/70073694/145655875-6f79b109-6c41-45bd-b427-c92aca0cdb8e.png)

Once saved we can run our code. Navigate back to the terminal and type in the command, *dotnet run* and hit enter.

![Screenshot (197)](https://user-images.githubusercontent.com/70073694/145656045-572582d6-562c-4fe4-abfe-ec80130e971e.png)

If everything worked correctly then your terminal will read identically to mine.

![Screenshot (198)](https://user-images.githubusercontent.com/70073694/145656130-5a22853f-7998-4f47-bcef-97f279af2ce2.png)

## Congratulations, you have successfully completed running a C# program within Visual Studio Code!
  








