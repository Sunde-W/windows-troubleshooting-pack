# Flush DNS Cache PowerShell Script  
This PowerShell script flushes the DNS cache and renews IP configuration.  

```powershell  
# Flush DNS cache  
ipconfig /flushdns  

# Release IP address  
ipconfig /release  

# Renew IP address  
ipconfig /renew  
```  

To use: Open PowerShell as Administrator and run this script. It will clear the DNS resolver cache and renew your IP configuration.
