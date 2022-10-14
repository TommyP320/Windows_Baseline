# Windows_Baseline

   **AllHosts.csv:**    This is a file that is in .csv format and has the host information for machines on your network.  Make the necessary changes as it pertains to you.
  
   **Autorunkeys.txt:** This is a file that has a list of well known auto run key locations on a Win10 Registry. Make the necessary changes as it pertains to you.
  
**NOTE:** 
These scripts are set up to be run in the directories they exist. This will make all the reference locations work. 
   For example, if you want to run the "compare_baseline_accounts" script, then your prompt should look similar to:
           
     PS C:\Users\TommyP320\Documents\03_Compare_Baseline_Scripts>
           
   If you want to change the locations, just ensure that all relative paths in your scripts are edited to show new locations!

To run Invoke-Commands (ICM) for remote powershell execution, you will need to enter domain/user name and password credential in the remote session login popup window.
