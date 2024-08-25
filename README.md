# Ubuntu_command

##### some useful command for Ubuntu users

1. Slack Softwate Update command in Ubuntu

- `sudo apt upgrade slack`

2. To see the user name in Ubuntu

- `whoami`

3. Xampp server start command in Ubuntu every single time after turn on the
   computer

- `sudo /opt/lampp/lampp start`

4. Modify ACL permissions for htdocs folder for daemon user, when using PHP and
   using xampp we are gonna need taht.

- `sudo setfacl -Rdm u:daemon:rwx /opt/lampp/htdocs/`
- than rename with same command "daemon" to "imran"
- `sudo setfacl -Rm u:daemon:rwx /opt/lampp/htdocs/`
- than rename "daemon" with "imran"
- finally this command will show details
- `sudo getfacl /opt/lampp/htdocs/`
- Slack update comment
- `sudo apt upgrade slack`

5. show unlocated software

- `dpkg -l | grep simplescreenrecorder`

6. uninstall command for unlocated software.

- `sudo apt-get purge simplescreenrecorder`

7. get package name

- `sudo apt-get purge package-name`
- `sudo reboot`

- will show list all files and directories in a directory, including hidden
  files and directories.
- `ls -a`

8. `php --ini` will show list of file of PHP.

9. This command will display the hostname of the machine you are currently
   logged into.

- `hostname`

10. will show server status of each component.

- `sudo /opt/lampp/xampp status`
- `sudo /opt/lampp/lampp status proftpd`

11. Update all software from Ubuntu terminal.

- `sudo apt update && sudo apt upgrade`

12. Clean Up: After the upgrade is complete, you can clean up any residual
    packages that are no longer needed. Run the following command:

- `sudo apt autoremove`

13. Sometimes, upgrading packages may require installing new dependencies or
    removing obsolete packages, This command may remove some packages if it's
    necessary to resolve dependencies or conflicts.

- `sudo apt dist-upgrade`

14. Sometimes, making new branch locak machine can't find it another device.

- `git fetch`
- this command will fix this.
- `git branch` we can check branch by using this command.

15. Search command for VS-code

- `ctrl+p` for file search in vs-code.
- `ctrl+f` for word search in vs code.

16. Ubuntu System Information

- `uname -a` General System Information
- `lsb_release -a` Detailed System Information
- `sudo lshw` Hardware Overview:
- `sudo lshw > hardware_info.txt` This provides a comprehensive overview of your hardware. You can also output this to a file for easier viewing.

17. CPU Information in Ubuntu

- `lscpu` CPU Details
- `cat /proc/cpuinfo` Another way to get CPU information:

18. Memory Information Ubuntu

- `free -h` RAM Details:
- `sudo dmidecode --type memory` Detailed RAM Information

19. Ubuntu Disk Information

- `df -h` Disk Space Usage:
- `lsblk` Disk Details:
- `sudo fdisk -l` Another detailed view of disk partitions

20. GPU Information in Ubuntu

- `lspci | grep VGA` GPU Details
- `sudo lshw -C display` Detailed GPU Information

21. Network Information in Ubuntu

- `ip a` Network Interfaces
- `ifconfig` Detailed Network Configuration

22. How to set PropTypes in react./ Props type in react.

- import PropTypes from "prop-types"; // up to the file
- MyApp.propTypes = {
  // this code will be down to the file
  count: PropTypes.number,
  onClick: PropTypes.func,
};
