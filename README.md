# OptiFine Support Team Cheat Sheet



## Common Problems

### No File Association
    Download [Java](https://java.com) or [AdoptOpenJDK](https://adoptopenjdk.net/)
    - If there is still an error Download [JarFix](https://johann.loefflmann.net/en/software/jarfix/index.html)
    
### Cape Stolen
    Reset OptiFine Password, move Cape back to account
    - Optionally have them reset their Email password

### Linux
    Ubuntu/Ubuntu Based Distros: Have them go to the properties of the .jar and enable "Allow Executing"

    Arch/Arch Based: `chmod +x optifine-jar-file.jar`
    
### OptiFine wont work on Badlion/Other PVP Clients
    We do not provide any support for pvp clients, before saying this: Have them try in a *Vanilla* instance of OptiFine, if issue persists, continue.
    if it doesn't say something like "We do not support PVP clients as there are to many variables to account for"
  #### OptiFine With Lunar
    Lunar isn't supported at all as it steals OptiFine

### Minecraft/OptiFine running on iGPU not dGPU
    Open dGPU Control Panel (AMD Adrenaline or NVidia Control Panel (NOT GeForce Experience))
    AMD Adrenaline:
    - Go To "Gaming" Tab
    - Add a Game
    - Locate javaw.exe (Normally in C:\Program Files (x86)\Minecraft Launcher\runtime\jre-x64\bin FOR STOCK MINECRAFT)
    
    NVidia Control Panel (IF USING NORMAL LAUNCHER IT MAYBE AUTO ADDED BY GeForce Experience):
    - Manage 3D Settings
    - Program Settings
    - Add -> Browse
    - Locate javaw.exe (Normally in C:\Program Files (x86)\Minecraft Launcher\runtime\jre-x64\bin FOR STOCK MINECRAFT)
    - Select NVidia Processor in drop down -> Click Apply
    
### Password Reset Email Not Sent
    Ask Them how long they have waited, it can take up to 24 hours to send.


## Cape Problems

### Banner Cape Doesn't Work
    Make sure they arent using more than 8 layers on the banner, or the Mojang Pattern.
#### Piglin + Globe + Mojang Patterns
    Piglin and globe patterns are not supported yet because of needcoolshoes.com needing permission from mojang.
    Mojang Pattern is not allowed because of Copyright + Impersonation
    
### Cape Not Showing Ingame
    Check Both Settings (Skin Customization > Cape: ON & Video Settings > Details > Show Capes: ON)
    Check that the cape is assigned to their [Account](https://optifine.net/login)
    Clear Browser Cookies - Check if Anti-Virus is blocking OptiFine - Check if ISP is blocking OptiFine



## StartUp Issues

### Always use [JarFix](https://johann.loefflmann.net/en/software/jarfix/index.html)
    This should always be the First attempt at fixing a startup issue unless it matches another one on here
    

## "Obscure" Problems

### File Permissions
    If there is a file permission error try deleting the OptiFine Version from the libraries folder `C:\Users\<user>\AppData\Roaming\.minecraft\libraries\optifine\OptiFine\<version>`
    

## Common Questions

### Render Regions not Recommended for iGPU
    Render regions renders the world in bigger chunks, so its more GPU-heavy, which iGPU's dont handle too well

### Internal Shaders not Recommended
    They are mainly made for Debugging or Enabling Shader Pipeline
    
### Change Email
    If its within 30 days, see Refund section, and donate with correct email.
    Otherwise its a lost cause, see if they can create the email they typed in.
    
### Refunds
    If you have anyone that is wanting to refund their capes or has anything related to PaymentWall, dont redirect them to sp.
    Instead redirect them to [PaymentWall's support](https://www.paymentwall.com/en/contacts).
    Note: PayPal or Bank Chargeback can block you.

