# WebsiteBlocker
 Python app that utilises the time module to block certain distracting websites via the hosts file within working hours

## Installation
 Windows Users
 --------------
  ```Add the .pyw file to Task Scheduler to run the process as an administrator at system startup```
 
 Mac and Linux Users 
 -------------
  ```Add the file path to the Cron table as :
     
     sudo crontab -e
    
    # Inside the crontab file append the following line to the end of the file
     
     @reboot python3 path_to_file.py
  
  
  ```
     
  
  
  
  
     

 
 
