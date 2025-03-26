# teststand_testcases

## Overview
In this repo you will find all the testcases which uses the onedriver 
To use those drivers please integrate the nuget package containing the specific .dll file from artifactory. <br/> 
For further questions about this repo please contact:<br/>  

## Table of Contents
- [Installation](#Installation)
- [Getting-Started](#Getting-Started)
- [File-structure](#File-structure)
- [Contributing](#contributing)

## Installation
1. Clone the repository:

   ```sh
   git clone ssh://pfde-vm-gerrit.eu.p-f.biz:29418/FA/SENS/URS/teststand_testcases
   ```

2. Install the NI Teststand:
Download the NI Teststand according to your system configurations from the following link:

[https://www.ni.com/de/support/downloads/software-products/download.teststand.html?srsltid=AfmBOor6PTh3nt3YdPmF_pel2wg8YT4lQTx0ZteGQmQwhpgpNZk8DIbt#548352]

3. Open the Project:


## GettingStarted


## File Structure
```
📂 teststand_testcases
├── 📂 TestUltrasonic  #(Folder for all ultrasonic sensor testcases)
│   ├── 📂 TestCasesCommon  #(Reusable components)
│   │   ├──📄 AdjustmentRange.seq #(sequence file for adjustment range)
│   │   ├──📄 AnalogErrorFreeze.seq  #(sequence file for adjustment range)
│   ├── 📂 TestF42  #(Project specific components)
│   ├── 📂 TestF77  #(Project specific components)
│   ├── 📂 TestM18  #(Project specific components)
│   ├── 📂 TestUsi  #(Project specific components)
│   ├── 📂 TestASCARI  #(Project specific components)
├── 📂 TestRadar  #(Folder for all radar sensor testcases)
│   ├── 📂 TestCasesCommon  #(Reusable components)
│   │   ├──📄 AdjustmentRange.seq  #(sequence file for adjustment range)
│   │   ├──📄 AnalogErrorFreeze.seq  #(sequence file for adjustment range)
├── 📄 package.json  #(Project metadata and dependencies)
├── 📄 README.md  #(Project documentation)
├── 📄 .gitattributes  #(Ignored files in Git)
└── 📄 .gitignore  #(Ignored files in Git)
```
## Contributing
Contributions are welcome! Please follow these steps:
1. Clone the repository.
2. Open the corresponding project in NI Teststand
3. Make your changes and commit them
4. Push to the remote repository(Gerrit)
5. After succesful code reviews by users and Jenkins
5. Pull the changes to get the latest changes.
