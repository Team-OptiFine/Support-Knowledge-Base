# OptiFine Support Team FAQ

## Common Cape Issues

### The user's Cape was Stolen
    There is not really anything we can do here. But tell the user that they can reset the password for Minecraft, Email, and optifine.

### Cape Not Showing Ingame
    Check Both Settings (Skin Customization > Cape: ON & Video Settings > Details > Show Capes: ON)
    Check that the cape is assigned to their Account
    Clear Browser Cookies - Check if Anti-Virus is blocking OptiFine - Check if ISP is blocking OptiFine
    Check that they can connect to the cape server, send the link in a fashion that Discord does not provide a preview image, such as "`http://s.optifine.net/capes/sp614x.png`". If they can not, proceed to Cape Server Blocked under Obscure Problems.

### Cape Server Blocked <!-- This is related to "Cape Not Showing Ingame" -->
    In short, have the user open `C:\Windows\System32\drivers\etc\hosts`, if a line contains `s.optifine.net` is there, then we need to delete it.
    - Open Notepad with Administrator (Search "Notepad" in your Windows Search Bar, right click on it and press Run as Administrator. Accept the prompt that comes up.
    - Press File -> Open
    - In the bottom right corner of the file window, change `Text Documents (*.txt)`` to ``All Files (*.*)`
    - Navigate to ``C:\Windows\System32\drivers\etc``
    - Double click on hosts
    - Delete the entire line that contains `s.optifine.net`
    - Press Control + S to save.
    - Close Notepad and restart your computer.

### Banner Cape Doesn't Work
    Make sure they arent using more than 8 layers on the banner, or the Mojang Pattern.

#### Modern & Mojang Patterns
    Piglin and globe patterns are not supported yet because of needcoolshoes.com needing permission from mojang.
    Mojang Pattern is not allowed because of Copyright + Impersonation

## Common File Issues

### OptiFine opening with something *other* than Java
    Download Java (https://java.com) or AdoptOpenJDK (https://adoptopenjdk.net/)
    - If there is still an error Download JarFix (https://johann.loefflmann.net/en/software/jarfix/index.html)

### Linux
    Ubuntu/Ubuntu Based: Have them go to the properties of the .jar and enable "Allow Executing"
    Arch/Arch Based: `chmod +x optifine-jar-file.jar`

### OptiFine installer error (Access Denied)
    If there is a file permission error try deleting the OptiFine Version from the libraries folder `C:\Users\<user>\AppData\Roaming\.minecraft\libraries\optifine\OptiFine\<version>`

## Other

### PvP Clients
    We do not officially provide support for them. If you want to help out, that is fine. But it's recommended that you ask them to go to a stand-alone version of OptiFine and if the issue continues, you can help them. If not, its most likely the pvp client causing the issue.

### Refunds
    If you have anyone that is wanting to refund their capes or has anything related to PaymentWall, dont redirect them to sp.
    Instead redirect them to PaymentWall's support (https://www.paymentwall.com/en/contacts)
    Note: PayPal or Bank Chargeback can block you.

### Change Email
    In order to process an email change request, the request must come from the original email, and list a replacement email. A confirmation must be made listing both emails (this is provided via a canned response under "Email Change Request"). Once confirmation is received, DM sp614x with the emails and the relevant ticket. Note: Users on the original email have 30 days to reverse the change. If the user does not have access to the original email/the email attached to the cape, then a change is not available.
    
### Data Deletion Requests/GDPR Requests
    If the request is not via email, tell them to send an email from the email that is attached to the account they'd like to remove.
    First, check that the user has an actual account by searching the email in the Database. If one comes up, proceed. If one doesn't, tell the user. We can ONLY process requests sent in from the actual email.
    Then, send a confirmation email that will be found as a canned response under "Data Deletion Confirmation" and replacing the filler content with their email.
    Once they agree, DM sp614x with the email and a link to the ticket.

### Minecraft/OptiFine running on iGPU not dGPU
    Open dGPU Control Panel (AMD Adrenaline or NVidia Control Panel (NOT GeForce Experience))
    AMD Adrenaline:
    - Go To "Gaming" Tab
    - Add a Game
    - Locate javaw.exe (Normally in C:\Program Files (x86)\Minecraft Launcher\runtime\jre-x64\bin FOR STOCK MINECRAFT)
    
    NVidia Control Panel (IF USING VANILLA LAUNCHER IT MAYBE AUTO ADDED BY GeForce Experience):
    - Manage 3D Settings
    - Program Settings
    - Add -> Browse
    - Locate javaw.exe (Normally in C:\Program Files (x86)\Minecraft Launcher\runtime\jre-x64\bin FOR STOCK MINECRAFT)
    - Select NVidia Processor in drop down -> Click Apply
        
    Note: IF they have Minecraft running under a different version of java, it will be located in `C:\Program Files\AdoptOpenJDK\<java version>\bin` or `C:\Program Files\Java\<java version>\bin` and must be javaw.exe

### White lines/Lines around blocks
    > **1.)** Close Minecraft and any other games, open Nvidia Control Panel (right click on the desktop then click Nvidia Control Panel)
    > **2.)** Click `Adjust image settings with preview`
    > **3.)** Click `Let the 3D application decide` then click `Apply` in the bottom right 
    The lines should no longer show up around blocks. 
