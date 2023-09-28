# Remote camera for 3D printer
# Authors 
- Wiktor Zantowicz
# Description of the project 
This project focuses on creating a 3D printer monitoring system with a Raspberry Pi-based camera. This setup provides convenience and flexibility for users to oversee their 3D printing projects from anywhere. 

# Science and tech used 
Parts and software used in this project:
- Raspberry Pi Zero: Core hardware running OctoPrint and camera
- Raspberry Pi Camera: dedicated camera for real-time monitoring
- Raspberry Pi Zero case
- OctoPrint: An open-source 3D printer control software that supports webcam integration.
- octoeverywhere.com: The chosen platform for remote access, offering a user-friendly interface for camera feed access.



# State of the art 
I used OctoPrint as the camera management system. It allows for remote access in LAN, but in an academic network, such connections are typically blocked by default. Because of this, I decided to utilize octoeverywhere.com as the server. As a result, anyone with access to the account can monitor the 3D print from anywhere. A free account allows for 30 seconds of viewing, after which the page needs to be refreshed.

The recommended Raspberry Pi for OctoPrint is the 3rd version, but for this project, a Raspberry Pi Zero is sufficient because we are not utilizing the full capabilities of OctoPrint.

To use the system, all that's needed is the login and password available in the Complexity Garage.
# What next?
Text here... 
# Sources 
- [Writing on GitHub] ( https://docs.github.com/en/get-started/writing-on-github ) 
