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

## Ops Challenge: Class 08
## Ops Challenge - Windows Batch Scripting

It could be said that batch scripts are to Windows as bash scripts are to Linux. If you’re using basic Windows terminal commands (non-Powershell), then a .bat file is the way to go!

## Objectives

Students will learn how to use the ROBOCOPY command to perform recursive file copy operations.

## Resources

How to Use Windows Batch File Commands to Automate Repetitive Tasks
Wikibooks: Windows Batch Scripting

## Tasks

## Part 1: A Batch File. Your job is to document every single line of the batch file in detail. Explain what is happening.

## @echo off: 


- This command turns off echoing of executed commands to the console, making the script output cleaner by not displaying each command.


## setlocal enabledelayedexpansion: 


- This command enables delayed environment variable expansion, which is useful when working with variables in loops or code blocks.


## set /p sourcePath=Enter the source folder path:: 


- This line prompts the user to enter the path of the source folder and stores the input in the sourcePath variable.


## set /p destinationPath=Enter the destination folder path:: 


- Similarly, this line prompts the user to enter the path of the destination folder and stores the input in the destinationPath variable.


## if not exist "!sourcePath!\": 


- This line checks if the source folder specified by the user exists. If it doesn't exist, it displays an error message and exits the script using the goto :eof command.


## if not exist "!destinationPath!\": 


- Similar to the previous line, this checks if the destination folder exists and displays an error message if it doesn't.






## robocopy "!sourcePath!" "!destinationPath!" /E: 


- The core of the script, this command uses Robocopy to copy the contents of the source folder to the destination folder. The /E flag tells Robocopy to copy subdirectories, including empty ones.


## if errorlevel 8: 


- After the Robocopy operation, this line checks the error level returned by Robocopy. If the error level is 8 or higher, it indicates that Robocopy encountered errors during the copy operation. In this case, the script displays an error message.


## else: 


- If no errors are detected by Robocopy (i.e., the error level is less than 8), the script displays a success message indicating that the copy operation was completed successfully.


## :end: 


- This is a label used to indicate the end of the script. It's typically used with the goto command for exiting the script.


## endlocal: 


- This command marks the end of the local environment variable scope defined by setlocal. It ensures that any environment variable changes made within the script are discarded when the script ends.


## Part 2: Push to GitHub

Since your Ops Challenge repository is stored locally on your Ubuntu, the most convenient way to submit the assignment is by logging in to GitHub on your Windows VM.

Once you have successfully logged into your GitHub profile on the Windows VM, create a new file in your Ops Challenge repository. Copy and paste your batch script into the new file and save it with the appropriate file extension.

Before you can ACP changes from your Ubuntu Server again, make sure to synchronize the changes you made while using the Windows VM to avoid conflicts. To achieve this, run git pull from the terminal before you begin any new tasks in your local repository on your Ubuntu. Help your team with this today as it may be a little confusing.

## Learning Journal 8

## Today I Learned

One of the most effective tools in adult learning is reflection. By writing coherent summaries of lessons learned, we cement that learning and deepen our understanding of a subject. It also helps us to measure our progress.

You should probably only spend about 10-15 minutes on this assignment, although if you would find it helpful to invest more time, you are welcome to do so.

## Reflection

For this journal entry, no specific prompt other than to start off with “Today I learned…” or “Recently I learned…” and go from there.

Today, I learned to collaborate with others to achieve a common goal. This experience was particularly unique due to the virtual nature of our learning process. I believe it all worked out well, and we not only learned about event viewers but also delved into system log analysis and explored the process of restoring the system after manipulating the registry, which was quite fascinating. I had been somewhat frustrated yesterday, but working with others helped take my mind off it, as we all found common ground.

## Read: Class 09


## Readings: Workstation Deployment SOP

Below you will find some reading materials and some additional resources that support today’s topic and the upcoming lecture.

Review the Submission Instructions for guidance on completing and submitting this assignment.

## Reading

So, You Want to Write an SOP?

What is a Standard Operating Procedure (SOP), and why is it important for an organization?

A standard operating procedure (SOP) is a company-specific procedure detailing the steps required to perform a specific task. Writing an SOP involves both a scientific and artistic approach, and there are various methods for creating them, some more preferable than others. SOPs range from minimalist to novel-length, and the consequences of poorly written or absent SOPs can be significant.

What are the three types of documents that should be included in an SOP manual? Briefly describe each type.

