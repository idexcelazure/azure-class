# Lab 5 - Create a custom VM image

* Start the Windows VM from the previous lab. If you don't have one, just create a new Windows VM in a new resource group
* RDP to the server. Install IIS using PowerShell with this command: **Install-WindowsFeature Web-Server**
* Run sysprep to generalize the server (run sysprep.exe)
* Use the steps listed in this article to capture an image of your server: https://docs.microsoft.com/en-us/azure/virtual-machines/windows/capture-image-resource
* Deploy a new VM from your new image (hint: you can do this in the portal by navigating to your new image)
* Double check that IIS is already installed on your new VM based off of your image
* Stop/deallocate the VM...we'll use it in the next lab
