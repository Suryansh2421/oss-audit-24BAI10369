# oss-audit-24BAI10369
# Open Source Software Audit Scripts

**Student Name:** Suryansh Dhakarwal  
**Registration Number:** 24BAI10369  
**Chosen Software:** VLC Media Player  

## Overview
This repository contains a collection of Bash shell scripts designed to audit and interact with open-source software on a Linux system, specifically focusing on VLC Media Player as the chosen software. These scripts demonstrate various aspects of system administration, package management, and open-source principles.

## Scripts Description

### script1.sh - System Identity Report
This script generates a comprehensive system identity report including:
- Distribution information
- Kernel version
- Current user details
- Home directory
- System uptime
- Current date
- License information about open-source software

### script2.sh - FOSS Package Inspector
This script inspects the installation status of VLC Media Player and provides:
- Installation check using package manager
- Package details if installed
- Description of VLC as an open-source multimedia player

### script3.sh - Disk and Permission Auditor
This script performs a disk and permission audit on key system directories:
- Checks permissions and sizes of /etc, /var/log, /home, /usr/bin, /tmp
- Specifically audits VLC configuration directory (~/.config/vlc)

### script4.sh - Log File Analyzer
This script analyzes log files for specific keywords:
- Takes a logfile path and optional keyword (defaults to "error")
- Counts occurrences of the keyword
- Displays the last 5 matching lines

### script5.sh - Open Source Manifesto Generator
This interactive script generates a personal open-source manifesto:
- Asks three questions about open-source usage and beliefs
- Creates a personalized manifesto file
- Saves the output to a text file

## Prerequisites and Dependencies
- **Operating System:** Linux (specifically tested on Ubuntu/Debian-based distributions)
- **Shell:** Bash (version 4.0 or higher)
- **Dependencies:**
  - Standard Linux utilities: `uname`, `whoami`, `uptime`, `date`, `grep`, `cut`, `tr`, `awk`, `du`, `ls`
  - Package manager: `dpkg` (for Debian/Ubuntu systems)
  - Text processing tools: `tail`, `cat`

## Installation and Setup
1. Clone or download this repository to your Linux system
2. Navigate to the script directory: `cd /path/to/script/directory`
3. Make all scripts executable:
   ```bash
   chmod +x script1.sh script2.sh script3.sh script4.sh script5.sh
   ```

## Step-by-Step Instructions to Run Each Script

### Running script1.sh
```bash
./script1.sh
```
**Description:** This script runs automatically and displays the system identity report. No user input required.

### Running script2.sh
```bash
./script2.sh
```
**Description:** This script automatically checks for VLC package installation and displays the results. No user input required.

### Running script3.sh
```bash
./script3.sh
```
**Description:** This script performs the directory audit automatically. It requires read access to system directories, so it may need to be run with appropriate permissions (sudo if necessary for certain directories).

### Running script4.sh
```bash
./script4.sh /path/to/logfile [keyword]
```
**Parameters:**
- `/path/to/logfile`: Path to the log file you want to analyze (required)
- `keyword`: Search term to look for (optional, defaults to "error")

**Examples:**
```bash
./script4.sh /var/log/syslog
./script4.sh /var/log/apache2/error.log error
./script4.sh /home/user/app.log warning
```

### Running script5.sh
```bash
./script5.sh
```
**Description:** This is an interactive script. It will prompt you with three questions:
1. Name one open-source tool you use every day
2. In one word, what does 'freedom' mean to you?
3. Name one thing you would build and share freely

Answer each question and press Enter. The script will generate and display your manifesto.

## Notes
- These scripts are designed for educational purposes as part of an open-source software audit assignment
- Some scripts may require elevated permissions to access certain system directories
- The scripts assume a Debian/Ubuntu-based Linux distribution due to the use of `dpkg`
- VLC Media Player is used as the example open-source software throughout the scripts
- All scripts include proper error handling and user-friendly output

