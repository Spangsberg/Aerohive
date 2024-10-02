# Aerohive

CLI Cnnfiguration of Aerohive access points, without need for a cloud dashboard.

The attached config file will create an SSID and attach it to both radios of the AP with a WPA2 AES passphrase.

If you don't need your SSID broadcast on 2.4GHz and you have Aerohive AP250 or newer, the line:   
radio profile RADIO0 phymode 11ng  

can be changed to:  
radio profile RADIO0 phymode 11ac  
and both radios will operate in 5GHz mode, on seperate channels. 

Please go through the config file and change all < > placeholder sections to suit your needs

Do a factory reset of the AP before uploading the config. 
SSH credentials for a reset AP:
User: admin
Password: aerohive

Link to CLI Command refference where all commands are documented and you can find more advanced features:
https://amarketplaceofideas.com/wp-content/uploads/2017/08/Aerohive%20CLI%20Guide.html

