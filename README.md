# SYSTEM-SOFTWARE-LAB

[![download](https://img.shields.io/badge/Direct_Download-zip-blue.svg?logo=appveyor&longCache=true&style=for-the-badge)](https://github.com/KTU-CSE/System-Software-lab/releases/latest)
[![website](https://img.shields.io/badge/Live-Site-green.svg?logo=appveyor&longCache=true&style=for-the-badge)](https://ktu-cse.github.io/System-Software-lab/)

B.Tech CSE S5 System Software Lab

Batch: CSE 2k20-24, ILAHIA COLLEGE OF ENGINEERING AND TECHNOLOGY 

University: APJ Abdul Kalam Technological University

## Content

- **[CPU Scheduling](CPU%20Scheduling/README.md)**

  - [FCFS Scheduling](CPU%20Scheduling/FCFS/README.md)
  - [SJF Scheduling](CPU%20Scheduling/SJF/README.md)
  - [Priority Scheduling](CPU%20Scheduling/Priority/README.md)
  - [Round Robin scheduling](CPU%20Scheduling/RoundRobin/README.md)

- **[Memory Management](Memory%20Management/README.md)**

  - [Single-Level Directory-File Organisation Technique](Memory%20Management/SingleLevelDir/README.md)
  - [Two-Level Directory-File Organisation Technique](Memory%20Management/TwoLevelDir/README.md)

- **[Deadlocks](Deadlocks/README.md)**

  - [Banker's Algorithm](Deadlocks/BankersAlgorithm/README.md)

- **[Disk Management](Disk%20Management/README.md)**

  - [FCFS Disk Scheduling](Disk%20Management/FCFS/README.md)
  - [SCAN Disk Scheduling](Disk%20Management/SCAN/README.md)
  - [C-SCAN Disk Scheduling](Disk%20Management/CSCAN/README.md)

- **[Virtual Memory](Virtual%20Memory/README.md)**

  - [FIFO Page Replacement Algorithm](Virtual%20Memory/FIFO/README.md)
  - [LRU Page Replacement Algorithm](Virtual%20Memory/LRU/README.md)
  - [LFU Page Replacement Algorithm](Virtual%20Memory/LFU/README.md)

- **[Process Synchronization](Process%20Synchronization/README.md)**
  - [Producer Consumer Problem](Process%20Synchronization/Producer%20Consumer/README.md)
  - [Dining Philosophers Problem](Process%20Synchronization/Dining%20Philosophers/README.md)
  - [Pass 1 of a Two Pass Assembler](Process%20Synchronization/Assemblers/Two%20Pass%20Assembler/Pass%201%20of%20a%20Two%20Pass%20Assembler/README.md)
  - [Pass 2 of a Two Pass Assembler](Process%20Synchronization/Assemblers/Two%20Pass%20Assembler/Pass%202%20of%20a%20Two%20Pass%20Assembler/README.md)
  - [Single Pass Assembler](Process%20Synchronization/Assemblers/Single%20Pass%20Assembler/README.md)
  - [Absolute Loader](Process%20Synchronization/Absolute%20Loader/README.md)
  - [Symbol Table With Hashing](#)          // toBeDone

<hr />

## Requirements

1. GCC Compiler --> [TDM-GCC MinGW Compiler](https://sourceforge.net/projects/tdm-gcc/)

 2. Any Text Editor of your preference 
    - [VS Code](https://code.visualstudio.com/) 
    - [Sublime Text](https://www.sublimetext.com/)  
    - [Atom](https://atom.io/)
    - [Brackets](http://brackets.io/)

## What each directory in this repo contains

```
1) CPU Scheduling      
	└──── FCFS
         	└──── 1.fcfs.c
         	└──── README.md                     
	└──── SJF
         	└──── 2.sjf.c
         	└──── README.md  
	└──── Priority
         	└──── 3.priority.c
         	└──── README.md  
	└──── RoundRobin
         	└──── 4.roundrobin.c
         	└──── README.md  
        └──── README.md   
    
2) Memory Management
	└──── SingleLevelDir
         	└──── 5.singleLevelDir.c
         	└──── README.md  
	└──── TwoLevelDir
         	└──── 6.twoLevelDir.c
         	└──── README.md  
        └──── README.md     

3) Deadlocks
	└──── BankersAlgorithm
         	└──── 7.bankers.c
         	└──── README.md  
        └──── README.md   

4) Disk Management
	└──── FCFS
         	└──── 8.fcfsDisk
         	└──── README.md  
	└──── SCAN
         	└──── 9.scan.c
         	└──── README.md  
	└──── CSCAN
         	└──── 10.csan.c
         	└──── README.md  
        └──── README.md   

5) Virtual Memory
	└──── FIFO
         	└──── 11.fifoPage.c
         	└──── README.md  
	└──── LRU
         	└──── 12.lru.c
         	└──── README.md  
	└──── LFU
         	└──── 13.lfu.c
         	└──── README.md  
        └──── README.md   

6) Process Synchronization
	└──── Producer Consumer Problem
	         	└──── 14.producer.c
         		└──── README.md  
	└──── Dining Philosophers Problem
				└──── 15.dining.c
				└──── README.md  
	└──── Assemblers
			└──── Two Pass Assembler
			       	└──── Pass 1 of a Two Pass Assembler
			       	|	   └──── 16.pass1.c	
			      	|	   └──── README.md  
				└──── Pass 2 of a Two Pass Assembler		
			       	|	   └──── 17.pass2.c	
			      	|	   └──── README.md  
			└──── Single Pass Assembler  
			       		   └──── 18.singlepass.c
			      		   └──── README.md  
	└──── Absolute Loader
				└──── 19.absolute.c
				└──── README.md  
	└──── Symbol Table With Hashing
```

## Getting Started

Clone this repo
```
$ git clone https://github.com/MUHAMMEDSAJAl/SYSTEM-SOFTWARE-LAB.git
```
Switch to the program folder
```
$ cd the/dir/where/program/file/is
```
Compile the source code
```
$ gcc yourProgramFile.c
```
To Execute
``` 
$ ./a.out
```

## License  
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE) file for details

## Spread the word
Liked the project? Just give it a star :star: and spread the word!