Core Procedures: These documents outline the fundamental processes and tasks necessary for the operation of a specific function, department, or organization. They provide detailed step-by-step instructions on how to perform critical tasks.
Policy Documents: These documents define the rules, regulations, and guidelines governing the organization's operations. Policies set the context within which procedures are executed and provide a framework for decision-making.
Supporting Documents: These documents offer supplementary information that enhances the understanding and execution of core procedures. They may include flowcharts, checklists, forms, and reference materials.


Why are SOPs considered a primary way to implement or enforce policies in an organization?

Policies serve as the guiding principles that direct an organization toward the accomplishment of its mission, vision, and goals. However, without Standard Operating Procedures (SOPs), these policies remain theoretical and lack actionable guidance. SOPs play a crucial role in translating policies into practical actions. They promote uniformity and consistency in executing tasks, which is essential for demonstrating adherence to the benchmarks set in service level agreements. In essence, SOPs provide the tangible steps and instructions needed to operationalize organizational policies effectively.

What does the author emphasize regarding the audience when writing SOPs, and why is it essential to consider them?

That the audience is typically made up of employees who will execute the procedures outlined in the SOPs. It is crucial to consider the audience because the clarity, simplicity, and comprehensibility of the SOPs directly impact their ability to understand and follow the procedures effectively. 

Imagine you are a part of a multicultural team responsible for following an SOP. How would you address potential misunderstandings or differing interpretations of the procedure due to cultural differences? Propose strategies to foster effective cross-cultural communication.

Ensure that the SOPs are as clear, detailed, and unambiguous as possible.
Offer training and education sessions that explain the SOPs and provide an opportunity for team members to ask questions.
Promote cultural awareness and sensitivity within the team. 
Recognize that different cultures may have alternative ways of approaching tasks. 

## Learning Journal 9

## Today I Learned

One of the most effective tools in adult learning is reflection. By writing coherent summaries of lessons learned, we cement that learning and deepen our understanding of a subject. It also helps us to measure our progress.

You should probably only spend about 10-15 minutes on this assignment, although if you would find it helpful to invest more time, you are welcome to do so.

## Reflection

Write a brief reflection on your learning today, or use the prompt below to get started.

Consider the “learning pyramid" as shown in the image below. Do you find that matches the way that you learn, or would you weigh the activities differently? If so, how?

The more involved you are in the learning process the better your retention of the information. When I learn hands on I retain the information longer and understand it better. If I am just listening to a lecture I can have a tendency to zone out. If I know I am responsible for teaching others, not only do I have to know the material myself, I need to be able to break it down to others in a way that they will understand.


## Things I want to know more about

Proper formating and use of references in a SOP

## References

