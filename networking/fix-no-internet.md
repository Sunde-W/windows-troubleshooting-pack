# Fix No Internet Connection on Windows  
If your PC can't connect to the internet, try these steps:  

1. **Check physical connections** – Ensure the Ethernet cable is plugged in or Wi‑Fi is turned on.  
2. **Restart your router and modem** – Power cycle your networking hardware.  
3. **Run the Windows Network Troubleshooter** – Go to Settings → Network & Internet → Status → Network troubleshooter.  
4. **Reset the network adapter** – In Device Manager, disable and re‑enable the network adapter.  
5. **Flush DNS and renew IP** – Open Command Prompt (Run as administrator) and run:  
   ```  
   ipconfig /flushdns  
   ipconfig /release  
   ipconfig /renew  
   ```  
6. **Update network drivers** – Download the latest drivers from your device manufacturer.  

If these steps don't resolve the issue, contact your ISP.
