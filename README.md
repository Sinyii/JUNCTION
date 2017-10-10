# JUNCTION
1. download "junction" http://technet.microsoft.com/en-us/sysinternals/bb896768.aspx <p>
2. move all the .exe files to your "system32" directory<p>
3. uninstall you google chrome and remove the google folder in the program file<p>
4. make sure you have make this directory in your target drive: "D:\Program Files\Google"<p>
5. use cmd(administor) to execute: junction "C:\Program Files (x86)\Google" "D:\Program Files\Google"<p>
6. install google chrome
7. now your google file will be saved in "D:\Program Files\Google", and the folder "C:\Program Files (x86)\Google" just a shadow folder of it.<p>
*list 3 and 4 are important!<p>
*remove junction point: "junction -d "C:\Program Files (x86)\Google"
