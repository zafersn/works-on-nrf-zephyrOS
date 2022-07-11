CONTENT-LIST
=================
<!--ts-->
  * [ The directory could not be found](#1-the-directory-could-not-be-found)
  * [ west: error: invalid choice: 'build'](#t2-west-error-invalid-choice-build)
  <!--* [ To see dtb file located path](#)
  * [ To see dtb file located path](#)-->
  
<!--te-->

# 

<br><br><br><br>


### **1. The directory could not be found** 

if you get the directory ... could not find error, do in order,
```
The directory "c:\Users\TR\Documents\GitNetfeasa\IoTPass\hello_world" could not be found.
```

* Go File => preferences => settings => Select worksapce tab under the search box => nRF Connect
* Delete that folder from the list of applications (A list of paths to applications that should be shown as part of this workspace.)
* reboot VS code.


### **2. west: error: invalid choice: 'build'**

there are some reasons causing this errors: 

 **changing**
* workspace locations
* nrfsdk locations

to fix it,
1. try setting by selecting default nrf-sdk location c:\ncs\v2.0.0
2. if it is not work the attempt below.  right-click your project and start a new terminal here, then specify the workspace path and execute the command "west init"


