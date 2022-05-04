# how to use

cd  
mkdir ~/update (only first time)  
cd update  
wget https://raw.githubusercontent.com/vilija19/polka_scripts/main/update_node   (only first time)  
chmod +x update_node  
 
Edit file update_node with your data:    
kusama: User running the service (change accordingly in chown kusama:kusama)   
/home/kusama/ change to your home directory.  
ksm-validator.service: Service name (change accordingly in all instances)  
The last line journalctl will run the service logs to check the update has been successful. Exit with Ctrl+C  

sudo ./update_node <version> (without the v in version).  
Example: 
sudo ./update_node 0.9.20 

Based on https://gist.github.com/michalisFr/daa01c7374793a684a3a1f61e4959492
