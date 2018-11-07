# lta-v1-system-software
Software for the control of the LTA board first fabrication.

###################################################
### Clonning repository to work with Xilinx SDK ###
###################################################
1) Create a SDK the usual way (Export Hardware and Launch SDK).
2) Create an application (Empty app) the usual way.
3) Navigate the Git Console to that location, where the src/ directory is.
4) git init to start a new empty git repository.
5) Register that repo with the remote GitHub repo:
-> git remote add origin https://github.com/leoeltipo/lta-v1-system-software.git

6) git pull 
7) git pull origin master
8) Now the files are already cloned. 
9) In Xilinx SDK, right click on project name and Refresh.
10) Add inc/ path in project settings.
11) That's it. Commit, push and pull the usual way from command line.
The first time:
-> git push origin master.
