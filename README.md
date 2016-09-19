# aws-tools
Collection of Python scripts to manage Amazon AWS

## Installation
* Clone the repository
* CD to the folder
* Run the following command to install require software
 * pip install -r requirements.txt

## Usage
* It's pretty self explanatory what each script does. Run the script without parameter to get the usage

## Notes
* Need Python 2.7x
* Make you've configured the "config" and "credentials" files before using these scripts. Check for the existence of the ".aws" folder if you're not sure
* The ".aws" folder can be created either manually or by using "aws configure". It can be located in the following locations
  * On Linux/Mac: ~/.aws
  * On Windows: %USERPROFILE%\\.aws (Normally C:\\Users\\USERNAME\\.aws)
* "aws configure" requires the [AWS Command Line Interface](https://aws.amazon.com/cli)
