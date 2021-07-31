# Add Logo to Easy Access Screen
   This repo lets you easily add a logo the the SAP Easy Access Screen.
## Table of contents
* [General info](#general-info)
* [Requirements](#requirements)
* [Setup](#setup)
* [Status](#status)
* [Contact](#contact)


## General info
> After installing SAP about 20 times for our DevOps architecture I decided to create this repo to easily update the logo. You'll likelly want to use your own logo so you will need to follow the setup steps.

## Requirements
In order to use this repo you need to have [abapGit](https://github.com/abapGit/abapGit) installed in the system you want to add the logo to.
You will need a logo that is appropriately sized, 500px x 500px worked well for us.
If you want to transport the logo, you will need to create a transport in the SAP system

## Setup
1. Fork repo
2. Replace logo in /src/znuve_logo.w3mi.data.jpg
> The name of your logo must be identical i.e. znuve_logo.w3mi.data.jpg
> Alternatively, you can update the references throughout your fork of the logo name if you want to use your own filename
3. Clone this repo in your SAP system using [abapGit](https://github.com/abapGit/abapGit)
4. Optional: delete the forked repo

## Status
Project is: _finished_

## Contact
Created by [@nesl9](https://www.nuvecommerce.com/) - feel free to contact me!
