Automating the Smoke Tests for Control Center v2.0
S0D7
_______________________________________________________
Folder Structure is important

Make a folder <any name, here we call it Smoke Test Tools>
Inside it group ALL the .exe files
Inside it <Smoke Test Tools> create a folder called : buffer_folder
Inside it <Smoke Test Tools> create a folder called : reports
Inside folder reports [Smoke Test Tools > reports] create a file called : log.txt

For DAFW, download DAFW Resources, extract the folder and keep in the same folder as the Application
1. open Command Prompt in the concerned folder hosting the Application
2. Run .\DAFW_Smoke_Testing_tool.exe 
3. Note : It might fail - you will see the page load and no further action in that case
          For a proper activity, you will notice the page loading, cursor moving and process being performed
          If it fails, just go to cmd and re-enter the above provided command, no need to close browser or anything
          You might need to perform it a couple of times before it acts up
_______________________________________________________
After running the concerned .exe file
1. In the buffered_folder folder the screenshots are saved
2. In the log.txt the status is saved

3. In the reports folder the .word document is saved

