#Build Flow Stats - A Jenkins Plugin 
##Introduction
A build in Jenkins can either be green, yellow or red depending on how the build went. When a build is red there is one or several issues that need to be fixed before the build can go green and thus becoming successful. When searching for reasons as to why the build failed one needs to go through the logs in search of the issues. This can be time consuming especially if you have several builds that are red. 

The plugin _Build Flow Stats_ was created in order to help Jenkins-users with this issue. The plugin searches every log that goes red or yellow in order to present the problems that led to the build-failure. The plugin also provides a list of the most common errors that appears in the logs. This can help the Jenkins-user prioritize problems that needs to be 
resolved.

![](http://i.imgur.com/2ziKLNZs.jpg) The logo for _Build Flow Stats_

##How to use the plugin
###Data Presentation
In the plugin _Build Flow Stats_ there is **Data Presentation**, there you can choose how far back you want to find info for builds. 

![](http://i.imgur.com/zeaFQXm.jpg)

After choosing how far back and which job to present you push the button **Present Data**.  

Afterwards the plugin will present this:

![](http://i.imgur.com/LZST8C1.jpg)

The number of successes, failures, aborts, unstables and not built builds will be shown as well what the failure rate is. Where it says _Unknown Failure Cause_ there will be the different failures with a link to the builds where the errors occurred in parenthesis.   
**Most Common Failure Causes** is where the most common 

###Data Deletion
The _Data Deletion_ section is there to let the plugin-user be able to remove builds easily.

![](http://i.imgur.com/cDoFijE.jpg)

###Add errors for the plugin to find 
The plugin is not prepared with errors that can appear in a log. The idea is instead that the plugin-user will add patterns for errors in the _Failure Analysis_. The patterns will let the plugin search through failed builds and find those patterns thus being able to recognize the different errors. 

![](http://i.imgur.com/xx5a723.jpg)

To add a problem in _Failure Analysis_ the pattern from the log for a specific error is added in the **Edit Failure Causes**. A name for the problem such as "Compile Error" for example is neccessary aswell as a decription for what the problem is.

![](http://i.imgur.com/7oOTP9P.jpg)

JAG HAR ÄNDRAT