## License
This project is released under the GPL License, in line with open-source principles.# Open Source Software Audit Scripts

**Student Name:** Suryansh Dhakarwal  
**Registration Number:** 24BAI10369  
**Chosen Software:** VLC Media Player  

## Overview
This repository contains a collection of Bash shell scripts designed to audit and interact with open-source software on a Linux system, specifically focusing on VLC Media Player as the chosen software. These scripts demonstrate various aspects of system administration, package management, and open-source principles.

## Scripts Description

### script1.sh - System Identity Report
This script generates a comprehensive system identity report including:
- Distribution information
- Kernel version
- Current user details
- Home directory
- System uptime
- Current date
- License information about open-source software

### script2.sh - FOSS Package Inspector
This script inspects the installation status of VLC Media Player and provides:
- Installation check using package manager
- Package details if installed
- Description of VLC as an open-source multimedia player

### script3.sh - Disk and Permission Auditor
This script performs a disk and permission audit on key system directories:
- Checks permissions and sizes of /etc, /var/log, /home, /usr/bin, /tmp
- Specifically audits VLC configuration directory (~/.config/vlc)

### script4.sh - Log File Analyzer
This script analyzes log files for specific keywords:
- Takes a logfile path and optional keyword (defaults to "error")
- Counts occurrences of the keyword
- Displays the last 5 matching lines

### script5.sh - Open Source Manifesto Generator
This interactive script generates a personal open-source manifesto:
- Asks three questions about open-source usage and beliefs
- Creates a personalized manifesto file
- Saves the output to a text file

## Prerequisites and Dependencies
- **Operating System:** Linux (specifically tested on Ubuntu/Debian-based distributions)
- **Shell:** Bash (version 4.0 or higher)
- **Dependencies:**
  - Standard Linux utilities: `uname`, `whoami`, `uptime`, `date`, `grep`, `cut`, `tr`, `awk`, `du`, `ls`
  - Package manager: `dpkg` (for Debian/Ubuntu systems)
  - Text processing tools: `tail`, `cat`

## Installation and Setup
1. Clone or download this repository to your Linux system
2. Navigate to the script directory: `cd /path/to/script/directory`
3. Make all scripts executable:
   ```bash
   chmod +x script1.sh script2.sh script3.sh script4.sh script5.sh
   ```

## Step-by-Step Instructions to Run Each Script

### Running script1.sh
```bash
./script1.sh
```
**Description:** This script runs automatically and displays the system identity report. No user input required.

### Running script2.sh
```bash
./script2.sh
```
**Description:** This script automatically checks for VLC package installation and displays the results. No user input required.

### Running script3.sh
```bash
./script3.sh
```
**Description:** This script performs the directory audit automatically. It requires read access to system directories, so it may need to be run with appropriate permissions (sudo if necessary for certain directories).

### Running script4.sh
```bash
./script4.sh /path/to/logfile [keyword]
```
**Parameters:**
- `/path/to/logfile`: Path to the log file you want to analyze (required)
- `keyword`: Search term to look for (optional, defaults to "error")

**Examples:**
```bash
./script4.sh /var/log/syslog
./script4.sh /var/log/apache2/error.log error
./script4.sh /home/user/app.log warning
```

### Running script5.sh
```bash
./script5.sh
```
**Description:** This is an interactive script. It will prompt you with three questions:
1. Name one open-source tool you use every day
2. In one word, what does 'freedom' mean to you?
3. Name one thing you would build and share freely

Answer each question and press Enter. The script will generate and display your manifesto.

## Notes
- These scripts are designed for educational purposes as part of an open-source software audit assignment
- Some scripts may require elevated permissions to access certain system directories
- The scripts assume a Debian/Ubuntu-based Linux distribution due to the use of `dpkg`
- VLC Media Player is used as the example open-source software throughout the scripts
- All scripts include proper error handling and user-friendly output

## License
This project is released under the GPL License, in line with open-source principles.
