# Vagrantfile for andular development
## Introduction
If user use vagrant enviroment for development angular on Windows,  
user will encount some trouble(e.g. symbolic error).  

This vagrant file avoid these trouble using yarn and winnsd  

# usage
Install winnsd  
```
vagrant plugin install vagrant-winnfsd
```
And up vagrat  
```
vagrant up
```
You can use share folder '/vagrant' for develop angular.
