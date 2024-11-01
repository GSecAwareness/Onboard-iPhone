# Onboard iPhone into Intune and Assign Compliance Policy

## Introduction

### Intune MDM (Mobile Device Management) for iPhone is a cloud-based management solution within Microsoft Intune that allows organizations to securely manage iOS devices like iPhones and iPads. It provides a way for IT administrators to control, configure, and protect company data on these devices, ensuring security and compliance without compromising the user experience.

### Intune can enforce security policies and configurations on enrolled iPhones, such as passcode requirements, Wi-Fi settings, VPNs, and email profiles.  It allows organizations to push apps or app bundles to devices from the App Store, as well as in-house built apps. The IT department can manage app permissions, enforce policies, and control updates. Intune also offers remote management options such as locking or wiping devices, resetting passcodes, and troubleshooting issues. IT can check compliance status and ensure devices adhere to company policies and posture configuration.

#### 1)	In the App Store, download the Intune Company Portal app  

#### 2) Open the app and read through the setup steps. Press Begin to start the setup process  

<img src="https://github.com/GSecAwareness/Onboard-iPhone/blob/main/1.PNG" alt="get-content" width="300"/>


#### 3) On the next screen, read through “Device management and your privacy”   

####  This will tell you what the organization can and cannot access on your device.  
      It cannot view browsing history, see personal emails, documents, contacts, or calendar.  
      It cannot access passwords, view or edit photos.  
      It cannot see the location of your device.  

      It can view the model, serial number, OS, device name  
      It can reset your device to factory settings  
      It can view information collected by corporate apps and networks  
      It can see your phone number and installed apps  
      It can see the location of a lost device  

<img src="https://github.com/GSecAwareness/Onboard-iPhone/blob/main/2.PNG" alt="get-content" width="300"/>

#### 4) Click on Continue to download the management profile. If it asks for permission, do so.  

####    If there's a security delay, approve it to start the 1-hour countdown before setup can proceed. 

#### 5) Go to the Settings app and select Profile Downloaded.

<img src="https://github.com/GSecAwareness/Onboard-iPhone/blob/main/3.PNG" alt="get-content" width="300"/>  

#### 6) After the security lockdown has ended, go to setting and click on Profile Downloaded
insert managment profile pic

#### 7) Choose to Install, located at the top right and enter your password. It will ask you again if you trust the profile's source for remote management. Choose Trust. 
#### At this point you are taken to a screen to confirm the installation of a root certificate on your phone. A root certificate establishes a trusted connection between your device and your company’s network. It verifies that your device is connecting to a legitimate Intune server. It essentially tells your device, “This server is trusted by your organization, and any data exchange with it is safe.” Intune relies on certificates to encrypt communications between your device and the MDM server.

#### 8) Once the management profile is installed, an pop-up will ask for adminstrative management rights for each app installed. Choose Change to allow management. The apps will install in the background. 





