Linux- where apps run
Git- where code lives
jenkins - automation brain
Maven - Builds code
Docker - Packages app
AWS - Provides servers
Kubernetes - Manages scale
Terraform - Creates infrastructure
Prometheus - watches health


Linux is an operating system that can be installed locally or in the cloud.
DevOps engineers uses linux operating system to access servers remotely, install software, run applications, check logs, restart services, and troubleshoot failures.


Linux File System
/ = root
bin = basic commands
etc = configuration files
var = logs & variable data
home = user files
tmp = temporary files
usr = installed programs

DevOps Tips:
When config fails -  check /etc
When App fails - check /var/log

Linux Command
Linux uses different commands to pass tasks to the operating system.
echo file name = display file name
id = display user id, groups they belong to
sudo = super user do
pwd = where am I? or display my current location
apt = package/program manager
sudo apt install = telling the OS to install a package
whoami = tells the OS to display the current user
q= quit or exit

Navigation Commands
pwd = where am I? or display my current location
ls = list 
cd /path = change to the path / move to this path

Files command
mkdir directory-name = create directory name
touch filename = create file name
cp filename = copy filename
mv filename = move filename
rm filename = remove filename
rmdir dirname = remove directory (for an empty directory)
rm -r = remove directory (for non-empty directory)

View file commands
cat filename = show contents of the filename
less file name = display the content of the filename
tail-f = quickly accessing the last few lines of a given text file.



1️⃣ Why Permissions Exist (Plain English)

Linux is multi-user.
Permissions answer 3 simple questions:

Who can read this file?

Who can modify it?

Who can execute it?

This prevents:

Accidental damage

Security breaches

One user breaking another user’s work

-   rwx   r-x   r--
|   |     |     |
|   |     |     └── Others
|   |     └──────── Group
|   └────────────── User (owner)
└────────────────── File type
