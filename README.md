# Vagrant 

#### a tool for building and managing virtual machine environments in a single workflow.

## Concepts

- __Using Vagrant on your local computer__

## Installation

#### Ubuntu

- Open the Terminal application:
	- Now you will execute command line in your Terminal (each of them start with `$`)
- Install VirtualBox: `$ sudo apt-get install virtualbox`
- Install Vagrant: `$ sudo apt-get install vagrant`
- Add the __Ubuntu 20.04 (Focal)__ image to your box list: `$ vagrant box add ubuntu/focal64` __Warning__: this step can take time.
- Create your first virtual machine:
	- `$ vagrant init ubuntu/focal64 `-> it will generate a Vagrantfile with base = `"ubuntu/focal64"` - you don’t have to execute this command line everyday, only once, to create a new virtual machine
	- `$ vagrant up` -> it will start your virtual machine
	- `$ vagrant ssh` -> now you are inside your virtual machine.

## Project Directories

| PROJECT                        | DIRECTORY | 
|  -----------                    |     -----------  |
|1. __vagrant__ |[0x00-vagrant](https://github.com/lebogangolifant/zero_day/tree/master/0x00-vagrant)|










## Acknowledgements

[ALX Africa](https://www.alxafrica.com/)


