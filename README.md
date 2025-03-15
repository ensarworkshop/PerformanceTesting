# PerformanceTesting
PerformanceTesting
Steps to Install JMeter

**How to Download and Install JMeter for Windows?**

**What is JMeter?How to Download and Install JMeter?Conclusion**
Performance testing is the need of the hour for any organization.
It is not always possible to perform manual performance tests, and this is when the need for a performance testing tool comes in.
JMeter is the most trusted performance testing tool in the industry. Here, in this demo, you will learn how to download and install JMeter onto your system.

**What is JMeter?**
JMeter is an open-source testing tool that analyzes and measures the performance of software and products.
The tool is entirely Java-based and ensures performance testing, load testing, and functional testing. 

Earlier, JMeter was originally developed for web applications but has now expanded to several other functions. 

Let’s have a look at the process to download and install JMeter:

There is just one prerequisite for downloading and installing JMeter: to have Java installed in your system.

**1. Check if Java Is Installed**
Open the command prompt
Put the command java -version
Java_Version

If you have Java installed in your system, the command will show the version of Java installed, 
else, before going forward with the installation of JMeter, you must install Java.
**2. Download JMeter**
To download JMeter go to the Apache JMeter website
https://jmeter.apache.org/download_jmeter.cgi

On the website go to the binaries section and download the zip file
Wait for the zip folder to be downloaded
Apache_JMeter

**3. Install JMeter**
Once the zip folder is downloaded, go to the folder location, and then extract the zip folder
Once the folder is extracted go inside that folder and then go inside the bin folder here
In the bin folder open the jmeter.bat file
Batch_File

It will take a while to open, and this is how you can download and install JMeter onto your system. 

Now when you have installed JMeter, you can execute a test for the same.

Get Mentored by Leading Java Experts!
Full Stack Java DeveloperExplore ProgramGet Mentored by Leading Java Experts!

**4. Create the First Test Plan **
The first step in creating the test plan is 

Adding a Thread Group
Open the JMeter window
The window is divided into two parts. The left side has all the added elements, while the right side has all the elements' configurations.
Rename the test plan and save it
Now, rename it as the FirstJMeter.
Right-click on the test plan.
Go to add -> Threads (Users) -> Thread Group
Adding_Threads_JMeter

Now, once you click on the Thread Group, there are three things on the screen that are important concerning the load test:

The number of threads (users):
This is the number of threads or users JMeter will simulate.

Let's make it 100.

Ramp-Up Period (in seconds):
This is the time that JMeter takes before starting the thread over.

Let’s keep this as 12.

Loop Count:
This is the number of times the test will be executed.

And this one, let's leave it to be 1.

Thread_Group_JMeter

The next step is to 

Add an HTTP Request
Right-click on FirstJMeter and again go to add
In the drop-down select samplers
These are all the types of requests that JMeter can work on.

For now, choose the simplest of them all, the HTTP request. 
Here you will have to give the address to some home pages or websites.

Http_Requests

Now, rename it to be HomePages.

Here, in the Server Name or IP box, you have to give the server name or the IP.

Copy the URL : qa.porting.com/login
Come back to the JMeter window and paste it into the Server Name box. 
Don't give HTTP or HTTPS since these are protocols that will come in the other box. They will be automatically taken in the HTTP request case.

Then in the path dialog box, leave a forward slash there.
IP_Address

Now, when the HTTP test is ready, the next step is to perform the test on it. To perform the test:

Add Listeners 
To determine what the results of the test will be, you need to add some more test elements.

Right-click on FirstJMeter
Go to listener options
Listeners_In_JMeter

In the box that appears, there are different types of reports that JMeter provides.

For now, select the two of these: 

View results in table
View results tree
Run the test
Now, save the test and run it
For running the test, click the green button
Now, check the results of the test
Go to view results in table
View_Results_In_Table

You can see the green status that shows that the test was successful. The label name: FirstJMeter and the sample time can be seen. 
Then check “view results in a tree”
View_Results_In_Tree

The green status or the success status can be seen here as well. 

The test will be performed concerning the number of users, the ramp-up period, and the loop count set up in the first step. 

Hence, here on the screen, it is evident that the test is still running. The time is taken, the number of tests being performed, and the status of each hit onto the Simplilearn website can be seen.

And this is how performance testing is performed with the help of JMeter.
