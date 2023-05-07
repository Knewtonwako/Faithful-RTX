# Faithful-RTX
The files here are to add raytracing for both Faithful x32 and x64.


Faithful website : https://faithfulpack.net

 DO NOT PUT x32 files into x64 and vice versa


Steps to enable raytracing with Faithful

Locate the path of minecraft resource packs: C:\Users\You\AppData\Local\Packages\Microsoft.MinecraftUWP_8wekyb3d8bbwe\LocalState\games\com.mojang\resource_packs

open either the x32 or x64 folder and open the manifest with a text editor of your choice, at the end of the file add



,
  
     "capabilities" : [
       "raytraced"
     ]




make sure you put this after Modules  (IT MUST HAVE THE COMMA BEFORE "capabilities" TO ENSURE IT WORKS!!!!)

Copy the files in the blocks folder into either the x32/x64 blocks folder. 

Make sure candles, deepslate, and huge_fungus folders are put into the blocks folder

Now load the game select which faithful resource pack you've added the files to and enjoy


PS: In the case that the glass isnt transparent. replace the glass.png within the blocks folder with the one provided alongside the main download
