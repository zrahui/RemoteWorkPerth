## Windows Virtual Desktop

This folder contains architecture and deployment guides for WVD (Windows Virtual Desktop).

For the latest, up-to-date deployment and service information; refer to the articles below on docs.microsoft.com
https://docs.microsoft.com/en-gb/azure/virtual-desktop/overview

### Web Client
Access the WVD Web Client through this short link: [aka.ms/wvdweb](http://aka.ms/wvdweb)

### WVD PowerBI Dashboard
Download the prebuilt PowerBI Dashboard for WVD [here](https://github.com/zrahui/RemoteWorkPerth/blob/master/WVD/WVD%20Reporting.zip)

### Videos
* [Stefan Georgiev - Modernize your image management strategy](https://medius.studios.ms/Embed/video-nc/StefanGeorgiev)
* [Stefan Georgiev - Best practices for profile management with FSLogix](https://medius.studios.ms/Embed/video-nc/Stefan-Georgiev) - AD Auth with Azure Files
* [Roop Kiran Chevuri - Optimizing your deployment](https://medius.studios.ms/Embed/video-nc/Roop-Kiran-Chevuri)
* [Pavithra Thiruvengadam - Secure Your Deployment at Scale](https://medius.studios.ms/Embed/video-nc/PavithraThiruvengadam)
* [Denis-Gundarev Deployment best practices for latency-sensitive workloads in Windows Virtual Desktop](https://medius.studios.ms/Embed/video-nc/Denis-Gundarev)

### Adding Hosts to existing Host Pool
* [Stefan Georgiev (Video) - Adding VM's to Host Pool](https://www.youtube.com/watch?v=-QSzxRk8rpU)
* [Expand existing Host Pool](https://docs.microsoft.com/en-us/azure/virtual-desktop/expand-existing-host-pool)

### Securing and Optimising the virtual machine image for Windows Virtual Desktop 
When creating your master template, whether it's for a server session based desktop (e.g. Windows 2016) or desktop operating system (e.g. Windows 10), it is important that you secure and optimise the image. Here are some references to help you.
* [Recommended settings for VDI desktops](https://docs.microsoft.com/en-us/windows-server/remote/remote-desktop-services/rds-vdi-recommendations)
* [Optimizing Windows 10, version 2004, for a Virtual Desktop Infrastructure (VDI) role](https://docs.microsoft.com/en-us/windows-server/remote/remote-desktop-services/rds-vdi-recommendations-2004)
* [Optimizing Windows 10, version 1909, for a Virtual Desktop Infrastructure (VDI) role](https://docs.microsoft.com/en-us/windows-server/remote/remote-desktop-services/rds_vdi-recommendations-1909)
* [Deployment guide for Windows Defender Antivirus in a virtual desktop infrastructure (VDI) environment](https://docs.microsoft.com/en-us/windows/security/threat-protection/windows-defender-antivirus/deployment-vdi-windows-defender-antivirus)
* [Virus scanning recommendations for Enterprise computers that are running currently supported versions of Windows](https://support.microsoft.com/en-us/help/822158/virus-scanning-recommendations-for-enterprise-computers)
* [Using Group Policy Objects to hide specified drives](https://support.microsoft.com/en-us/help/231289/using-group-policy-objects-to-hide-specified-drives)

### Securing Access to Windows Virtual Desktop
* [How to configure Conditional Access with Session Management for Windows Virtual Desktop (WVD)](https://www.robinhobo.com/how-to-configure-conditional-access-with-session-management-for-windows-virtual-desktop-wvd/)

### Managing Profile Size
* https://stealthpuppy.com/fslogix-containers-capacity/
* [Storage options for FSLogix for WVD](https://docs.microsoft.com/en-gb/azure/virtual-desktop/store-fslogix-profile)

### Troubleshooting
* [Microsoft Windows Virtual Desktop Troubeshooting](https://docs.microsoft.com/en-us/azure/virtual-desktop/troubleshoot-set-up-overview)
* Other Links
    * [https://www.robinhobo.com/category/microsoft/windows-virtual-desktop-wvd/](https://www.robinhobo.com/category/microsoft/windows-virtual-desktop-wvd/)
    * [https://christiaanbrinkhoff.com/](https://christiaanbrinkhoff.com/)

### Other Links
* PowerShell Reference - https://docs.microsoft.com/en-us/powershell/module/windowsvirtualdesktop/
* VM Sizing Guidance - https://docs.microsoft.com/en-us/windows-server/remote/remote-desktop-services/virtual-machine-recs
* Creating master image - https://docs.microsoft.com/en-us/azure/virtual-desktop/set-up-customize-master-image
* Support matrix for WVD Web Client - https://docs.microsoft.com/en-us/azure/virtual-desktop/connect-web
* Third-party scripts for onboarding AD Groups into WVD - https://blog.azureinfra.com/2020/01/04/windows-virtual-desktop-group-sync-script/, https://www.microcloud.nl/wvd-group-assignments-powershell/

