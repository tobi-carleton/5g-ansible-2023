# Set up Server VM

* Choose an installation type
    * [Oracle Virtual Box VM Installation](./oracle-virtual-box-vm-setup.md)
    * [Digital Ocean VM Installation](./digital-ocean-vm-setup.md)
* Install mySQL on the VM using the following commands
    * sudo apt update
    * sudo apt-get install mysql-server
* Install Zabbix Server, Frontend, and Agent on your VM (link provided has been set to the commands for Ubuntu 22.04) - https://www.zabbix.com/download?zabbix=6.4&os_distribution=ubuntu&os_version=22.04&components=server_frontend_agent&db=mysql&ws=apache
* If using Digital Ocean VM, follow instruction on this website to set up a VNC server that will allow you to have a remote desktop on the cloud VM (this is required in order to view the Zabbix Server frontend GUI) - https://www.digitalocean.com/community/tutorials/how-to-install-and-configure-vnc-on-ubuntu-20-04
* Once logged in on the remote desktop GUI, launch a web browser and go to the URL "localhost/zabbix". There will be a guide to configure the Zabbix front end configurations
* Once done with the front end configuration - log in using the default credentials Admin/zabbix