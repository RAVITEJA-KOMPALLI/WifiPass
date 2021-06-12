To check all the wifi networks that are connected to your device

In Command Prompt:
------------------
To list all the devices connected to your device, use 
    
    netsh wlan show profiles  

To list all the details of a single network, use

    netsh wlan show profile Wifi_name
    
    Example: netsh wlan show profile TP Link
- Using the above, In Security: we find the "Security Key" as "Present" (If a password do exist for that network)

To make the Password Visible, Use 
    
    netsh wlan show profile Wifi_Name key=clear
    
    Example:  netsh wlan show profile TP Link key=clear
    
----

Open .py files to get the passwords using python code