# README for tgCheckFileIntegrity.deb
## Integrity File Content:
# Checking the integrity of this package
##  Run this below command in a Linux system terminal
1. md5sum tgCheckFileIntegrity-1.0.0.deb
2. sha1sum tgCheckFileIntegrity-1.0.0.deb
3. sha256sum tgCheckFileIntegrity-1.0.0.deb

## The following result you will get
0b596c116c6a07f51f88003bf9242fc9  tgCheckFileIntegrity-1.0.0.deb
7f5901ef2078defd6b8618ec868318c8752c8d8a  tgCheckFileIntegrity-1.0.0.deb
8c0eb2491ae420942867b16b5be6d89ad97757830a6826fae8a56cbd459bf0ba  tgCheckFileIntegrity-1.0.0.deb

## Note:
If you do not get the similar result, do not use this package.

## Method File Content:
# Method to use this package
## STEP1: Run this below command in terminal to install this package.
1. sudo dpkg -i tgCheckFileIntegrity-1.0.0.deb
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

