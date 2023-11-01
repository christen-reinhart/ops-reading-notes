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

## Read: Class 05


## Windows Command Line Tools

Below you will find some reading material, code samples, and some additional resources that support today’s topic and the upcoming lecture.

This topic is important to aid in troubleshooting and gain a better understanding of interfacing through the CLI instead of the GUI.

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

## Things I would like to know more about

How to better utilize the different CLI interfaces to aid in troubleshooting.

## Weekly Partner Power Hour Report

You may find it difficult or challenging to connect with industry professionals and gain an inside look at how the tech world operates. We’ve drawn on our network to bring you speakers and topics relevant to this stage of your career transition. These presentations may serve to educate, enlighten, and motivate you along your journey. Take advantage of this opportunity, and make the most of the insights these presentations provide… you never know where a connection will lead.

## Instructions

If there is no live presentation on campus in this module, select the appropriate presentation from the list below.

All presenters are open to connections and invite you to reach out to them, so that you can learn more about them, their company, and the industry.

Presentations

Module	Topic	Speaker
01	Oops —- I did Git Again	Hexx King

## Assignment

## Contribute to the discussion:

Share one or two ways the speaker’s information will change your approach to your career transition.

Making sure my public profile represents good and professional values.

How to customize your profile in order to make you stand out to potential employers.

## List a few key take-aways from this presentation.

Share a screenshot of your LinkedIn connection request, including a nicely worded note, sent to the speaker or someone else at their company. 

Completed the task requesting a connection and took a screenshot.

## Instructor 1-on-1 Meeting

During the course, your instructor will work with you to schedule time for a brief in-person meeting.

Before you meet with your instructor, please answer a few questions so that we can make your time in this course as productive as possible.

## Reflection

Take a moment to reflect on:

1. What are your goals while taking this course?

To stay open minded and learn as much as possible to set me up for success in my future in cybersecurity.

2. Are there any areas of concern, questions about the course or adjustments we might consider?

I am having issues understanding the coding aspect of the course(Ops Challenges).

3. What professional proficiency would you consider to be your top strength?

Hard work and being willing to put in the time even if I don't understand something to gain a better grasp on the subject.

4. What areas of professional competency would you like to improve?

The coding and command line aspect of the course.

## Assignment

Please share your reflections here, for the instructional team to review prior to your 1-on-1 meeting.

My biggest concern is the limited amount of time in the day and the volume of information required to fully comprehend the material and apply it in a practical environment. 

On the positive side, I am consistently pushing myself to meet the standards of this course. So, I am pushing the envelope, and that is a good thing, considering that, from what I can see so far, I am managing well

## Learning Journal: Class 05
## Learning Journal

Today I Learned

One of the most effective tools in adult learning is reflection. By writing coherent summaries of lessons learned, we cement that learning and deepen our understanding of a subject. It also helps us to measure our progress.

You should probably only spend about 10-15 minutes on this assignment, although if you would find it helpful to invest more time, you are welcome to do so.

## Reflection

Write a brief reflection on your learning today, or use the prompt below to get started.

“Adults need to know why to learn something; as soon as they answer this question, they are ready to start.”

The why applies to both large-scale (learning web development as a new profession) and small-scale (learning a particular tool or technique), and your learning journal is an excellent place to identify and contemplate those whys. They are important. So… what is your why?

Learning a new skill or profession can open up opportunities for career growth and higher earning potential. Sometimes, the "why" is simply a deep interest or passion for a subject or field. Learning can lead to greater job satisfaction by allowing you to work on projects or in roles that align with your interests. Some people learn because it allows them to express their creativity and innovation. Learning a specific tool or technique may be driven by the need to solve specific problems or challenges.

## References

[Chat GPT](https://chat.openai.com/c/b2dc5c3a-5c88-4ed4-9b5f-1a90b0c0779d)

## Read: Class 06

## Windows Security Center

Below you will find some reading materials and some additional resources that support today’s topic and the upcoming lecture.

Review the Submission Instructions for guidance on completing and submitting this assignment.

## Readings

Windows Defender Security Center

What are the five main sections included in the Windows Defender Security Center, and what functionalities do they offer?

Virus & Threat Protection: This section is focused on protecting your computer from malware and other threats.
Device Performance & Health: This section helps you keep your device running smoothly and identify potential issues.

Firewall & Network Protection: Configure the Windows Firewall settings to control incoming and outgoing network traffic.
 App & Browser Control: You can configure SmartScreen settings to protect your device from potentially malicious apps and websites.
      e)   Family Options: If you're using Windows in a family environment, this section    provides parental control and monitoring features.

