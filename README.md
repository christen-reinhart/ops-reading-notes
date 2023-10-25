# Ops 102: Intro to Computer Operations

- [Reading 1](https://www.google.com/search?q=install+vs+code+ubuntu&sca_esv=576343061&sxsrf=AM9HkKkakpreo4jp_-J7uD7lSwLkrIIy5w%3A1698200546952&source=hp&ei=4ns4ZcKRN_DUkPIP1MyjmAU&iflsig=AO6bgOgAAAAAZTiJ8sCbKAmoL8Rh7gvdwx47muf3AbAL&oq=&gs_lp=Egdnd3Mtd2l6IgAqAggAMgcQIxjqAhgnMgcQIxjqAhgnMgcQIxjqAhgnMgcQIxjqAhgnMgcQIxjqAhgnMgcQIxjqAhgnMgcQIxjqAhgnMgcQIxjqAhgnMgcQIxjqAhgnMgcQIxjqAhgnSIEJUABYAHABeACQAQCYAQCgAQCqAQC4AQHIAQCoAgo&sclient=gws-wiz)
- [ops-102-reading-02.md](ops-102-reading-02.md)
- [ops-102-reading-02.md](ops-102-reading-02.md)

# Ops 201: Foundations of Computer Operations

## How to Use System Restore

1. What is the purpose of the Windows System Restore tool?

- One of the primary purposes of System Restore is to help users recover data and  their system from software-related problems. If you make changes to your system, such as installing a problematic driver or software, and it leads to issues like performance problems or crashes, System Restore enables you to undo those changes. In some cases, malware or viruses can infect your system and cause damage. System Restore can help in recovering your system to a state before the infection occurred, removing the malicious changes made by the malware.

2. How long does it usually take to use the System Restore tool in Windows?

- Creating a restore point is usually a quick process and should only take a few minutes.The time it takes to restore your system to a specific restore point can vary. In many cases, it's a relatively fast process, typically taking 20-30 minutes. Your computer may need to be rebooted one or more times during the restore and update process, which can add to the overall time.

3. How do you start a System Restore from the command prompt?

- Access the Command Prompt:
Press Win + R to open the "Run" dialog.
Type cmd and press Enter to open the Command Prompt with administrator privileges. You'll need administrator rights to perform System Restore.
Run System Restore Command:
In the Command Prompt window, type the following command:
Bash 
rstrui.exe
Press Enter.
After running the command, the System Restore wizard should appear on your screen.

4. What options are available if System Restore did not fix the problem?

- If you have multiple restore points, try using a different one. Ensure your Windows operating system is up-to-date by checking for and installing the latest Windows updates.  If the issue started after installing new software or drivers, consider uninstalling those recent installations. 

- It is important to perform data backups in-order to maintain the integrity and availability of the information your business requires to perform day to day business.

### Things I want to know more about
- How to priorize and manage backups especially in a virtual environment.
### Resources 
- Utilized Chat GPT for reference and the website below.
- [Windows Restore Link](https://www.lifewire.com/how-to-use-system-restore-in-windows-2626131)

## Identify Your Accountability Partners

An accountability partner is a person who advocates for you to stick to your commitments, and keep moving towards your goals. Accountability partners help you stay motivated, highlight areas for growth, offer candid feedback, provide a sounding board, give emotional support, and are your cheerleaders. Learning how to be accountable for your actions leaves you with less room for excuses and procrastination.

## Assignment

Find 2 people in your current class to be your accountability partner.
Those two people should not be in your direct friend pool. They need to be people you are less casual around.

- Jason Dallas
- Raymond Mankin


### Once your two partners have accepted the role, please submit those two names in the assignment entry screen.

Your accountability partners will be responsible for checking your resume and your personal pitch in this course.


Allocate 10 minutes for this assignment

TA’s will be grading you on submitting 2 students names that are in your cohort

## What is Bash?

1. What is the primary function of a shell in a computer’s operating system? 

- Shells allow users to interact with the operating system by entering text commands. They provide a means for users to write scripts or batch files. Shells provide commands for creating, copying, moving, deleting, and managing files and directories.

2. How does Bash locate and execute commands on a Linux or Unix system? 

- It locates and executes commands on a Linux or Unix system through a process known as command execution. Bash reads the command from the input provided by the user. Then it parses the command line to understand what command you want to execute. 

3. How can you determine if your system is running a Bash shell?

- Type “echo” if your system is using Bash as the default shell, it will typically display "/bin/bash" or a similar path to the Bash shell executable. This command shows the name of the currently running shell. You can check the version of the Bash shell by typing “--version”.

4. What makes Bash scripting powerful and why is it considered scriptable?

- It is widely available on Unix like operating systems. Allows you to execute system commands and utilities directly from the script. Bash scripts can use variables to store and manipulate data. 

5. Bash scripting allows for customization, automation, and efficiency. Discuss methods or practices from your previous work experience or cultural background that aim to achieve similar goals in daily tasks. 

- Standard Operating Procedures (SOP’s) in my previous occupation(US Army) we used SOP’s all the time, SOPs are established to document and standardize processes, ensuring consistency and efficiency in daily operations.

The reason this topic is important to know is to understand the underlying systems that run and automate processes.

## References

- Chat GPT was used for reference
- [What is Bash Ref](https://opensource.com/resources/what-bash)

  ### Things I want to know more about:
- I would like to know more about Linux and the CLI.

## Learning Journal

## Today I Learned

One of the most effective tools in adult learning is reflection. By writing coherent summaries of lessons learned, we cement that learning and deepen our understanding of a subject. It also helps us to measure our progress.

## Andragogy vs. Pedagogy

1. Pedagogy:
Teacher-Centered: Pedagogy is often associated with traditional teaching methods where the teacher is at the center of the learning process.
2. Andragogy:
Learner-Centered: Andragogy is an approach that emphasizes the role of the learner in the educational process.

3. Maybe you’ve seen a graphic similar to this before? 
I have been in classes where the teacher was more of a facilitator and relied upon the combined knowledge of the class in-order for students to learn from each other. The teacher makes sure the students stay on topic and puts out specific material related to the course learning objectives. This was in a professional development class where most of the individuals were experienced in a common field and older.

## Kolb's Adult Learning Cycle (via psychologytoday.com)

This is a learning style model developed by researcher David Kolb and it is a core principle in the way our curriculum is designed and our instruction is delivered at Code Fellows. Note the “Reflective Observation” component; it is that piece that is a primary differentiator between the way adults learn and the way children learn.

As an adult, learning is different for you now than it was when you were younger. Do a quick read of this article that describes the differences between andragogy (adult-focused learning) and pedagogy (child-focused learning).

Over the duration of this course there will be a series of learning journal assignments where you will be prompted to reflect on your learning. The reflection is a critical part of adult learning, and the self-awareness that results is a key component of emotional intelligence. Initially, these journal assignments will give you prompts to get you started, but as time goes by some assignments will be less structured so that you explore your thoughts with more self-determination and freedom.

## Reflection

Write a brief reflection on your learning today, or use the prompt below to get started.

Consider the following quote from the article linked above:

“[Adult learners] are deeply involved not only in planning, but also in evaluating their learning, as they know what knowledge they want to acquire.”

In other words, you should continuously evaluate your learning, and your learning journal is an excellent way to keep track of that. How do you see yourself planning and evaluating your learning? What details will you record and/or measure? How often will you evaluate what you want to learn?

I have a clear goal in mind for this course: to gain a better understanding of cybersecurity. Although I've been in the IT career field for some time, this specialty is somewhat different. Right now, I'm focused on establishing a solid rhythm and following directions. I'm absorbing all the information presented here and conducting my own research through webinars with SANS Institute and YouTube videos. I also have friends from the military who are either already in the field or just starting out. Using the insights I gain from them, I'm trying to better assess where I'd like to end up and map out a career path, taking advantage of the benefits available to me through the VA.

I'm in the process of determining the most effective learning path while maintaining relevance in the field. I'm considering whether to continue working or return to school to maximize my education. Additionally, I'm working on deciding which job in the cybersecurity field I'd like to pursue (such as a SOC Analyst/Blue Team position) so I can tailor my training plan accordingly.
This class is just the beginning of building a strong knowledge base for me at the moment.

##References

- Chat GPT assisted me with spelling and grammar.

## Issue tracking system

Below you will find some reading materials and additional resources that support today’s topic and the upcoming lecture.
Review the Submission Instructions for guidance on completing and submitting this assignment.

## Reading
  
Introduction to Help Desk Support Roles

1. What role does the help desk professional play within an organization, particularly in relation to customers?
   
- Help desk professionals are often the first point of contact for customers who have technical issues or questions. They diagnose and troubleshoot technical issues, whether they are related to software, hardware, or network problems. Help desk professionals document their interactions with customers, which includes noting the steps taken to resolve issues. They keep customers informed about the progress of issue resolution, expected timelines, and any additional steps that may be required. 

2. The article differentiates between hard and soft skills. In your culture or community, are there specific skills that are highly valued? How do they compare to the skills mentioned in the article?

- As technology plays an integral role in contemporary society, digital literacy and the ability to use and adapt to technology are highly valued. In an ever-changing world, the ability to adapt to new circumstances, learn quickly, and be flexible in one's approach is highly regarded. Effective communication, including verbal and non-verbal communication, active listening, and the ability to convey ideas clearly, is often highly valued.

3. Why have security skills become more important in recent years for help desk technicians?

- The digital landscape has seen a significant increase in cybersecurity threats, including malware, ransomware, phishing, and data breaches. When a security incident occurs, help desk technicians may be involved in the incident response process, which includes identifying the breach, containing it, and reporting it.Customers and clients expect organizations to protect their data and privacy.  Help desk professionals are often the first point of contact for employees seeking assistance. 


4. How do writing skills and critical thinking skills play a vital role in the work of help desk technicians?

- Well-organized and clear documentation is vital for tracking issues, sharing knowledge within the team, and creating a knowledge base. Help desk technicians often communicate with customers and colleagues through written communication, such as emails, ticket updates, and documentation. 

## References

- I used Chat GPT for spelling and grammer corrections.
- [Helpdesk Roles Link](https://www.pearsonitcertification.com/articles/article.aspx?p=2260779&seqNum=5)

## Things I would like to know more about

- I am pretty familiar with helpdesk, I think it is a good role to use for learning experience





- [Things I want to know more about](https://opensource.com/resources/what-bash)
- [ops-201-reading-02.md](ops-201-reading-04.md)
- [ops-201-reading-02.md](ops-201-reading-05.md)
- [ops-201-reading-02.md](ops-201-reading-06.md)

# Ops 301: Networking and Systems Administration

- [ops-301-reading-01.md](ops-301-reading-01.md)
- [ops-301-reading-02.md](ops-301-reading-02.md)

# Ops 401: Cybersecurity Engineering

- [ops-401-reading-01.md](ops-401-reading-01.md)
- [ops-401-reading-02.md](ops-401-reading-02.md)
