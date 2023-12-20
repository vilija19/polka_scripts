# how to use


### Install 
git clone git@github.com:vilija19/polka_scripts.git update  
or  
git clone https://github.com/vilija19/polka_scripts.git update  
cd update   
chmod +x update_node  
cp .env_sample .env  
 
Edit file .env with your data:    
USER - User running the service    
BIN_DIR - path to kusama binary file.  
BASE_URL - base repo URL. From time to time it could be changed.  
E.g. https://github.com/paritytech/polkadot-sdk/releases/download/polkadot-  or https://github.com/paritytech/polkadot-sdk/releases/download/  
SERVICE_NAME -  Service name in systemctl  
The last line journalctl will run the service logs to check the update has been successful. Exit with Ctrl+C  

sudo ./update_node <version> (without the v in version).  
Example: 
sudo ./update_node 0.9.20 

Based on [https://gist.github.com/michalisFr/daa01c7374793a684a3a1f61e4959492](https://gist.github.com/michalisFr/daa01c7374793a684a3a1f61e4959492)
