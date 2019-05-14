# findDevByVendorName
Find devices in a network using vendor name.
## Description 

This script provides you a fast way to search devices by vendor name. In order to use this script you must install jq
## Prerequisites
### Ubuntu 18.04.2 LTS
```
sudo apt install jq
```
## Installation 
```
cd ~ && git clone https://github.com/Yanujz/findDevByVendorName.git
cd ~/findDevByVendorName/
./install
```
## Usage
```
findDevByVendorName -h

Usage: findDevByVendorName -v [vendor] -o [output] -f [filename]
   
  -v 	| --vendor     : Specify vendor name
  -f 	| --filename   : Specify filename
  -vv	| --verbose    : Set verbose
  -o 	| --output     : Set output {json|jsonPretty|raw|file}
  -h 	| --help       : Prompt usage message
 Example:
  findDevByVendorName -v wiznet -vv -o jsonPretty
```

## Important 
If you want to add more vendors you have to edit "vendorMacPrefix.json" file located at ~/.devByVendor/dependencies/

## Author
  **Yanujz** - [Github Profile](https://github.com/Yanujz)
## License
This project is licensed under the MIT License - see the [LICENSE.md](https://github.com/Yanujz/findDevByVendorName/blob/master/LICENSE.md) file for details
