# TestGithub
=============
 You need to have [Linux](https://www.wikihow.com/Install-Linux) installed.
 
 Ubuntu(18.04) Linux should be used to compile and Run (execute) C program.
 
 https://vitux.com/how-to-write-and-run-a-c-program-in-linux/
 

## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)
* [Example](#example)
* [Compile](#compile )
* [Run](#run)
* [Operating System](#operating-system)


## General info ##
This is simple information about compile and Run the C program.
	
## Technologies ##
 created with:
* Linux
* Ubuntu version: 18.04LTS
* Gcc 

## setup ##
### Type command to install gcc compiler ###
 ./$ sudo adt-get install build-essential

### To check gcc version ### 
 ./ $gcc -version 
 
 ### Document directory ###
  ./$cd Documents/  
  ./$sudo mkdir programs/ 
  ./$cd programs/
 
### Open a file using Editor ###
  ./$sudo gedit first.c
  
## Example ##
./#include<stdio.h>
./int main()
./{
./printf("\n welcome to homepage!!\n");
./}

Save and Exit

## Compile ##
./$sudo gcc first.c

## Run ##
./$./a.out

### Running system tests ###

See [tests/README.md] (tests/README.md).

### Running in Vagrant ###

See[vagrant/README.md] (vagrant/README.md).

### Operating System ###
./Linux
  
	
