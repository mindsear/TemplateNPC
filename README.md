# TemplateNPC
Template NPC for TrinityCore 3.3.5  
  
**UPDATE:** You must edit Rbac.h found in TrinityCore\src\server\game\Accounts  
Right above `RBAC_PERM_MAX` add  
```c++
    // custom permissions 1000+
    RBAC_PERM_COMMAND_RELOAD_TEMPLATE_NPC                    = 1019,  
```  
  
  
## How to install  
1. Copy TemplateNPC.cpp and TemplateNPC.h to your source folder (TrinityCore\src\server\scripts\Custom)  
2. Copy template_npc.patch to your TrinityCore root folder.
3. Apply the patch using git bash console. The command is 
    **patch -p1 <template_npc.patch**  
4. Use CMake (configure and generate)  
5. Execute characters.sql to your database  
6. Open TrinityCore.sln and Build the solution (Ctrl+Shift+B)  
  
  
## Screenshot
![alt tag](https://image.ibb.co/nGfeYn/template_Npc.png)  
  
Video Showcase:  
https://streamable.com/yxv1m
