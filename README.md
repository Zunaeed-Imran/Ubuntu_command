# Ubuntu_command
##### some useful command for Ubuntu users 

1. Slack Softwate Update command in Ubuntu
- `sudo apt upgrade slack`
2. To see the user name in Ubuntu
- `whoami`
3. Xampp server start command in Ubuntu every single time after turn on the computer
- `sudo /opt/lampp/lampp start`
4. Modify ACL permissions for htdocs folder for daemon user, when using PHP and using xampp we are gonna need taht.
- `sudo setfacl -Rdm u:daemon:rwx /opt/lampp/htdocs/`
- than rename with same command "daemon" to "imran"
- `sudo setfacl -Rm u:daemon:rwx /opt/lampp/htdocs/`
- than rename  "daemon" with "imran"
- finally this command will show details
- `sudo getfacl /opt/lampp/htdocs/`
- Slack update comment
- `sudo apt upgrade slack`
<<<<<<< HEAD

5. show unlocated software
- `dpkg -l | grep simplescreenrecorder`

6. uninstall command for unlocated software.
- `sudo apt-get purge simplescreenrecorder`

7. get package name
- `sudo apt-get purge package-name`
- `sudo reboot`
=======
- will show list all files and directories in a directory, including hidden files and directories.
- `ls -a`
>>>>>>> af31c4e (main)
