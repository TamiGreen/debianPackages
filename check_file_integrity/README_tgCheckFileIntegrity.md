# README for tgCheckFileIntegrity
## Integrity File Content:
# Checking the integrity of this package
##  Run this below command in a Linux system terminal
1. md5sum tgCheckFileIntegrity-1.0.1.deb
2. sha1sum tgCheckFileIntegrity-1.0.1.deb
3. sha256sum tgCheckFileIntegrity-1.0.1.deb

## The following result you will get
1. 3588fe6ba8b3b3dd251cebfc1c2a8471  tgCheckFileIntegrity-1.0.1.deb
2. 3f03f8ef533745eadce3faf5243a04bdeb670ccb  tgCheckFileIntegrity-1.0.1.deb
3. 1e10b30e843ce87295cffdea0d778976435fa4c608f2c2ae1221eac01d348d2d  tgCheckFileIntegrity-1.0.1.deb

## Note:
If you do not get the similar result, do not use this package.

## Method File Content:
# Method to use this package
## STEP1: Run this below command in terminal to install this package.
1. sudo dpkg -i tgCheckFileIntegrity-1.0.1.deb
2. which tgCheckFileIntegrity
3. It should display /usr/bin/tgCheckFileIntegrity it means success.

## STEP2: To see codes of this package, run the below command in the terminal.
1. cat $(which tgCheckFileIntegrity)

## STEP3: Use this package.
1. Run the below command in the terminal.
2. tgCheckFileIntegrity

## STEP4: To uninstall this package run this below command in terminal.
1. sudo dpkg -r tgCheckFileIntegrity
2. tgCheckFileIntegrity
3. It should display 'command not found' it means this package is removed.

Author Information:
### Author's Information
### 1. Date:2023-Mar-15
### 2. Website: https://tami-green-cv.com
### 3. Email:tamigreen2020@gmail.com
### 4. Licence: MIT

