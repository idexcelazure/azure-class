# Lab 5 - Create a custom VM image

* Create a new Windows VM in a new resource group
* RDP to the server. Install IIS using PowerShell with this command: Install-WindowsFeature Web-Server
* Run sysprep to generalize the server (run sysprep.exe)
* Use the steps listed in this article to capture an image of your server: https://docs.microsoft.com/en-us/azure/virtual-machines/windows/capture-image-resource
* Deploy a new VM from your new image (hint: you can do this in the portal by navigating to your new image)
* Double check that IIS is already installed on your new VM based off of your image
* Delete the resources from this lab when you're done
