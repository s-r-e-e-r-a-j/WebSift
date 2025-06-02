## WebSift
WebSift is a powerful ethical hacking and OSINT (Open-Source Intelligence) tool designed to extract email addresses, phone numbers, social media links, and other links from websites. It is developed for Termux and Linux-based systems. This tool is ideal for security professionals and researchers who need to gather publicly available information for ethical and legal purposes.

## Features
- Scrapes **email addresses** from a given website.
- Extracts **phone numbers** in standard formats.
- Scrapes **social media links** and **other URLs** from websites to enhance OSINT capabilities
- Saves the extracted information for further analysis.
- Automatically checks and installs missing dependencies (curl, grep, wget).
- Compatible with **Termux** and **Linux distributions**

## Legal Disclaimer
This tool is intended for legal and ethical use only. The user is solely responsible for ensuring compliance with local laws and regulations. WebSift developers are not liable for misuse or unauthorized activities conducted using this tool.
## Installation
1. **Clone the Repository**
```bash
git clone https://github.com/s-r-e-e-r-a-j/WebSift.git
```
2. **Navigate to the WebSift directory**
```bash     
cd WebSift
```
3. **Navigate to the WebSift directory**
```bash
cd WebSift
```  
4. **Run the Script**
``` bash
bash websift.sh
```  
## Usage
1. Provide a valid URL when prompted.
   
2. Choose whether to extract email addresses, phone numbers, social media links, other links, or all three
   
3. Optionally save the extracted data to a folder.
## Example
```markdown
                                                                                                                                                                                              
                                                                                                                                                                                             
   __          __  _        _____ _  __ _                                                                                                                                                    
   \ \        / / | |      / ____(_)/ _| |                                                                                                                                                   
    \ \  /\  / /__| |__   | (___  _| |_| |_                                                                                                                                                  
     \ \/  \/ / _ \ '_ \   \___ \| |  _| __|                                                                                                                                                 
      \  /\  /  __/ |_) |  ____) | | | | |_                                                                                                                                                  
       \/  \/ \___|_.__/  |_____/|_|_|  \__|                                                                                                                                                 
                                                                                                                                                                                             
                         Developer: Sreeraj                                                                                                                                                  
                                                                                                                                                                                             
* Email, Phone Number, Social Media Links, and Other Links Scraper Tool                                                                                                                      
* Copyright © Sreeraj, 2024                                                                                                                                                                  
* GitHub: https://github.com/s-r-e-e-r-a-j                                                                                                                                                   
                                                                                                                                                                                             
[!] Checking internet connection...                                                                                                                                                          
[*] Connected to the internet.                                                                                                                                                               
[*] Enter URL to begin : http://testphp.vulnweb.com                                                                                                                                          
[*] Scrape emails from website? (y/n) : y                                                                                                                                                    
[*] Scrape phone numbers from website? (y/n) : y                                                                                                                                             
[*] Scrape social media links or other links? (y/n) : y                                                                                                                                      
[!] Scraping started                                                                                                                                                                         
[*] Emails extracted successfully:                                                                                                                                                           
wvs@acunetix.com                                                                                                                                                                             
[*] Phone numbers extracted successfully:                                                                                                                                                    
4445535400                                                                                                                                                                                   
[*] Social media links and other links extracted successfully:                                                                                                                               
http://download.macromedia.com/pub/shockwave/cabs/flash/swflash.cab#version=6,0,29,0                                                                                                         
https://www.acunetix.com/blog/articles/prevent-sql-injection-vulnerabilities-in-php-applications/                                                                                            
https://www.acunetix.com/vulnerability-scanner/                                                                                                                                              
https://www.acunetix.com/vulnerability-scanner/php-security-scanner/                                                                                                                         
http://www.eclectasy.com/Fractal-Explorer/index.html                                                                                                                                         
http://www.macromedia.com/shockwave/download/index.cgi?P1_Prod_Version=ShockwaveFlash                                                                                                        
http://www.w3.org/TR/html4/loose.dtd                                                                                                                                                         
[*] Do you want to save the output (y/n) : y                                                                                                                                                 
[*] Enter folder name : result                                                                                                                                                               
[*] Output saved successfully in result                                                                                                                                                      
[!] Exiting....                                                                                                                                                                             
```                   


## Dependencies
WebSift automatically checks for and installs the following dependencies if they are missing:

- **curl**
- **grep**
- **wget**
  
No manual installation is required!

## License
This tool is open-source and available under the MIT License.
## About
WebSift is an open-source project developed by Sreeraj. It combines the power of ethical hacking and OSINT techniques to provide a reliable and efficient solution for gathering publicly available information.
