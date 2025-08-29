
# InstallShield

## Preface
When you want to copy your software into another machine, you need to perform a few routine tasks. These may include:

- Registering `.dll` files  
- Checking for existing versions  
- Asking for user input  
- Setting expiry dates for evaluation copies  
- Restricting installations to a given number of licenses  

To achieve this in the Windows environment, there are a few software options. One is the InstallShield setup that comes with Visual Basic, and another is the professional InstallShield software from [InstallShield.com](http://www.installshield.com).  

Among them, **InstallShield Professional** is the most user-friendly. Avoid relying entirely on AppWizard—hand coding is better. Always test the setup on a **bare machine**.

---

## Key Considerations Before Writing a Setup Application

### 1. Executable Files
- Overwrite existing ones  
- Check for other executables  
- Check system registry for information  
- Handle any additional info  

### 2. DLLs
- Overwrite existing ones  
- Check for other executables  
- Check system registry for information  
- Handle any additional info  

### 3. OCX Files
- Overwrite existing ones  
- Check for other executables  
- Check system registry for information  
- Handle any additional info  

### 4. Writing into INI Files
- `win.ini`  
- `system.ini`  
- Other `.ini` files  

### 5. System Registry
- Create new keys and values  
- Update existing ones if needed  
- Delete existing keys and values  
- Read required information  

### 6. Submitting SQL Scripts
- Client-side  
- Server-side  

> Always verify the correct database version using the system registry.

### 7. Directory Structure
Collect the target directory structure before copying files.  

### 8. Bitmaps
- Startup bitmap  
- Background bitmap  
- Dialog bitmaps  
- Billboards  

### 9. Icons
Prepare application icons.  

### 10. Shortcuts
- System menu  
- Desktop  
- Other folders  

### 11. License Information
Collect license details.  

### 12. Logos
Collect logos to display.  

### 13. Text Validation
Perform spell check and grammar check.  

### 14. File Copy Location
- Standard system location  
- Option to let the user choose  

### 15. Service Packs
If service packs are planned, set required registry info.  

### 16. Installation Restrictions
Restrict users to a particular number of installations.  

### 17. Expiry Dates
Optionally set expiry dates for evaluation software.  

### 18. Power Failure Handling
Plan for what happens if power fails during installation.  

### 19. Bare Machine Testing
Always test on a fresh machine.  

### 20. Knowledge Base
Refer to:  
- [InstallShield.com](http://www.installshield.com)  
- [Revenera InstallShield Product Page](https://www.revenera.com/install/products/installshield)  

### 21. Purpose of InstallShield
- Just to install on client machines  
- To promote your product  
- To bill clients extra  

### 22. Available Software
- VB InstallShield  
- InstallShield Professional (**most preferable**)  
- InstallShield for various software  

### 23. Licensing
Ensure you use an authorized version. Piracy checks may occur after release.  

### 24. Estimated Time
- **Professional**: ~24 hours (3 man-days)  
- **Medium Skill**: ~15 man-days  
- **Layman**: ~2 man-months  

---

**Issued by Bhavani Prasad Polimetla in Public Interest in year 2000**
