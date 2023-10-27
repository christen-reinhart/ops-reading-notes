# seattle-ops-201d14-reading1
## How to Use System Restore

1. What is the purpose of the Windows System Restore tool?

One of the primary purposes of System Restore is to help users recover data and  their system from software-related problems. If you make changes to your system, such as installing a problematic driver or software, and it leads to issues like performance problems or crashes, System Restore enables you to undo those changes. In some cases, malware or viruses can infect your system and cause damage. System Restore can help in recovering your system to a state before the infection occurred, removing the malicious changes made by the malware.

2. How long does it usually take to use the System Restore tool in Windows?

Creating a restore point is usually a quick process and should only take a few minutes.The time it takes to restore your system to a specific restore point can vary. In many cases, it's a relatively fast process, typically taking 20-30 minutes. Your computer may need to be rebooted one or more times during the restore and update process, which can add to the overall time.

3. How do you start a System Restore from the command prompt?

Access the Command Prompt:
Press Win + R to open the "Run" dialog.
Type cmd and press Enter to open the Command Prompt with administrator privileges. You'll need administrator rights to perform System Restore.
Run System Restore Command:
In the Command Prompt window, type the following command:
Bash 
rstrui.exe
Press Enter.
After running the command, the System Restore wizard should appear on your screen.

4. What options are available if System Restore did not fix the problem?

If you have multiple restore points, try using a different one. Ensure your Windows operating system is up-to-date by checking for and installing the latest Windows updates.  If the issue started after installing new software or drivers, consider uninstalling those recent installations. 

It is important to perform data backups in-order to maintain the integrity and availability of the information your business requires to perform day to day business.

### Things I want to know more about
#### Resources 
Utilized Chat GPT for reference and the website below.

https://www.lifewire.com/how-to-use-system-restore-in-windows-2626131



# seattle-ops-201d14-career-class01
## Identify Your Accountability Partners

An accountability partner is a person who advocates for you to stick to your commitments, and keep moving towards your goals. Accountability partners help you stay motivated, highlight areas for growth, offer candid feedback, provide a sounding board, give emotional support, and are your cheerleaders. Learning how to be accountable for your actions leaves you with less room for excuses and procrastination.

Assignment

## Find 2 people in your current class to be your accountability partner.

Those two people should not be in your direct friend pool. They need to be people you are less casual around.

- Jason Dallas
- Raymond Mankin


Once your two partners have accepted the role, please submit those two names in the assignment entry screen.

Your accountability partners will be responsible for checking your resume and your personal pitch in this course.


Allocate 10 minutes for this assignment

TA’s will be grading you on submitting 2 students names that are in your cohort


# seattle-ops-201d14-reading2

## Reading

## What is Bash?

The reason this topic is important to know is to understand the underlying systems that run and automate computer processes.

1. What is the primary function of a shell in a computer’s operating system? 

- Shells allow users to interact with the operating system by entering text commands. They provide a means for users to write scripts or batch files. Shells provide commands for creating, copying, moving, deleting, and managing files and directories.

2. How does Bash locate and execute commands on a Linux or Unix system? 

- It locates and executes commands on a Linux or Unix system through a process known as command execution. Bash reads the command from the input provided by the user. Then it parses the command line to understand what command you want to execute. 

3. How can you determine if your system is running a Bash shell?

- Type “ echo $0 ” if your system is using Bash as the default shell, it will typically display "/bin/bash" or a similar path to the Bash shell executable. This command shows the name of the currently running shell. You can check the version of the Bash shell by typing “--version”.

4. What makes Bash scripting powerful and why is it considered scriptable?

- It is widely available on Unix like operating systems. Allows you to execute system commands and utilities directly from the script. Bash scripts can use variables to store and manipulate data. 

5. Bash scripting allows for customization, automation, and efficiency. Discuss methods or practices from your previous work experience or cultural background that aim to achieve similar goals in daily tasks. 

- Standard Operating Procedures (SOP’s) in my previous occupation(US Army) we used SOP’s all the time, SOPs are established to document and standardize processes, ensuring consistency and efficiency in daily operations.

