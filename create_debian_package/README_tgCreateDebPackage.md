# README for tgCreateDebPackage.deb
## Integrity File Content:
# Checking the integrity of this package
##  Run this below command in a Linux system terminal
1. md5sum "tgCreateDebPackage-1.0.1.deb"
2. sha1sum "tgCreateDebPackage-1.0.1.deb"
3. sha256sum "tgCreateDebPackage-1.0.1.deb"

## The following result you will get
2ce4dcc83a9987f8c5ce352a5eae59ad  tgCreateDebPackage-1.0.1.deb
2ad026e32f2506e56f523c1a43350edbe0cc7d3d  tgCreateDebPackage-1.0.1.deb
23750ff0f8bf46e51a4f8894bcc3dda26a764bb033cc4251667bc02b2a2e1979  tgCreateDebPackage-1.0.1.deb

## Note:
If you do not get the similar result, do not use this package.

## Method File Content:
# Method to use this package
## STEP1: Run this below command in terminal to install this package.
1. sudo dpkg -i tgCreateDebPackage-1.0.1.deb
2. which tgCreateDebPackage
3. It should display /usr/bin/tgCreateDebPackage it means success.

## STEP2: To see codes of this package, run the below command in the terminal.
1. cat $(which tgCreateDebPackage)

## STEP3: Use this package.
1. Create the bash script without dot sh. 
2. Run the below command in the terminal.
3. tgCreateDebPackage
4. A debien package .deb file will be created.


## STEP4: To uninstall this package run this below command in terminal.
1. sudo dpkg -r tgCreateDebPackage
2. tgCreateDebPackage
3. It should display 'command not found' it means this package is removed.

### Author's Information
### 1. Date:2023-Jan-12
### 2. Website: https://tami-green-cv.com
### 3. Email:tamigreen2020@gmail.com
### 4. Licence: MIT

