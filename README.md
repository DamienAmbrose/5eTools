# Damien's Unblocked 5eTools!
*Visit the original site here: https://5e.tools/index.html*  
*View the original repository here: https://github.com/5etools-mirror-3/5etools-src*  

>In a world that insists and demands of control over every aspect of our digital lives, some of us wonder *"why?"*
>
>Why is it that we must mindlessly oblige to these immaterial and arbitrary rules enforced upon us without reason- without need- without **justice**.
>
>In this dystopian world we live in, we must seek solace in a communal experience so immaterial, arbitrary, and meaningless as the rules we seek to break:
>
>***Dungeons and Dragons.***

## Dependencies
- Ubuntu 23.04 or above
- Google Chrome 126.0.6478.126 or above
> [!NOTE]
> Previous versions may be supported, but stability is not guaranteed.

## Installation
*This project is designed to be manually installed onto systems wherein SUDO access is restricted, terminal functionality rendered non-existent, and internet connection compromised.*

### Step 1: 
Download and extract the source code. Look for `Code > Download Zip` on this repository's Code page. Alternatively, clone it via Git or SSH if you feel comfortable.  
![image](https://github.com/user-attachments/assets/425ba17c-bf91-41f6-af77-b12b10370e65)

### Step 2:
Move your newly downloaded repository folder (titled "5eTools") to your home directory (the folder which contains your Desktop and Documents folders).
![Screenshot from 2025-06-11 20-41-50](https://github.com/user-attachments/assets/761e27e2-db9b-4c89-9467-bfa039dc9da4)
>[!WARNING]
> Make sure there aren't any subfolders in the folder you unzipped. The folder `5eTools` should contain the folders `audio`, `css`, and so on. If there
>is another folder inside `5eTools` (probably *also* called "5eTools"), move **this** folder to your home directory, instead of the original folder.
>![Screenshot from 2025-06-11 20-52-48](https://github.com/user-attachments/assets/028ccff2-cdf0-4dba-921a-88501a2b0d6e)

### Step 3:
`5eTools` contains a utility file called 5e.desktop. Copy this file into `~/.local/share/applications`. The `.local` folder is in the same directory you moved the `5eTools` folder
in **Step 2**.
![Screenshot from 2025-06-11 20-48-45](https://github.com/user-attachments/assets/228face8-c0a7-4b50-abc3-406b82444b0d)
> [!IMPORTANT]
> To view the `.local` folder, you may need to show hidden files and folders in your file manager. In Nautilus, hit `Ctrl+H` or navigate to and check `Menu > Show Hidden Files`.

### Step 4:
Return to your home directory. Rename the `5eTools` folder to `.5e`. Make sure this folder contains the folders referenced in **Step 2**.
>[!WARNING]
>No shell scripts will work correctly if the folder is incorrectly named, or if it is a redundant wrapper folder.

![Screenshot from 2025-06-11 20-58-37](https://github.com/user-attachments/assets/74a77d55-307a-4ff4-b16f-42dc0f3ddd10)

> [!TIP]
> After you finish installation, configure your file manager to hide hidden items again. Check **Step 2**.

## Running
To run 5eTools on your machine, hit the `Super` key, or use the button on the status bar to open the Activities panel. Then, simply search for "5eTools" in the search bar.

An application should show up titled "5eTools". Run it, et voilà!

## Licensing
This project is made in large part by the unofficial GitHub mirror of 5eTools, licensed to [TheGiddyLimit](https://github.com/5etools-mirror-3/5etools-src/commits?author=TheGiddyLimit).

The original MIT license of the project remains intact. This project is further sublicensed to me under MIT for my contributions. Check [LICENSE](LICENSE.md) and [LICENSE_ORIGINAL](LICENSE_ORIGINAL.md).
