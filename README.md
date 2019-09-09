## Beer Recommendations Using Turi Create

Using Turi Create's Recommendation models to explore improvements to initial Beer Recommendation App. 

### Build

In order to use Turi Create on a Windows OS, jupyter notebook must be run through Ubuntu within a Linux sub-system.

First install WSL from Windows following the instructions on https://docs.microsoft.com/en-us/windows/wsl/install-win10.

After installing a Linux distribution, (Ubuntu, for example), must reinstall python through the Linux distribution.  
Install and create new virtual environment through WSL by running the following code:  
- Install  
`sudo pip3 install virtualenv`  
- Create and activate new environment  
`virtualenv <env_name>`  
`cd <env_name>`  
`source bin/activate`

Intall packages to be used
 - Pandas
 - Numpy
 - Jupyter Notebook
 - Scikit
 - Turicreate
 
 Locate folder in windows explorer for data files to be used in the Linux Subsystem  
 `C:\Users\<username>\AppData\Local\Packages\CanonicalGroupLimited.UbuntuonWindows_79rhkp1fndgsc\LocalState`  
 
 If adding files to WSL, must allow permission by the following code  
 `chmod 777 <file>`
