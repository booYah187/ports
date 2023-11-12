This guide assumes that you already have a github account. If not please create one before proceeding.
Step one. Forking the repo. Navigate to https://github.com/christianhaitian/PortMaster, the main portmaster repo, and click on the fork button toward the top right. This will clone the repo to your github so that you can make your own changes, in this case adding new port files. 

![1](https://github.com/booYah187/ports/blob/main/pr/1.png) 

Step two. Syncing your repo with main. This wont be necessary for your first Pull Request, but prior to making changes on your forked repo you can press "sync fork" to bring your PortMaster up to date with the main.

![2](https://github.com/booYah187/ports/blob/main/pr/2.png) 

Step three. Uploading port to your fork. From your PortMaster select add file, upload files.

![3](https://github.com/booYah187/ports/blob/main/pr/3.png) 

There are three files you will be uploading, the .zip of your port will be uploaded to the root of the repo, while the port.md file and port.screenshot.png will be uploaded to the markdown and images folder respectively. An easy way to accomplish this is to create two folders named markdown and images on your pc. Place the .md and .png in their respective folders, than drag and drop port.zip, /images, and /markdown into the github upload files box. This will put the markdown file and screenshot in the correct subfolders.

![4](https://github.com/booYah187/ports/blob/main/pr/4.png) 

One more task before pressing commit, fill in the subject and description in the following format. 


Subject "New Port for Portname" 

Description "New Port for Portname

URL: https://port.website

Portname

Instructions: This game is ready to run. All files are included. OR Download game from port.website, copy port.files to port.directory

Controls:
d-pad/l-stick = movement
a = shoot
b = jump

Notes: Special thanks to GameDev at https://gamedev.com for creating the game and allowing us to distribute the files.

Tested on:
RG35s/ArkOS

RG351p/AmberELEC

RG351v/AmberELEC

RG351mp/AmberELEC

RG353m/ArkOS

RG353p/JelOS

RG353v/ArkOS

RG353vs/ArkOS

OGA/ArkOS

RG503

RG552

x55/JelOS

RK2023

RGB30/JelOS

RGB20s/uOS"

Once you have filled in the subject and description with all pertinent details, press commit.

Step 4. Creating the Pull Request. Navigate to https://github.com/christianhaitian/PortMaster/pulls and click New Pull Request toward the top right.

![5](https://github.com/booYah187/ports/blob/main/pr/5.png) 

Then select "compare across forks"

![6](https://github.com/booYah187/ports/blob/main/pr/6.png) 

And finally choose your PortMaster fork from the drop down menu.

![7](https://github.com/booYah187/ports/blob/main/pr/7.png) 

Make sure that the subject and description match the information you filled in earlier when you commited your port files to your fork of PortMaster

![8](https://github.com/booYah187/ports/blob/main/pr/8.png) 

And finally you can select "create pull request"

Checks will automatically occur to make sure that you uploaded all necessary files.

![9](https://github.com/booYah187/ports/blob/main/pr/9.png) 

After a few minutes, and assuming you included all necessary files, the checks will pass, and your work has concluded. Once your pull request is merged your port(s) will be available to download.

![10](https://github.com/booYah187/ports/blob/main/pr/10.png) 
