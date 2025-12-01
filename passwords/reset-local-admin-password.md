# Reset Local Admin Password  
*If you need to reset a forgotten local administrator password on Windows:*  

1. Log in with another admin account.  
2. Open **Computer Management** → *Local Users and Groups* → *Users*.  
3. Right-click **Administrator** (or the target account) → **Set Password...**  
4. Enter and confirm the new password.  
5. If no other admin exists, boot into Safe Mode with Command Prompt and run:
   `net user Administrator NewP@ssw0rd!` (replace `NewP@ssw0rd!` with the new password).  
6. Log in with the updated credentials and verify access. 
