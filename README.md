# Log Analysis
This is small application created to provide summery of Log files specially Maximo Log Files

 This program is developed Nagesh Telange , Primary purpose is analysis of IBM Maximo logs and generate summerized report to get statistics of Logs.
 Total Memory Value is default set 6442450944L to avoid interruption of program while writing analysis report file
 however developers can upgrade as per business need.
 It is Limited to scan one file at a time and provide analysis for the same to run smoothly and consume less memory.
 
#### Prerequisite:
Require JAVA 8 or higher version to run this program. System must be already configured with environment variable to execute programs.
Full access granted to presentworking directory where program will be executed.

#### Steps :
1) Open Terminal or Command Prompt 
2) provide path till folder where Analysis.jar is present 
3) Exeute jar using java command 
`$java -jar Analysis.jar`
4) Program will prompt details for path of SystemOut File 
`Enter File path for analysis [Provide detail with file] :`
        Provide complete path file log file
        
`C:\Users\ironman\Documents\Projects\SystemOut.log` In windows

or


`/home/ironman/Documents/Projects/SystemOut.log` In Unix/Linux

```
*************************Welcome to Log Analysis**********************


You can perform below Operation :
         1. Show all Errors
         2. Show all Warnings
         3. Show all Debugs
         4. Show Memory Utilization
         5. Show WorkOrder MBO Counts
         6. Show Service Request Count
         7. Show MBS SET Counters
         8. Number of Used Connection
         9.Prepare Log analysis with all details
         10.exit
		 
 Press Enter Number to Continue :
```
 

5) Provide input to view related details in Terminal or Command 
6) if press option 9, System will generate file 'Log_Analysis.txt' consiting all options from 1 to 8 in single file
7) Open Log_Analysis.txt to view details systematically 
  
#### Limitation :
1) Need to access/execute  via termial or command compt only, Lack of GUI
2) Only one file will scan at time
3) Total Memory value is set to 6442450944L to avoid interuption while generating file
4) Folder and Access exceptions are not handled hence complete path of file need to provide and access of folder has to be provided prior execution.
