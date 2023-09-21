# Checking the integrity of this package
##  Run this blow command in linux system terminal
1. md5sum tgCreateDebPackage-1.0.0.deb 
2. sha1sum tgCreateDebPackage-1.0.0.deb
3. sha256sum tgCreateDebPackage-1.0.0.deb

## The following result you will get
1. 3766ec112a64de7e33a81e76975e3a93  tgCreateDebPackage-1.0.0.deb
2. c0c84c74a5ce530fe2a13a59a52370da7490b094  tgCreateDebPackage-1.0.0.deb
3. 59c49e93b522b5d13098d32eebb3274803583569ba4dbf905e60323de6fa83c7 tgCreateDebPackage-1.0.0.deb

## Note:
If you do not get the similar result, do not use this package.

# Method to use this package
## STEP1: Run this below command in terminal to install this package.
1. sudo dpkg -i tgCreateDebPackage-1.0.0.deb   
2. which tgCreateDebPackage            
3. It should display "/usr/bin/tgCreateDebPackage" it means success.

## STEP2: Use this package.
1. Create the bash script without dot sh. 
2. Run the below command in the terminal.
3. tgCreateDebPackage
4. A debien package .deb file will be created.

## STEP4: To uninstall this package run this below command in terminal.
1. dpkg -r tgCreateDebPackage   
2. tgCreateDebPackage         
3. It should display "command not found" it means this package is removed.

Author
Date:2023-Jan-12
Authors website: tami-green-cv.com
email:tamigreen2020@gmail.com
Licence: MIT
