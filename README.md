# Faithful-RTX
The files here are to add raytracing for both Faithful x32 and x64.


Faithful website : https://faithfulpack.net


Steps to enable raytracing with Faithful

Locate the path of minecraft resource packs: C:\Users\You\AppData\Local\Packages\Microsoft.MinecraftUWP_8wekyb3d8bbwe\LocalState\games\com.mojang\resource_packs

open either the x32 or x64 folder and open the manifest with a text editor of your choice, at the end of the file add



,
  
     "capabilities" : [
       "raytraced"
     ]




make sure you put this after Modules  (IT MUST HAVE THE COMMA BEFORE "capabilities" TO ENSURE IT WORKS!!!!)

next copy the textures into the block folder.

Now load the game select which faithful you've added the files to and ensure they work :)
