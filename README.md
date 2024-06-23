# Project: Comprehensive Automation for Security, User Management, Backups, and String Manipulation

## Description

This project involves various roles and tasks typically encountered by DevOps professionals. The tasks include handling backup processes, managing security issues, creating user accounts, and performing string manipulations using Linux commands and Bash scripting. The project is divided into four main parts, each addressing specific problems and requirements.

## Problem Statement
Companies encounter a wide range of challenges based on their unique infrastructures and operational needs. In this project, you will tackle multiple tasks that are central to the role of a DevOps professional. These tasks encompass crucial areas such as backup management, security issue resolution, user and password management, and advanced string manipulation. To address these challenges, you will often need to write Bash scripts or execute specific Linux commands.

Each task is designed to simulate real-world problems and requires careful attention to detail. The tasks are structured to provide clear instructions, but they will also test your ability to apply Linux commands and scripting skills effectively. By completing these tasks, you will gain practical experience in automating routine operations, enhancing system security, managing user accounts efficiently, and manipulating text data precisely.

The detailed instructions for each task are outlined below. Please read them thoroughly, follow the specified requirements, and deliver the expected outputs. Good luck, and may you find this project both challenging and rewarding!

## Part 1: Security Issue

### Objective
As a DevSecOps engineer in a financial company, identify instances terminated by a specific user (Paul) from a CloudTrail event history file.

### Instructions
1. Create a Bash script to filter and manipulate the event history data.

2. Extract instance IDs terminated by the user `Paul`.

3. Save the results in a file named `result.txt`.

### Deliverables
- `script.sh`: Bash script to filter and extract the required information.

- `result.txt`: File containing the instance IDs terminated by Paul.

## Part 2: User and Password Script

### Objective
As a System Administrator, automate the creation of new user accounts and password generation to streamline account management and meet project deadlines.

### Instructions
1. Create a Bash script named `user_password.sh`.

2. The script should accept user account name and comments as parameters.

3. Create a new user account and generate a password.

4. Ensure users change their password upon first login.

### Deliverables
- `user_password.sh`: Bash script to automate user account creation and password management.

## Part 3: Backup and Cronjob

### Objective
As a DevOps Engineer in a gaming company, automate the backup of critical directories every 5 minutes.

### Instructions
1. Create a Bash script named `backup.sh`.

2. Backup the directories `/home/ec2-user/data`, `/etc`, `/boot`, and `/usr`.

3. Save the backups in the `/mnt/backup` directory with unique names based on hostname and timestamp.

4. Compress the backups with the `.tgz` extension.

5. Set up a cron job to run the script every 5 minutes.

### Deliverables
- `backup.sh`: Bash script to perform the backups and compression.

- Cron job configuration.

## Part 4: String Manipulation

### Task 1: Modify Environmental Variable
### Objective
Extract and use the private IP from a JSON file to set an environmental variable in a Terraform configuration file.

### Instructions
1. Extract the private IP from `info.json`.

2. Update the `ec2_private_ip` variable in the `terraform.tf` file using Linux commands.

### Deliverables
- `command.sh`: Script to perform the extraction and update.

### Task 2: Convert PEM Key Format
### Objective
Convert a single-line PEM key file into a multi-line format for use in an Ansible playbook.

### Instructions
1. Convert `certificate.pem` from single-line to multi-line format.

2. Save the result in `new.pem`.

### Deliverables
- `new.pem`: PEM file in multi-line format.

### Task 3: Identify Invalid User Attempts
### Objective
Analyze SSH connection logs to identify invalid user attempts and count the occurrences..

### Instructions
1. Parse the `auth.log` file to find invalid user attempts.

2. Count and list the invalid user names and the number of attempts.

### Deliverables
- `invalid_user.sh`: Script to identify and count invalid user attempts.

## Project Skeleton 

```css
DevOps Essentials: Automating Security, User Management, Backups, and String Manipulation (folder)

|----First_Part
|--------event_history.csv        # Given to the students
|--------result.txt               # To be delivered by students 
|--------script.sh                # To be delivered by students  

|----Second_Part
|--------user_password.sh         # To be delivered by students

|----Third_Part                   
|--------backup.sh                # To be delivered by students

|----Forth_Part
|--------Task_1
|------------info.json            # Given to the students
|------------terraform.tf         # Given to the students
|------------command.sh           # To be delivered by students  
|--------Task_2
|------------certificate.pem      # Given to the students
|------------new.pem              # To be delivered by students
|--------Task_3                   
|------------auth.log             # Given to the students
|------------invalid_user.sh      # To be delivered by students
```

### At the end of the project, the following topics will be covered:

- Bash Scripting

- Sed Command

- Grep Command

- Awk Command

- Cut Command

- Uniq Command

- String Manipulation

## Resources

- [Grep, Sed, Awk, Cut Commands](https://blog.knoldus.com/play-with-text-in-linux-grep-cut-awk-sed/)

- [Bash Scripting](https://linuxconfig.org/bash-scripting-tutorial-for-beginners)

- [Uniq Comand](https://www.geeksforgeeks.org/uniq-command-in-linux-with-examples/)

By completing this project, you will enhance your skills in Linux command-line operations, Bash scripting, and automation of routine tasks, which are essential for efficient system administration and DevOps practices.
