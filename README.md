# sstart
A secure app launcher that helps to split your Desktop to several users. 

This Application is using sudo, socat, nc along with a bunch of shellscripts to start applications as different users. 

While using you will get a bunch of USER-ENVIRONMENT users for example zem-firefox or zem-icedove you can use the sstart tool to simply start an app: 

sstart ENVNAME COMMAND
sstart firefox firefox

sstart icedove icedove

The disadvantage is: less security compared with solutions using xen or kvm (like qubes) or lxc
The advantages: 
  - Higher Performance than a fully virtualized environment. 
  - it does even work on a desktop already running in a VM or LXC container. 

