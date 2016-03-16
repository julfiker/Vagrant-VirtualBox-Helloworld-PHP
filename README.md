# PHP app deployment using Vagrant and Virtualbox on Ubuntu 14.04 LTS
Vagrant is an open source tool for building a complete virtual development environment. Very often, a test environment is required for testing the latest release and new tools. Also, it reduces the time spent in re-building your OS. By default, vagrant uses virtualbox for managing the Virtualization. Vagrant acts as the central configuration for managing/deploying multiple reproducible virtual environments with the same configuration.

If you want to know abuot vagrant and virtualbox, Please visit following url
https://www.vagrantup.com/
https://www.virtualbox.org/


## Step 1: If you don't have install vagrant and virtualbox, you should install by following command
### Installing Virtualbox:

$ sudo apt-get install virtualbox


### Installing Vagrant:

$ sudo apt-get install vagrant


Install the dkms package to ensure that the VirtualBox host kernel modules (vboxdrv, vboxnetflt and vboxnetadp) are properly updated if the Linux kernel version changes during the next apt-get upgrade.

$ sudo apt-get install virtualbox-dkms


## Step 2: Deployment 
Go to the project root folder, then run

$ vagrant up



## Step 3: Access the project through http
open browser, then access url

http://127.0.0.1:8000

It will show "Hello world!!";



## Step 4: Optional, You can apply other vagrant command as you need
After changing anything to need to update deployment file system, then run

$ vagrant provision


If you want to restart vm, then run

$ vagrant reload


If you want to access through ssh into the Virtual machine and want to review deploymented code, then run

$ vagrant ssh


If you want to shudown vm and shutdown of all process of vagrant, then run

$ vagrant destroy



## Contact information

You can contact me if you need anything regarding vagrant, virtual machine or linux container. I am enjoying a lot with these tools as a learner. 

Email: mail.julfiker@gmail.com
More information

Just visit following link

http://julfikerbd.wordpress.com/

Enjoy!
