#!/bin/bash 

service_name="Apache" 
timestamp=$(date +"%Y-%m-%d %H:%M:%S") 
status=$(systemctl is-active httpd) 

if [ "$status" == "active" ]; then 

    message="Online" 
    echo "$timestamp - $service_name - Status: $status - $message" >> "/mnt/filesystem/anamaria/online.log" 

else 

    message="Offline" 
     echo "$timestamp - $service_name - Status: $status - $message" >> "/mnt/filesystem/anamaria/offline.log" 

fi 