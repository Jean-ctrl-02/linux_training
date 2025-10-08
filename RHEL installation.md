## RED HAT INSTALLATION 

#### PREREQUISITES
1. VirtualBox
   > - Download and install virtualBox [here](https://www.virtualbox.org/). 
3. RHEL 10 iso
   > - Create a Red Hat Enterprise Linux (RHEL) Developer Account
   > - Log in and download RHEL 10 image [here](https://developers.redhat.com/content-gateway/file/rhel/Red_Hat_Enterprise_Linux_10.0/rhel-10.0-x86_64-dvd.iso)

   
   

#### CREATE VIRTUAL MACHINE (VM)
1. **VM Name**: 'insert a consistent name'
2. **ISO image**: 'select the RHEL iso image you downloaded'
3. **OS**: Linux
4. **OS Distribution**: Red Hat
5. **OS Version**: Red Hat (64-bit)
6. Uncheck **'Proceed with Unattended Installation'**
7. **'Specify virtual hardware'**: Base memory (RAM) = 2GB, CPUs = 2 or more
8. **Disk size**: 20GB
9. Go settings, to storage and select **'Controller:SATA'**

### RUNNING THE VIRTUAL MACHINE (VM)
1. Select *english* as the language and press **'continue'**
2. Press the **'Connect to Red Hat'** and enter your red hat account crendentials and register.
3. For **'software selection'** select **'workstation'** and for add-ons select **'Container Management'**, **'Security Tools'**, **'Development Tools'**.
4. create a root password for the **'Root Account'**
5. Create a user account in the **'User Creation'**
6. Begin installization
7. When complete, press **'reboot system'**



