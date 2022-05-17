# Hyungjun Doh's Week 6 Lab Report
* Streamlining ssh Configuration  
    
    * Show your .ssh/config file, and how you edited it (with VScode, another program, etc)  
    ![ssh Configuration #1](ssh_Configuration_%231.png)
    * Show the ssh command logging you into your account using just the alias you chose.  
    ![ssh Configuration #2](ssh_Configuration_%232.png)  
    * Show an scp command copying a file to your account using just the alias you chose.  
    ![ssh Configuration #3](ssh_Configuration_%233-1.png)  
    * Correct description of streamlining ssh configuration.
    In this task, we are going to make a .ssh file that would allow us to use "short cut" to loging in. By setting up the .ssh file with the known HostName and User Id, we can just use the alias "ieng6" by typing the following command.
        >> ssh ieng6

* Setup Github Access from ieng6  
    * Show where the public key you made is stored on Github and in your user account (screenshot).  
    ![from ieng6 #1](from_ieng6_%231.png)  

    * Show where the private key you made is stored on your user account (but not its contents) as a screenshot.  
    ![from ieng6 #2](from_ieng6_%232.png)  

    * Show running git commands to commit and push a change to Github while logged into your ieng6 account.  
    ![from ieng6 #3](from_ieng6_%233-1.png)  

    * Show a link for the resulting commit.  
    ![from ieng6 #4](from_ieng6_%234.png)
    [Link for the resulting commit](https://github.com/hdoh-ucsd/markdown-parser/commits/main/test-Ieng6.md)  
    
    * Correct description of setting up Github access from ieng6.  
    Remark that we have made the public key for the server log-in process. Now we are going to use to make another key to make access from the server to the github page. As we make our key in the server, we will copy and paste this to the github page SSH keys. Now that we have the screenshots that shows we have the private key stored on the server, git commands works properly, setting up Github access from ieng6 is done!  
* Copy whole directories with scp -r  
    * Show copying your whole markdown-parse directory to your ieng6 account.  
    ![with_scp-r_#1-1](with_scp-r_%231-1.png)    
    ![with_scp-r_#1-2](with_scp-r_%231-2.png)  
    * Show logging into your ieng6 account after doing this and compiling and running the tests for your repository.  
    ![with_scp-r_2](with_scp-r_%232.png)
    * Show (like in the last step of the first lab) combining scp, ;, and ssh to copy the whole directory and run the tests in one line.  
    ![with_scp-r_3](with_scp-r_%233-1.png)
    ![with_scp-r_3](with_scp-r_%233-2.png)
    * Correct description of copying whole directories.  
    In this task, we would use the specific commands for the scp command. First, we have use scp -r to copy whole directory to the server. In the lab, we have used this command to change only the modification with the part that we needed such as .class, .java, /lib ,etc. However, in this lab report, we would just use this command to practice whether if the .ssh file from part 1, would properly run in one line from the repository, not the server.