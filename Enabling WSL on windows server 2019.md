Enable WSL in Windows via:
Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Windows-Subsystem-Linux

Download Ubuntu, e.g. Ubuntu 22.04:
Invoke-Webrequest -Uri https://aka.ms/wslubuntu2204 -OutFile .\Ubuntu2204.appx -UseBasicParsing
Rename the downloaded file Ubuntu2204.appx to Ubuntu2204_.zip, then extract this archive. Inside there are different appx files for different platforms. Choose the one for your platform, e.g. Ubuntu_2204.1.7.0_x64.appx.

Rename the appx file for your platform to Ubuntu2204.zip and extract this archive.

Extract the files in Ubuntu2204.zip to the target location where you would like your linux distro to reside.

Open the target location folder with the files of Ubuntu2204.zip and run the file ubuntu.exe, which is located inside the folder. This will install the distribution. It is important that you don't move the folder any more after the installation as this will result in an error when starting Ubuntu later.

Add the folder containing the ubuntu.exe file to the path variable. Ubuntu can then be started via ubuntu on the command line.