## References

- Chat GPT was used for reference
- [Bash Reference Link](https://opensource.com/resources/what-bash)

### Things I want to know more about: 
- I would like to know more about Linux and the CLI.

## Learning Journal

## Today I Learned

One of the most effective tools in adult learning is reflection. By writing coherent summaries of lessons learned, we cement that learning and deepen our understanding of a subject. It also helps us to measure our progress.

You should probably only spend about 10-15 minutes on this assignment, although if you would find it helpful to invest more time, you are welcome to do so.

## Reflection

In other words, understanding your motivation for learning contributes to the effectiveness of your learning, and your learning journal is a place to explore those thoughts. What are your motivations for learning?

I am motivated to steer my career in a new direction, transitioning away from the world of satellite communications and moving closer to the realms of networking and system administration. Within the vast landscape of IT careers, I find cybersecurity particularly appealing and esteemed. This field encompasses a multifaceted range of IT disciplines, including coding, networking, system administration, and the critical art of monitoring and interpreting data using SIEMs (Security Information and Event Management systems).
My intention is not to depart from the IT field but to leverage my prior experiences and educational benefits offered through the VA to embark on a journey that aligns more closely with my evolving career aspirations. Cybersecurity, with its dynamic and constantly evolving nature, offers the perfect opportunity for me to utilize the knowledge and skills I've gained in the past while also expanding my expertise and contributing to the vital task of safeguarding digital landscapes.
## References
[Chat GPT](https://chat.openai.com/c/b2dc5c3a-5c88-4ed4-9b5f-1a90b0c0779d)

## Read: Class 05


## Windows Command Line Tools

Below you will find some reading material, code samples, and some additional resources that support today’s topic and the upcoming lecture.

Review the Submission Instructions for guidance on completing and submitting this assignment.

## Reading


How can you list the files in the current directory using the command prompt?

Press Win + R to open the "Run" dialog.
Type "cmd" and press Enter, or
Search for "Command Prompt" in the Start menu and open it.
To list files in the current directory, simply use the dir command:




How might the “sfc” command and the “gpupdate” command help in troubleshooting on 
            Windows?
         
 sfc (System File Checker):
Purpose: The "sfc" command is used to scan and repair corrupted or missing system files on a Windows system.
When Windows system files become corrupted or are missing, it can lead to various issues, including system instability, application errors, and system crashes.


  gpupdate (Group Policy Update):
Purpose: The "gpupdate" command is used to refresh Group Policy settings on a Windows computer. Group Policy defines various settings and configurations for Windows systems within a network.
In a networked environment, Group Policy settings play a crucial role in controlling security, user, and system configurations.




What advantages does the “robocopy” command offer over the “xcopy” command, and why is it useful for file transfers in certain situations?

Robocopy is specifically designed for robust and reliable file copying. It is more resilient to network interruptions and system failures.

Robocopy offers a wide range of options and switches that allow you to customize the copying process. You can control factors like file attributes, timestamps, and directory structures.

Think about any real-life scenarios from your cultural context where the use of command line tools could be beneficial. Describe one such scenario and explain how a specific command line tool would help address the situation.

I frequently use 'ipconfig' and 'ping' in troubleshooting. 'ipconfig' is particularly helpful for identifying the local computer's IP address. I used it recently to successfully complete the previous lab, allowing me to determine the IP address needed for Remote Desktop Protocol (RDP) access to the VM.
'Ping' is one of the most valuable troubleshooting tools for an IT technician when it comes to testing network connectivity. Once you have the IP address you're trying to reach, you can use 'ping' to verify connectivity.
## References

[Chat GPT](https://chat.openai.com/c/b2dc5c3a-5c88-4ed4-9b5f-1a90b0c0779d)

[Professor Messer](https://www.professormesser.com/professor-messer-archives/220-1002/microsoft-command-line-tools/)



# seattle-ops-201d14-reading3
# seattle-ops-201d14-reading4