[What is a SOP](https://www.thinkhdi.com/library/supportworld/2017/you-want-to-write-an-sop)

[Chat GPT](https://chat.openai.com/c/b2dc5c3a-5c88-4ed4-9b5f-1a90b0c0779d)


## Learning Journal 9

## Today I Learned

One of the most effective tools in adult learning is reflection. By writing coherent summaries of lessons learned, we cement that learning and deepen our understanding of a subject. It also helps us to measure our progress.

You should probably only spend about 10-15 minutes on this assignment, although if you would find it helpful to invest more time, you are welcome to do so.

## Reflection

Write a brief reflection on your learning today, or use the prompt below to get started.

Consider the “learning pyramid" as shown in the image below. Do you find that matches the way that you learn, or would you weigh the activities differently? If so, how?

The more involved you are in the learning process the better your retention of the information. When I learn hands on I retain the information longer and understand it better. If I am just listening to a lecture I can have a tendency to zone out. If I know I am responsible for teaching others, not only do I have to know the material myself, I need to be able to break it down to others in a way that they will understand.


## Read: Class 10

## Imaging, Backup, and Recover

Below you will find some reading materials and some additional resources that support today’s topic and the upcoming lecture.

Review the Submission Instructions for guidance on completing and submitting this assignment.

## Reading

1.What is Backup and Disaster Recovery and Why Do You Need It?

Backup and disaster recovery (BDR) involves duplicating and preserving files in a designated location. This ensures that files can be restored or retrieved in case of emergencies, like data loss or corruption. Although backup and disaster recovery are distinct, they are interrelated concepts that organizations should consistently address in tandem.

2.What is Backup and Disaster Recovery (BDR), and why is it essential for businesses?

BDR helps protect critical business data from various threats such as hardware failures, data corruption, accidental deletions, and cyberattacks. In the event of a disaster or significant system failure, BDR allows businesses to continue operations with minimal downtime. By having a robust BDR strategy in place, businesses can mitigate risks associated with data loss and business disruptions. 

3.Describe the process of data backup in detail.
Assessment: The process begins with identifying and categorizing the data that needs to be backed up.
Selection of Backup Method:
Full Backup: A complete copy of all selected data is created during each backup cycle. While this provides comprehensive coverage, it can be time and resource-intensive.
Incremental Backup: Only new or modified data since the last backup is copied. This approach conserves storage space and reduces backup time.
Differential Backup: Similar to incremental backup, but it copies all changes since the last full backup. This means that each backup after the initial full backup contains all changes.


Scheduled Backups: These are automated and occur at specified intervals, such as daily, weekly, or monthly.
Backups: Data is copied to storage devices physically located in the same place as the source system. This can include external hard drives, network-attached storage (NAS), or local servers.
Encryption: To protect sensitive data during transit and storage, encryption is often used.
Verification and Integrity Check: After each backup, data integrity should be verified to ensure that the backup is complete and error-free.
Testing and Recovery Planning: Regularly test the backup and restore processes to ensure data recoverability. 
Versioning: Some backup systems support versioning, allowing users to recover data from multiple points in time.
Documentation: Keep detailed records of backup procedures, schedules, and policies.
Employee Training: Ensure that employees understand backup policies and their role in the data protection process.

4.What does disaster recovery refer to, and why is it crucial to have it in addition to data backups?

Disaster recovery (DR) refers to the process and set of strategies and tools an organization uses to recover and restore its IT systems and data following a catastrophic event or disaster. The goal of disaster recovery is to minimize downtime, data loss, and service disruptions and restore critical systems to their normal operation as quickly as possible.

5.What is cloud backup and recovery, and how does it enhance data security?

Cloud backup and recovery, often referred to as cloud-based backup and recovery, is a data protection and disaster recovery strategy that leverages cloud computing services to store, back up, and restore data and applications. It enhances data security through several key mechanisms

6.In some cultures, the concept of data privacy is highly valued, while in others, sharing 
information openly is considered normal. How might these cultural norms affect the way individuals approach data backup and disaster data recovery? Provide examples to support your response.

Privacy-Conscious Cultures: In cultures where data privacy is highly valued (e.g., Western countries like the United States and European nations), individuals are more likely to prioritize data security.
Collectivist Cultures: In collectivist cultures (e.g., many Asian cultures), group welfare often takes precedence over individual privacy. Companies in such cultures may focus more on ensuring business continuity and disaster recovery to protect the interests of the collective.
Natural Disaster-Prone Cultures: Cultures residing in regions prone to natural disasters, such as Japan or the Philippines, may have a well-established culture of disaster preparedness. 

## Bookmark and Review

Article - How to Get started with Veeam Free Edition Veeam Agent for Microsoft Windows Free User Guide

## References

[Windows User Guide](https://www.veeam.com/documentation-guides-datasheets.html?productId=42&version=product%3A42%2F162) 

[Backup Disaster Recovery](https://www.ninjaone.com/blog/what-is-backup-and-disaster-recovery-and-why-do-you-need-it/) 

[Chat GPT](https://chat.openai.com/c/b2dc5c3a-5c88-4ed4-9b5f-1a90b0c0779d) 

## Things I would like to know more about

The processing of assessing and planning for a disaster recovery and business specific strategies for modeling one.

## Learning Journal: Class 10

## Today I Learned

One of the most effective tools in adult learning is reflection. By writing coherent summaries of lessons learned, we cement that learning and deepen our understanding of a subject. It also helps us to measure our progress.

You should probably only spend about 10-15 minutes on this assignment, although if you would find it helpful to invest more time, you are welcome to do so.

## Reflection

Write a brief reflection on your learning today, or use the prompt below to get started.

Read this short article on Imposter Syndrome. On a scale from 1 (least) to 10 (most), to what extent do you experience these feelings? Have you always felt the way you do now? If you have successfully lowered the number you’d use to rate your Imposter Syndrome, how have you done so?

Imposter Syndrome is a common experience, and the intensity of these feelings can vary from person to person. I have experienced moments of self-doubt and feelings of inadequacy, but the degree to which can differ over time and in various circumstances or the situation. It's not unusual for people to struggle with Imposter Syndrome at certain points in their lives, especially as they face new challenges or responsibilities.
To lower the level of Imposter Syndrome, individuals can take several steps, such as acknowledging their achievements and abilities, seeking support and guidance from mentors or peers, reframing negative thoughts, practicing self-compassion, and maintaining a growth mindset. It's essential to recognize that addressing Imposter Syndrome is an ongoing process, and it may require different strategies for different individuals. The key is to develop self-awareness and constructive habits to build confidence and overcome self-doubt.



## References

[Unmasking Imposter Syndrome](https://asana.com/resources/impostor-syndrome) 

[Chat GPT](https://chat.openai.com/c/e7817477-48cf-4b9a-8ac7-7dc17247a571) 

## Read: Class 11


## Data Restoration, Startup Repair, and Secure Disposal

Below you will find reading materials and some additional resources that support today’s topic and the upcoming lecture.

Review the Submission Instructions for guidance on completing and submitting this assignment.

## Reading

Solarwinds MSP: SSD Data Recovery Best Practices

What are some common indicators that an SSD may be failing?
SSDs can overheat if cooling is insufficient or if they are near the end of their lifespan.
Files and folders may suddenly disappear or become inaccessible, indicating potential data loss.
SSDs can develop bad blocks over time, causing data errors and instability. 

How do SSD failures differ from HDD failures in terms of detectability?
HDDs often produce audible sounds like clicking, grinding, or whirring when they're failing, making the issue more noticeable.
HDDs can slow down significantly when they start to fail, causing slower read and write operations. 
SSDs generate less heat, so overheating may not be as common as an indicator of failure.

What are bad blocks in an SSD, and how do they affect its performance?
Bad blocks in an SSD (Solid State Drive) are sections of memory cells that have become defective and are no longer reliable for storing data.
When an SSD detects a bad block, it will typically mark it as "unusable" and avoid using it for data storage. 
As bad blocks accumulate, the SSD may experience higher error rates during read and write operations, leading to system instability and increased likelihood of data loss.

How can power cycling an SSD help resolve certain issues?
Some SSD firmware updates may require a power cycle to apply changes effectively.
In cases where an SSD becomes unresponsive or data becomes inaccessible, power cycling can sometimes provide a temporary window to recover data before more serious issues develop.

How might this topic be relevant in the aftermath of a natural disaster? Describe how individuals or communities can use these techniques to recover data and resume their normal activities.

Depending on the natural disaster it may be better to have a SSD as opposed to a HDD.
Depending on the environment in general it may be better to have one or the other even though server rooms are climate controlled.
Depending on the application SSD’s are known for only being able to be written over so many times.
If you were looking to transfer data to a remote site SSD would transfer data faster.
HDD’s are more susceptible to damage to shock and being moved around due to moving parts.

Bookmark and Review

How to Erase a Hard Drive Using DBAN

References
[Erase Hard Drive](https://www.lifewire.com/how-to-erase-a-hard-drive-using-dban-2619148) 
[Data Recovery](https://www.n-able.com/blog/ssd-data-recovery-best-practices) 
[Chat GPT](https://chat.openai.com/c/e7817477-48cf-4b9a-8ac7-7dc17247a571) 
## Things I want to know more about
What does Solarwinds know about data recovery? I thought they had the worst hack in US history, but chat GPT said it was the OPM (Office of Personnel Management) hack.

## Career: Class 11: Give Your 60 Second Professional Pitch


## Give Your 60 Second Pitch

Being able to introduce yourself in a professional manner speaks volumes about you. Use these resources to learn how to create your personal-professional pitch. Aim for your pitch to be 30 to 60 seconds.

## Effective public speaking

How to create a professional pitch: Guide I and Guide II

Be prepared to utilize your personal pitch on project demo day when introducing yourself. Use these questions to guide you as you write.

What were you doing before you decided to change careers?

Why did you decide to learn Software Development?

Why did you pick this specific skill?

Ideal environment you’d use this skill?

Previous experiences that give a boost to your new career in tech?

## Assignment

Submit a written version of your 60 second pitch, using the suggested guidelines.

I'm Christen Reinhart, and my professional journey has revolved around network management, system administration, and satellite communications for over a decade. However, my passion for technology and its crucial role in safeguarding digital environments prompted me to shift my focus to the realm of cybersecurity.

Prior to embracing this change, my responsibilities involved ensuring the reliability, security, and performance of IT infrastructure in high-pressure, dynamic settings. I developed a profound understanding of IT communications principles, practices, and troubleshooting methods, which I'm eager to apply in the cybersecurity field.

I made the choice to specialize in cybersecurity because I'm deeply committed to protecting digital assets and data from evolving threats. Through rigorous training and certifications, I've acquired skills in threat detection, penetration testing, and incident response, equipping me to defend against cyber adversaries.

I'm seeking an environment where I can employ my cybersecurity expertise to address complex security challenges and fortify organizations against cyber threats. My background in IT, complemented by my cybersecurity skills, positions me to contribute effectively to securing digital landscapes.

In summary, my transition to the cybersecurity field is propelled by a fervent dedication to preserving the integrity of digital assets. With a strong foundation in IT and newfound expertise in cybersecurity, I'm ready to play a vital role in enhancing digital security and ensuring a safer cyber landscape."

Reference 

[Chat GPT](https://chat.openai.com/share/789a577e-7138-4619-943c-c69a2f21cd14) 

## Learning Journal: Class 11

## Today I Learned

One of the most effective tools in adult learning is reflection. By writing coherent summaries of lessons learned, we cement that learning and deepen our understanding of a subject. It also helps us to measure our progress.

You should probably only spend about 10-15 minutes on this assignment, although if you would find it helpful to invest more time, you are welcome to do so.

## Reflection

For this journal entry, no specific prompt other than to start off with “Today I learned…” or “Recently I learned…” and go from there.

Today I learned endpoint configuration and how to use powershell to configure different processes using the CLI. I also learned data recovery and how to properly delete data from a HDD and the importance of doing it properly. We also worked as a group again with a different group this time. This was a learning experience within itself since it was different individuals with different ideas so I got a different perspective. I went over my 60 second pitch which I have heard of during my transition out of the military. It was called an elevator pitch then though.

## Read: Class 12


## Virtualizing a Router with pfSense

Below you will find some reading materials and additional resources that support today’s topic and the upcoming lecture.

Review the Submission Instructions for guidance on completing and submitting this assignment.

## Reading

## Introduction to pfSense

List some popular uses for pfSense.

pfSense can set up a captive portal for wireless hotspots, which requires user authentication or acceptance of terms of service before granting access.
pfSense offers robust firewall capabilities to protect your network from unauthorized access and threats.
You can use it as a DHCP server to automatically assign IP addresses to devices on your network and as a DNS server to resolve domain names to IP addresses.

What are the hardware requirements for setting up a pfSense router?

pfSense can be installed on a wide range of hardware, from old PCs to embedded devices, giving users the flexibility to build customized network appliances to meet specific requirements.

Where can you find support options for pfSense users?

Users have access to a helpful community through forums, mailing lists, and IRC for free support. Additionally, pfSense has commercial support available for enterprise users who require professional assistance and services.

How can you access the automatic configuration backup utility in pfSense?

In the "Config History" tab, you can set up the automatic configuration backup settings. You can specify how often you want the configuration to be backed up, where the backups will be stored, and how many backups to retain. 

Reflect on the importance of cultural awareness in the field of network security and administration. How might cultural differences influence decision-making and problem-solving when dealing with virtual routers and firewalls, like pfSense, in a global context?

Since it is very flexible and cheaper, pfsense could be open to a wide variety of applications, individuals and markets.

## Reference

[PF Sense](https://turbofuture.com/computers/Introduction-to-pfSense-An-Open-Source-Firewall-and-Router-Platform) 

[Chat GPT](https://chat.openai.com/share/e5db4e2a-4f61-40a7-bff0-aa99dff41a51) 

## Things I would like to know more about

How effective this product actually is on a live network?

What are the best applications, most likely a small business of some sort or individuals on a limited budget.

## Accountability Partners Review

## Refining your Resume

Once your resume matches our guideline outlined here, have your accountability partners review your resume and give you feedback on how well it matches the guideline. Make a copy of your resume and send it to your accountability partner for suggested edits. Integrate those suggested changes onto your original resume and then DELETE the copy.

A note on feedback: Whenever possible, provide a balance of positive and negative feedback. If you consistently give only positive or negative feedback, people will distrust the feedback and it will become useless. Remember to highlight what you liked on their resumes while also sharing ways for them to improve.

Also, remember to make ALL changes in the original resume document emailed to you when you enrolled, to be sure you are updating the official file that is in our database—this file is what we will be sharing with partner companies once it is approved by your Instructor in 401.

## Assignment

When the suggested edits are implemented, upload here a PDF of the latest version.

Allocate 20 minutes to this assignment

TA’s will be grading this assignment by comparing your first submitted resume with the new submission, noting effort made towards improvement, and ensuring it matches the provided guideline.

It was recommended to remove my satellite communications and 82nd Airborne culinary experience. This way it would be more focused on Cybersecurity and I have achieved 2 more Coursera cybersecurity certificates. I will be working with my mentor from ACP through the VA as well to remove some of the military terminology.

## Learning Journal 12

## Today I Learned

One of the most effective tools in adult learning is reflection. By writing coherent summaries of lessons learned, we cement that learning and deepen our understanding of a subject. It also helps us to measure our progress.

You should probably only spend about 10-15 minutes on this assignment, although if you would find it helpful to invest more time, you are welcome to do so.

## Reflection

Write a brief reflection on your learning today, or use the prompt below to get started.

There’s an old saying: “Experience is what you get when you don't get what you wanted.” What strategies do you use for learning from disappointments (both big and small) so that the next experience becomes productive and positive?

I actually learn best from my mistakes because learning the hard way drives things home for me. I learn most effectively through hands-on experience and associative learning. I tend not to forget when I struggle through a problem or an issue, as it often involves a lot of repetition and starting over from scratch. I have a tendency to lose focus during presentations since they are generally not very engaging. That being said, when I learn something through experiencing disappointment or being let down, I usually want to avoid feeling that way again.

## Read: Class 13

## Cloud Virtualization with AWS
Below you will find some reading materials and additional resources that support today’s topic and the upcoming lecture.
Review the Submission Instructions for guidance on completing and submitting this assignment.
## Reading
 Virtualization in the Amazon EC2 Cloud
How has virtualization evolved beyond desktops and servers?
Virtualization is a key enabler in creating hybrid and multi-cloud solutions, allowing organizations to seamlessly move workloads between different cloud providers or on-premises environments.

In the context of the Amazon IaaS Cloud Service Model, what does EC2 stand for?
In the context of Amazon Web Services (AWS), which is an Infrastructure as a Service (IaaS) cloud service provider, "EC2" stands for "Elastic Compute Cloud." The term "elastic" in EC2 emphasizes its ability to easily scale up or down based on the user's requirements, allowing them to pay only for the compute capacity they use.

What types of storage does EC2 use, and how is EC2 web traffic managed?
Auto Scaling allows you to automatically adjust the number of running EC2 instances based on the demand for your application. ELB is a service that automatically distributes incoming application traffic across multiple EC2 instances. EFS provides scalable and shared file storage that can be attached to multiple EC2 instances simultaneously.
What are the benefits of service-oriented architecture for customers of EC2 virtualized services? Scalability SOA allows customers to adjust their services independently.
Analyze how cloud virtualization can promote equitable access to technology resources across diverse populations. How can this technology bridge cultural gaps and empower underserved communities? 
Cloud providers are increasingly committed to sustainability. Cloud services can aid in disaster recovery and resilience planning. Cloud computing can create economic opportunities for underserved communities by enabling them to offer digital services, access e-commerce platforms, and participate in the digital economy.
## Video
EC2 Video Only
## Bookmark and Review
[Cloud Security for Dummies]((https://www.dummies.com/wp-content/uploads/Privileged-Access-Cloud-Security-For-Dummies-Thycotic-Special-Edition.pdf)) 
Be sure to read this article to be prepared for our in-class discussion in Class 14:
Reference
[AWS Cloud Practitioner](https://explore.skillbuilder.aws/learn/course/external/view/elearning/1990/aws-cloud-practitioner-essentials-core-services)
[Google Learned From Its Quest](https://www.nytimes.com/2016/02/28/magazine/what-google-learned-from-its-quest-to-build-the-perfect-team.html) 
[Virtualization in the Amazon EC2 Cloud](https://explore.skillbuilder.aws/learn/course/external/view/elearning/1990/aws-cloud-practitioner-essentials-core-services)
[Chat GPT](https://chat.openai.com/share/f052cd99-1c5a-4b48-a879-261c354fa2ec) 
## Things I want to know more about
Cloud services and cybersecurity, I watched a Sans Inst.  webcast and the different dynamics that go into protecting services in the cloud is interesting.


# Ops 301: Networking and Systems Administration

- [ops-301-reading-01.md](ops-301-reading-01.md)
- [ops-301-reading-02.md](ops-301-reading-02.md)

# Ops 401: Cybersecurity Engineering

- [ops-401-reading-01.md](ops-401-reading-01.md)
- [ops-401-reading-02.md](ops-401-reading-02.md)
