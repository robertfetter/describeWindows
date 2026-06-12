# describeWindows
Browser-based description of Windows executables/tasks

This is the installation package for the Windows Describe Executables/Tasks
(describeWindows) web browser based application.

This application is written in Linux bash and Python 3. It operates as a cgi-bin on an Apache web server.

Support is provided for both Windows 10 and Windows 11. 
Over 1000 entries for Windows is provided.

It operates on a Linux system. It can,  but does not have to, access Windows systems running in Virtualbox using ssh.

Contained here is an installation script (install) and three directories:
 
 html    contains web pages and images for the application
 
 cgi-bin contains the application script and supporting files
 
 tools   contains various script written during the build of this application.
         and the last audits for Windows 10 and Windows 11.
         There are also some other tools that may be of use.

The installation script needs to be run as 'root'.
It checks for the installation and running of the Apache Web Server.
It also looks for either Mozilla Firefox or Google Chrome.

The URL to run the application in stand-alone mode is:
  http://localhost/cgi-bin/describeWindows

Refer to the Help provided with the application for more information.

