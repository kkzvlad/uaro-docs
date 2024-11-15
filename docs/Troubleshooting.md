---
hide:
  - toc
---
# Troubleshooting

## Contents
1. [Client problem](#client-problems)
2. [My antivirus recognizes uaRO.exe and uaRO Patcher.exe as insecure software or virus.](#my-antivirus-recognizes-uaroexe-and-uaro-patcherexe-as-insecure-software-or-virus)
3. [Gepard Shield is stuck on the loading screen and is not showing any error messages.](#gepard-shield-is-stuck-on-the-loading-screen-and-is-not-showing-any-error-messages)
4. [There is a Gepard Shield error stating that illegal software is being used.](#there-is-a-gepard-shield-error-stating-that-illegal-software-is-being-used)
5. [I got an error: Gepard can't validate license on the server.](#i-got-an-error-gepard-cant-validate-license-on-the-server)
6. [There are low FPS or freezes occurring in the game client on a Windows 10/11 system with Nvidia graphics.](#there-are-low-fps-or-freezes-occurring-in-the-game-client-on-a-windows-1011-system-with-nvidia-graphics)
7. [Cannot init d3d OR grf file has problem](#cannot-init-d3d-or-grf-file-has-problem)

## **Client problems**

!!! Important 
    Always make sure you open **uaRO.exe**, Setup.exe or uaRO Patcher.exe as an administrator.

- Right-click on **uaRO.exe** and set its Compatibility mode to Windows 7, if you're running Windows 10 or Windows XP Service Pack 3, if you're running Windows 7.
- Right-click on **uaRO.exe** and tick the box next to **Run as Administrator**.
- Right-click on **uaRO Patcher.exe** and tick the box next to **Run as Administrator**.
- Be sure to grab the **latest patch** through **uaRO Patcher.exe**.
- Avoid installing the game to Program Files. Try to install it to somewhere like **`C:\Games\`**.
- **Disable Anti Virus AND Firewall** software before installing and/or patching. (Especially in the case of Avast and McAfee)
- If you use Warsaw (a bank software popular in Brazil), you will need to uninstall it.


#### **My antivirus recognizes uaRO.exe and uaRO Patcher.exe as insecure software or virus.**
It is possible that certain files within the client, particularly those that pertain to anti-cheat and anti-bot systems, may be flagged as viruses or potentially harmful software. Add game client folder, uaRO.exe or uaRO Patcher.exe as an exception for your antivirus.


#### **Gepard Shield is stuck on the loading screen and is not showing any error messages.**
Run Setup.exe from the uaRO folder and try different options:

- Choose the Resolution and Graphic Device.
- Remove checkbox from Play in Full Screen.
- Deactivate sound.
- Select checkbox "Delete all Ragnarok-related settings (factory reset)".


#### **There is a Gepard Shield error stating that illegal software is being used.**
![Gepard-Error-Code-503](img/Gepard-Error-Code-503.png)

Some mouse and keyboard software may be identified as prohibited macros or other types of unauthorized software.

In order to enter a game, it may be necessary to close this software. The list of approved software is constantly updated and added to the whitelist.


#### **I got an error: Gepard can't validate license on the server.**
- Check your internet connection.
- Add game client folder, uaRO.exe or uaRO Patcher.exe as an exception for your antivirus and firewall.


#### **There are low FPS or freezes occurring in the game client on a Windows 10/11 system with Nvidia graphics.**
To fix low FPS or freezes in the game client on a Windows 10 system with Nvidia graphics, follow these steps.

Go to the Nvidia Control Panel and adjust the 3D settings for uaRO.exe:

- Set the Max Frame Rate to 60 FPS
- Set the Monitor Technology to Fixed Refresh
- Set the Preferred Refresh Rate to Application-controlled
- Set Vertical Sync to Use the 3D-application setting

If you do not see these options, make sure to update your NVIDIA drivers. You can do this through the GeForce Experience application or by downloading the latest drivers from NVIDIA's website.

#### **Cannot init d3d OR grf file has problem**
![d3dOR](img/d3dOR.png)<br>
If you encounter this error, you need to run Setup.exe with administrator privileges, select DirectX7 in the Graphics API option, and save the changes.<br>
![DirectX7](img/DirectX7.png)