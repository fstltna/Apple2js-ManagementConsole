# Apple2js Management Console (1.0.0)
Allows you to manage your Apple2js server with a text based UI - 
Official support sites: [Official Github Repo](https://github.com/fstltna/Apple2js-ManagementConsole.git) - [Official Forum](https://appleii.retro-os.live/index.php/downloads/category/23-our-server-tools)


![Coffee MUD Sample Screen](https://pocketmud.com/coffee_mud.png) 

---

Edit "amc" and change the settings at the top if your Apple2js server is not in /home/apple2/apple2js

You also need to have my Apple2js Startup Script installed.

I suggest you then add this to your /home/apple2/.bashrc file:
	export PATH=/home/apple2/bin:/home/apple2/Apple2js-ManagementConsole:$PATH
You will need to install the required perl modules (as root):

- /home/apple2/Apple2js-ManagementConsole/installdeps


After that you should log out and back in and now "amc" should work.