2. What information does the “Device performance & health” section provide, and how can you access it?

Health Report: Storage capacity, Battery life, Apps and Software, Windows Time Service, Fresh Start 

In Windows Security go to Device Performance and Health.

  3. How does the Windows Defender Security Center notify you of issues that require your    attention?

When there is a critical security issue or recommendation, Windows Security may display a pop-up notification.
The Windows Security system tray icon, which appears in the taskbar, may display a yellow exclamation mark when there are security issues or recommendations.

4. What features are managed under the “Firewall & network protection” section in the Windows Defender Security Center?

Domain network, Private network, Public network

5. How does the concept of “security” in Windows Defender Security Center relate to your own experiences in keeping your personal belongings safe? Share some strategies you use to protect your belongings and how they might parallel the security measures used in the digital world.

In the physical world, we use locks and keys to control access to our homes or private spaces. Similarly, in the digital world, access control is managed through usernames and passwords.
Firewalls in the physical world are barriers that prevent the spread of fires. In the digital world, firewalls act as barriers that control network traffic and protect your devices from unauthorized access or malicious activity.
In both worlds, having backups is crucial. In the physical world, we may make copies of important documents or store duplicates of valuable items.

## Things I want to know more about 

Troubleshooting Windows related issues and utilizing the CMD prompt.

## References

