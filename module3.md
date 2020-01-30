# Installing Splunk

* **Linux:** Click free splunk, log in, Enterprise, linux, our version of linux, can use wget, do not install as root. Untar archive in opt, and go to splunk/bin. Will use commands like `./splunk start`, `./splunk stop`, and `./splunk restart`. Can find these using `./splunk help`. Accept license, create admin username, create admin password, it will display web interface address.

* **Windows:** Can use GUI installer or cli. Free Splunk, account, Enterprise, Windows, etc. System reqs, license. Can install defaults or customize installation. Can change install location, what account type, set password, shortcut, and installs. 

* **OSX** Same as the others. Can get as a dmg, or a tgz. Will be asked about splunk accepting network connections. 

Apps are preconfigured environments to extend prebuilt knowledge and capabilities. Built for a specific use case. **Roles determine what a user is able to see, do, and interact with.** Three main roles:
* Admin
...* Can install apps, ingest data, and create knowledge objects for all users.
* Power User
...* Can create and share knowledge objects for users of an app and do realtime searches.
* User
...* Will only see their own knowldege objects and those shared with them.

## Module 3 Quiz
1. You can launch and manage apps from the home app.
...* **True**
2. The password for a newly installed Splunk instance is:
...* **Created when you install Splunk Enterprise**
3. This role will only see their own knowledge objects and those that have been shared with them.
...* **User**
4. What are the three main default roles in Splunk Enterprise?
...* **Power**
...* **User**
...* **Admin**
5. Which apps ship with Splunk Enterprise?
...* **Home App**
...* **Search & Reporting**
