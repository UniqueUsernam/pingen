# Overview
pingen is a command-line tool, written with bash scripting, for generating a list of all possible PINs of a certain number of digits for use in a PIN brute-force attack for penetration testing. pingen uses only bash builtins, so it should work on any system that has the bash shell installed. It creates lists very quickly (a 4-digit PIN list is created in less than a second on the build system), though it can take longer for PINs with lengths of 6 or more digits. To generate a list, all you need to know is the number of digits in the PIN.
# Features
+ Save the list of possible PINs to a file for later use.
+ Print the list of possible PINs, send them through a pipeline, or use with other tools.
+ Extremely fast generation time for PINs up to 5 digits long.
+ Create a list of PINs with any number of digits.
+ No mandatory dependencies or installation requirements other than bash.
+ Built-in manual page for those with man installed.
# Installation
To install pingen, you can clone this git repository onto your device:
> git clone https://github.com/UniqueUsernam/pingen.git
## Dependencies
+ The bash shell, installed at the path /bin/bash (https://www.gnu.org/software/bash/).

There are no further dependencies required to use pingen. To view the built-in manual page, you need to have man installed, but this is optional.
# Disclaimer
Do not use pingen for any illegal purposes, including, but not limited to, hacking into others' accounts, devices, or networks without permission. Cracking others' PINs to gain access to their account, device, or network is illegal, and pingen may not be used to break the law. Penetration testing requires explicit approval from the owner of the system you are testing on, and pingen should only be used for penetration testing with that permission. The developer of pingen does not assume any responsibility for illegal actions performed with the aid of, or invlolving, pingen.
