# Unity
A repository for unity game engine related techniques / scripts I've written.

## SetupUnity.sh

This is a simple bash script that when given both the directory of an android studio project and a unity export, will do the necessary copying to be able to then implement Unity into an activity.

Process:
1) Copy libs file from unity export to android project (in my case I also had to delete 2 libraries from the unity libs file as they conflicted with libraries I was using in my android studio project).
2) Copy assets file from unity export to andorid project.
3) Copy jniLibs files from unity export to android studio project.
