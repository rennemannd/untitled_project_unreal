This is a UF student project to create an RPG style game in Unreal Engine 4. Below are instructions to get started on this project.

We are using the git flow model for branch orginization described here: https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow

The following instructions assume the use of GitKraken for source control but will work with other software.

1. Install Unreal Engine 4.21.2 through the epic games launcher 
2. Install git here: https://git-scm.com/book/en/v2/Getting-Started-Installing-Git
3. Install git lfs from here: https://github.com/git-lfs/git-lfs/releases
4. Run "git lfs install" in git bash
5. Git hooks must be enabled to use git lfs which is done in GitKraken by going to Preferences -> General and setting the path to sh.exe found in the git install bin.
6. Clone the project from this repo 
7. Open the project in UE. If using the default editor go to step 8, if using a different editor continue to step 9
8. Go into the project files and right click untitled_project.uproject then select "Generate Visual Studio Project Files".
9. To use a different editor open UE and naviagte to Edit ->  Editor Preferences -> General -> Source Code and change the IDE in the drop down menu for the source code editor. Then close out of the Editor Preferences and navigate to File -> Build CLion project (May say Reload CLion Project). 

With all of this setup git LFS should automatically tag large UE files but it is important to manually check in case something is missed.