[Article](https://www.faqforge.com/windows/windows-10/what-is-event-viewer-and-how-to-use-it-in-windows-10/)

## Career: Class 06: Behavioral Interview Questions


## Behavioral Interview Questions

Read through this document on the S.T.A.R method, which is the style potential employers prefer and expect you to answer questions during a behavioral interview.

## Assignment

Ask a chatbot of your choice to ask you 3 behavioral interview questions, one at a time. Answer the provided questions in the S.T.A.R method and ask the chatbot to provide you feedback.

Tell me about a time when you had to meet a tight deadline. What was the situation, the specific task, the action you took, and the result?

One time at band camp I had to jump a small form-factor communications platform out of an aircraft to support communications on the ground afterwards in support of a COMEX. First I would have to find out the requirements which usually included SIPR and NIPR, data and VOIP with the ability to send an encrypted email for a SITREP on both enclaves. The communications platform had wireless capability so I could tether my phone as a primary means of connectivity and I would bring a BGAN for my secondary means of transport for the kit as part of my PACE plan. I would also bring an Iridium satellite phone just in case for a contingent means of communication and for troubleshooting. Next I would perform a complete inventory of my equipment for accountability and have an inventory sheet with SNs as part of my mission folder. Then I would identify an individual to jump the equipment with and how we would cross load the kit. I would then perform a complete OPS check of the equipment verifying all services and my cut sheets with system baseline configurations and IP schemes. Prior to packing the items I would make sure the batteries were changed and time our setup for proper standards. I would then draw all CCI(sensitive material) and COMSEC and get my courier orders in order to be able to move equipment off the compound. Once all the equipment was properly sorted out I would pack it according to my packing list and stage it in a secure area. I would then be responsible for giving a mission brief/ presentation to the commander and answer any related questions. Fast forward once exiting the aircraft and getting on the ground I would get accountability of my items and move to a cleared area. From there we would move into setting up the COMMS for the time standard which was usually 30 min and then send up my SITREPs via email with accountability of all personnel and equipment including CCI. 
                                                                                                                                                                                  
Can you share an example of a time when you had to work with a difficult team member or coworker? Describe the situation, the task at hand, the actions you took, and the outcome.

  I had to work with an individual who had issues being on time to PT formation. This would hold up the process of conducting physical fitness afterward. It hindered my ability to get accountability of personnel prior to moving out and conducting PT. It also impacted the additional personnel I was responsible for since it impacted their training as well. At first I verbally counseled him, basically giving him a warning. I then wrote him up after multiple offenses. After that I assigned him additional duties as part of corrective actions. This basically pissed him off and he would not participate in exercises essentially sandbagging and not trying. Eventually I pulled him to the side and spoke man to man asking him if there was something I needed to know about him that would help me understand his situation better. He informed me of some additional things going on with him which helped me be more understanding so I could work with him. After this I was able to report back to my chain of command to work something out for him within reason. After some time his personnel situation resolved itself and things were back to normal essentially. He was a good guy, we just had to dig a little deeper since he wasn't talking about what was going on with him.
 
Tell me about a situation where you faced a significant challenge or obstacle at work. How did you handle it? Please describe the situation, the task, the actions you took, and the results. 

Towards the end of my career in the Army I had differences of opinion with my boss to say the least. He wasn't very honest and didn't take care of his people. I butted heads with him and voiced my opinion and it essentially backfired. Myself and quite a few others tried to make people understand above him but the leadership backed him even though he was wrong in my opinion. For leadership to side with us instead of him would completely undermine his command even if he was wrong. Unfortunately I learned the hard way sometimes you have to pick your battles even if you feel you are right. In a normal job you would just quit; you can't do that in the military for the most part. I later told him I couldn't work for him anymore and to move me to another section. For the remainder of my time in the military I just kept quiet and did my time.

## References

[STAR Method](https://careerservices.wayne.edu/pdf/behavioralinterviewinfo.pdf)
[Chat GPT](https://chat.openai.com/c/b2dc5c3a-5c88-4ed4-9b5f-1a90b0c0779d)


[Chat GPT](https://chat.openai.com/c/b2dc5c3a-5c88-4ed4-9b5f-1a90b0c0779d)

[Windows Defender](https://www.thewindowsclub.com/windows-defender-security-center)

## Learning Journal 6

## Today I Learned

One of the most effective tools in adult learning is reflection. By writing coherent summaries of lessons learned, we cement that learning and deepen our understanding of a subject. It also helps us to measure our progress.

You should probably only spend about 10-15 minutes on this assignment, although if you would find it helpful to invest more time, you are welcome to do so.

## Reflection

Write a brief reflection on your learning today, or use the prompt below to get started.

“What motivates adults to find time for their learning in their busy schedule? Mostly intrinsic motivators.”

In other words, adults are motivated by internal forces rather than by external expectations, and your learning journal provides an outlet for considering and noting those internal forces. Which of your internal forces for learning can you concretely identify? 

I want to learn more about IT, plain and simple. I found myself getting stagnant in the role I was in and wanted to use the education benefits afforded to me through the VA to advance that objective. I almost feel foolish for not taking advantage of a free education. I really wish I had gone to college a long time ago, although it would not have been free at the time. After Code Fellows, I still want to advance my education further. This is just the beginning. My only worry is that by focusing specifically on education, I may lose the hands-on experience that work provides. That being said, many others are getting into the field with no experience, just Code Fellows. At the end of the day I just want to be good at what I do and to be appreciated for it while being compensated properly.

## Read: Class 07


## OS Upgrade and Remote Access

Below you will find some reading materials and some additional resources that support today’s topic and the upcoming lecture.

Review the Submission Instructions for guidance on completing and submitting this assignment.

## Reading

Should You Learn Powershell?

PowerShell is used by both defenders and attackers in the cybersecurity field. Understanding PowerShell can be valuable for security professionals to analyze and defend against potential threats.

Who needs malware? IBM says most hackers just Powershell through boxes now, leaving little in the way of footprints

PowerShell scripts can run directly in memory, making them less likely to be detected by traditional antivirus software. This "fileless" approach can help hackers avoid leaving easily detectable footprints on a system.

What is the difference between Bash and PowerShell?

Bash is the default shell for Unix-based systems, including Linux and macOS.
Bash uses a combination of built-in commands and shell scripting to automate tasks.
  PowerShell is the default command-line shell for Windows. PowerShell is a full-fledged scripting language that goes beyond simple text processing. 


In what scenarios or environments can you use PowerShell? Name some major platforms where PowerShell is supported.

PowerShell is widely used for system administration tasks on Windows servers and workstations. PowerShell is a powerful scripting language for automating repetitive tasks, such as software installations, system backups, and log analysis. PowerShell is integrated with Azure for cloud resource management. PowerShell is used for SQL Server administration and automation.

List at least three reasons why learning PowerShell could be beneficial for your career and environment. 

PowerShell enables the automation of routine, time-consuming tasks, which can significantly improve efficiency. In the event of a security breach or incident, PowerShell can be used to quickly respond, contain, and investigate the breach. PowerShell can help enforce security policies and configurations consistently across systems. Cybersecurity professionals often use PowerShell during penetration testing and red teaming exercises to simulate real-world attacks and assess an organization's security defenses.

How can PowerShell’s automation capabilities improve efficiency and reduce manual errors?
Think about a situation where you might use PowerShell in your everyday life or job. How could 
PowerShell helps you accomplish a specific task or solve a problem?

PowerShell allows you to automate repetitive tasks that you perform regularly.
PowerShell scripts can perform tasks much faster than manual execution. 
PowerShell provides robust error-handling mechanisms.
PowerShell can be integrated with task schedulers to run scripts at specific times or intervals. 

What is a Powershell attack?

A cyberattack technique in which an attacker leverages the PowerShell scripting and automation framework to carry out malicious activities on a target system or network. 

## References:

[What is PowerShell](https://learn.microsoft.com/en-us/powershell/scripting/overview?view=powershell-7.3&viewFallbackFrom=powershell-7)

[Getting Started with PowerShell](https://learn.microsoft.com/en-us/powershell/scripting/learn/ps101/01-getting-started?view=powershell-7.3&viewFallbackFrom=powershell-7)

[Powershell Variables and Operators](https://ss64.com/ps/syntax-variables.html)

[Chat GPT](https://chat.openai.com/c/b2dc5c3a-5c88-4ed4-9b5f-1a90b0c0779d)

## Things I would like to know more about

I would like to gain a greater understanding of power shells uses in automation and cybersecurity

## Learning Journal 7

## Today I Learned

One of the most effective tools in adult learning is reflection. By writing coherent summaries of lessons learned, we cement that learning and deepen our understanding of a subject. It also helps us to measure our progress.

You should probably only spend about 10-15 minutes on this assignment, although if you would find it helpful to invest more time, you are welcome to do so.

## Reflection

Write a brief reflection on your learning today, or use the prompt below to get started.

Motivation and goals are an important part of adult learning; so is adapting to and gaining insight from things you did not anticipate. What would you say is the most unexpected part of this experience, and how have you learned from it?

The most unexpected part of today was Lab 7. It was quite challenging and took me about 4 hours to complete. Some of this was my own fault; I went ahead accidentally before reimagining the Windows machine from 7 to 10. Once that was completed, I had some additional issues with the PowerShell commands. I was not aware that they were case-sensitive. I wish I would have had more of an idea about the amount of scripting and CLI that was involved, so I could be more prepared. I wish I would have had a better feel for how time-consuming this class would be. I am putting in about 12 hours a day on average just in class work. That does not include the reading for the CompTIA test coming up and the test questions we are responsible for. I am trying to be open-minded and flexible since this can replicate real-world scenarios. I am also trying to humble myself and be appreciative of the opportunity afforded to me through the VA and Code Fellows. I guess I will just keep doing my best and keep pushing the believe button.

## Read: Class 08

## Readings: System Log Analysis, Registry, Control Panel

Below you will find some reading materials and some additional resources that support today’s topic and the upcoming lecture.

Review the Submission Instructions for guidance on completing and submitting this assignment.

## Reading

## Windows Registry Demystified

What is the Windows Registry, and what does it store?

The Registry stores various settings related to the Windows operating system itself. Installed applications and software packages can use the Registry to store their own settings and configurations. User-specific settings, preferences, and customizations are stored in the Registry.

What are the two types of registry settings stored for each Windows user account?

HKEY_CURRENT_USER (HKCU): This hive stores user-specific settings and configurations. 
HKEY_USERS (HKU): This hive contains subkeys for all user profiles that have logged into the system.

What are “registry hacks” and why might someone want to use them?

Registry hacks can be used to personalize the Windows user interface. Some registry hacks can improve system performance by adjusting settings related to memory usage, file access, and system responsiveness. It's possible to enable or disable certain features in Windows using registry hacks.


What are some common tasks you can perform by editing the Windows Registry?

Change the desktop background, screensaver, and theme settings.
Customize the appearance of the taskbar, icons, and window borders.
Modify the appearance of folder icons and system fonts.



Imagine you’re explaining the concept of the Windows Registry to someone who has never used a computer before. How would you make this explanation culturally relevant and relatable to their life experiences or background? 

Imagine your computer is like a big, organized library, and the Windows Registry is like a special book in that library. This special book contains important information about how your computer works, almost like the secret recipe for your favorite family dish. Just like in a recipe, where you need the right ingredients and instructions to make a delicious meal, your computer needs the information in this book to work correctly.

## References

[Chat GPT](https://chat.openai.com/c/b2dc5c3a-5c88-4ed4-9b5f-1a90b0c0779d)

[Windows Event Viewer](https://www.faqforge.com/windows/windows-10/what-is-event-viewer-and-how-to-use-it-in-windows-10/)

## Things I want to know about

The different ways hackers can manipulate the registry or use it in cyber attacks.





# Ops 301: Networking and Systems Administration

- [ops-301-reading-01.md](ops-301-reading-01.md)
- [ops-301-reading-02.md](ops-301-reading-02.md)

# Ops 401: Cybersecurity Engineering

- [ops-401-reading-01.md](ops-401-reading-01.md)
- [ops-401-reading-02.md](ops-401-reading-02.md)
