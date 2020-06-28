# Ray2Mod_NewProject
Boilerplate project to quickly get started with Ray2Mod

You can download this repository as a template under the releases page, and add it to Visual Studio by copying the ZIP file to the folder:

``C:\Users\[User Name]\Documents\Visual Studio 20xx\Templates\Project Templates``

To begin modding Rayman 2, you have to add Ray2Mod.dll as a reference to this project:
 1. Right click References in the Solution Explorer
 2. Click Browse and locate Ray2Mod.dll 
 3. Press OK to add the reference
  
 Now you can run your mod by building this project and dragging the exported DLL onto ModRunner.exe
 To automatically start the ModRunner when clicking Start, configure the following:
 1. Click Project -> <YourProject> Properties...
 2. Open the Debug configuration on the left
 3. As start action, select "Start external program" and Browse for ModRunner.exe
 4. Under start options, set the command line arguments to <YourProject>.dll (for example Ray2Mod_NewProject.dll)
 
 Now the ModRunner will start and inject your mod whenever you click start.
