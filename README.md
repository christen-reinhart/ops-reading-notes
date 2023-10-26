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

## Learning Journal: Class 03

## Today I Learned

One of the most effective tools in adult learning is reflection. By writing coherent summaries of lessons learned, we cement that learning and deepen our understanding of a subject. It also helps us to measure our progress.

You should probably only spend about 10-15 minutes on this assignment, although if you would find it helpful to invest more time, you are welcome to do so.

## Reflection

Write a brief reflection on your learning today, or use the prompt below to get started.

“For adult learners, their experience becomes the main resource of both their learning and the personal identity they have developed, as the richer and more diverse their experience, the more the diversity they can bring to their own learning.”

In other words, your life experience in learning the things you did before learning code will make this new experience more meaningful for you, and reflection on all of your experiences is essential in maximizing what you can gain from your study at Code Fellows. How do you think your prior life and professional experience will help you in this new endeavor?

I think my previous experience in life will help in cybersecurity in the following ways. I was a mechanic for 10 years before I joined the military. This helped me learn how to figure out complex problems on my own and pay attention to detail. I joined the military after and was in communications for 10 plus years mostly satellite communications and networking. While in the military I was expected to know more than just my job and cross trained all the time. Most of this experience while in the service was tactical communications. Once I left the military I worked at a NOC for about 2.5 years as well assisting in trouble shooting communications on aircraft and tactical terminals. I think my career is pretty diverse and I am looking to branch off again with cybersecurity.

## Chat GPT assisted me below

Your previous experiences as a mechanic, a military communications specialist, and a NOC (Network Operations Center) technician have equipped you with a valuable skill set and mindset that can be highly beneficial in the field of cybersecurity. Here's how your diverse background can be an advantage:
1. Problem-Solving Skills: Your experience as a mechanic, where you had to diagnose and resolve complex issues, has honed your problem-solving skills. In cybersecurity, identifying and mitigating security threats often involves solving intricate problems, making your mechanical experience transferable.


2. Attention to Detail: Attention to detail is crucial in cybersecurity. Small oversights can lead to significant vulnerabilities. Your background in mechanical work and military communications, where precision is essential, can help you excel in maintaining and securing systems with meticulous care.


3. Cross-Training: The military experience of cross-training and being adaptable is invaluable in cybersecurity. Cyber threats are diverse and ever-evolving, so your ability to learn and adapt quickly is an asset when dealing with new security challenges.


4. Communication and Networking Expertise: Your extensive experience in satellite communications and networking is directly relevant to cybersecurity. Understanding network protocols, architectures, and vulnerabilities is a significant advantage when securing networks and data.


5. Tactical Communications: Tactical communications experience brings a unique perspective to cybersecurity. Military tactics and strategies can be applied to the defense of systems and information assets.
Critical Thinking: Your military service likely involved critical thinking in high-stress situations. In cybersecurity, this skill helps assess threats, vulnerabilities, and responses effectively.


6. NOC Experience: Working in a NOC gives you insights into network monitoring and incident response, which are crucial aspects of cybersecurity.
Diverse Skill Set: Your diverse background allows you to approach cybersecurity from different angles. You can understand the technical aspects of systems and also consider security from operational and strategic perspectives.


7. Adaptability: You've demonstrated adaptability throughout your career. In cybersecurity, where threats change rapidly, this adaptability is a vital trait.
Security Clearance: If your military role required security clearances, this can be a significant advantage in certain cybersecurity roles, especially in government or defense-related positions.
Your diverse career path has equipped you with a valuable set of skills, and it's clear that you're well-prepared to transition into the field of cybersecurity. Consider pursuing relevant certifications or further education in cybersecurity to complement your existing knowledge and skills. Your unique background can make you a valuable asset in the constantly evolving world of cybersecurity.

## Chat GPT link

https://chat.openai.com/c/b2dc5c3a-5c88-4ed4-9b5f-1a90b0c0779d

## Read: Class 04

## Troubleshooting Techniques

Below you will find some reading materials and additional resources that support today’s topic and the upcoming lecture.

Review the Submission Instructions for guidance on completing and submitting this assignment.

## Reading

CompTIA A+ 220-902 Troubleshooting Methodology

1. What should you do if multiple issues are happening simultaneously during troubleshooting?

Make sure you ask the customer a lot of questions to isolate the issue. Ask them if something has changed recently or if it is a recurring issue to narrow things down. Consider all possible scenarios and try to make a theory on the cause of the issue or issues.

2.What should be done once a successful solution has been identified during the troubleshooting process? 

Figure out how you will implement your solution and how it could affect the network. Come up with a process on what you will do if the solution does not fix the problem or something goes wrong and you may have to revert to the previous settings or configurations. Coordinate with other sections to make sure that it will not interfere with daily operations.

3. What are the benefits of documenting the entire troubleshooting process in a knowledge base?

Continuity, it is very helpful if this occurs again or it is necessary to reference for any other reason mainly to cover your behind. We had to document everything when I worked at the NOC even if just for the reason of justifying our job.

4. Think about a technological device particularly popular in your culture or community. Imagine a scenario where issues arise: how would you apply CompTIA A+ troubleshooting methodology to help, while considering the end-user’s cultural background? 

You may have to take into account how much experience an individual has with technology. My grandma for instance would ask me at times for help with her cell phone when she first got one. She kinda rejected the technology at first since she had a dial phone all her life. Some of the functions confused her at first and she did not like them. A few years later once she got familiar with the device she loved it, I just had to be patient with her due to her lack of experience with those types of devices.

## References

[CompTIA A+ 220-902 Troubleshooting Methodology](https://www.professormesser.com/free-a-plus-training/220-902/how-to-troubleshoot/)

## Things I want to know more about
I am interested in working smarter and not harder though proper troubleshooting methodology.


# Ops 301: Networking and Systems Administration

- [ops-301-reading-01.md](ops-301-reading-01.md)
- [ops-301-reading-02.md](ops-301-reading-02.md)

# Ops 401: Cybersecurity Engineering

- [ops-401-reading-01.md](ops-401-reading-01.md)
- [ops-401-reading-02.md](ops-401-reading-02.md)
