

# Introduction
From April 17 to June 9, 2023 (8 weeks), my objective is to carry out my internship within the company CIRCL, located at 122 Rue Adolphe Fischer, 1521 Gare Luxembourg. During this internship in the field of computer science, specifically in the network-oriented area, I have been involved in a large-scale international project called MISP.

CIRCL is a company specialized in computer security and a recently created organization in 2012, which has made the right choices to make a name for itself and become a major player in computer security in Luxembourg. It is not only recognized nationally but also internationally thanks to its projects, commitment, and efficiency. With Alexandre Dulaunoy as my supervisor, I have received the best explanations and necessary support for the smooth running of the beginning of this internship.

It has been a month since we started our mandatory two-month internship in a company as part of our second year of the University of Technology Bachelor's degree program. In my opinion, this experience is essential during our academic curriculum because it allows us to experience the working world in the field we have chosen to study.

As a promotion having followed the general or technological stream in high school, unlike the vocational stream, we did not have the opportunity to acquire professional experience directly related to our studies. Therefore, this experience is extremely important and enriching for us because it represents our first real professional experience. In addition, the addition of a subject to accomplish during this period makes the experience even more interesting.

My objective at the end of my internship is to successfully complete the subject I have chosen, which aims to improve the virtualization and orchestration of the training infrastructure. This involves updating several files that are now several years old while taking into account that modifying these files can cause other errors elsewhere. It is, therefore, a meticulous and quite complex task to accomplish.

The subject was proposed by the host organization to help us in case we encounter problems because most companies where students do their internships have an IT department or a person with IT knowledge. Given that the subject is proposed by the company, it may require the use of tools that we have not specifically used during our classes but will need to use. The allocation of the subject by the company is, therefore, essential to the smooth running of this experience.

Nevertheless, the choice of this internship and more specifically this internship subject is a real opportunity for me, having a real ambition to specialize in a field that interests me enormously, which is cybersecurity. Working with people who practice a profession in this specialty of computer science is truly exciting, and doing a project directly related to my future study choice is even more so.

To explain this beginning of my internship in a computer company better, I will present in detail everything I have done since my arrival by first presenting the title of my subject and the tools used. Then, I will delve into the subject by showing what I have done by dividing this large part into three distinct parts: one focusing on research, the other on the manipulations I have carried out, and the last on my progress. Finally, I will briefly conclude by giving my opinion on my internship.



# TOPIC

In order to properly explain my project in detail, I will first present to you the title of my internship and what was initially requested of me during its preparation.
Next, I will continue by presenting the tools that were made available to me, as well as the software that I was asked to use in order to complete my project.
Finally, I will conclude by presenting what I was able to accomplish during this first month and what still needs to be done.



## Title of the internship subject 

The title of the internship subject is as follows: "MSc Student Internship Position - Improvement of Virtualisation and Orchestration of Training Infrastructure." This translates to "Internship position for Master's student - Improvement of virtualization and orchestration of training infrastructure." As you may have noticed, the subject is not really adapted to my current level of study. However, when choosing an internship subject, it seemed to be the closest to what I wanted to undertake in my future studies. It could also be a real challenge for me, pushing me to exceed my limits and discover more things.

To succeed in this work, I have a number of tasks and skills to acquire. Firstly, I must be able to master the SCM (Source Control Management) Git. Secondly, I must be able to deploy and install the MISP threat intel infrastructure on a VM to actively contribute to this open-source project. Finally, I need to acquire skills in Bash and Unix scripting.

Having had the opportunity to manipulate Git during my teaching hours and having a basic understanding of Bash and Unix scripting in the first year of my computer science course, I have some skills to rely on, although my skills in Bash are still very limited.


## Tools and software provided

Of course, given the subject of my internship, I won't be using switches or routers or anything like that which we have practiced many times in advanced network labs, for example, but will be exclusively manipulating things through a computer like in virtualization classes, for example. Therefore, the only hardware tool provided to me is a laptop on which I work under Ubuntu 22.04. In terms of software, I have mainly been using Vagrant, VirtualBox, and Virtualbox.
Furthermore, I have used other tools following the wise advice of my supervisor, such as HedgeDoc which allows me to format and document daily tasks, while also giving my colleagues the opportunity to see my progress and make modifications to what I have done. However, this is not the only collaboration tool used. I have been suggested to use Element to communicate with each person or all of them at once, to get quick responses.
All of these tools will allow me to modify the misp-vagrant folder, which contains all the files I need to work on for my project.

Therefore, here is the set of tools that I had to learn to use:

- Vagrant is an open-source tool designed to manage the creation and configuration of virtual machines. It enables the configuration, creation, and management of virtual development environments that enable the execution of development and testing tasks, testing of applications, and any other manipulations that require the use of stable and reproducible development. It's a tool that allows us to create virtual machines from preconfigured models called "boxes". In short, it allows users to easily and quickly create a reproducible development environment, which would reduce configuration errors and facilitate collaborative work.

- VirtualBox: This open source operating system virtualization software allows our computer to create and manage virtual machines, offering the possibility of running and testing multiple operating systems on a single physical machine. Therefore, users can install different operating systems such as Linux, macOS or Windows. Each of these virtual machines has its own resources and configurations, and none of them has access to files that may be present on the host machine, which means that tests are completely isolated.

- HedgeDoc: This note-taking and collaboration application is an open-source project accessible via a web browser. It allows users to do multiple things, such as taking notes alone or collaboratively in real-time, as it is a collaborative tool. Additionally, it allows for the creation of tables, lists, Gantt charts, adding comments, and many other features while taking notes. Therefore, it is an easy-to-use online collaboration tool that offers multiple functionalities.

- Element: Element is an instant communication tool that allows its users to communicate through video and audio calls, as well as messaging, either individually or in groups. It is available on multiple operating systems and offers advanced features in terms of security and privacy.

- misp-vagrant: Misp-vagrant is a virtual development environment that has been specially pre-configured for the MISP cybersecurity incident prevention system. It allows for the creation and local installation of MISP for testing, of course, using a Vagrant-based virtual machine, so that it does not affect the host machine in any way.

- Markdown programming language to write my internship progress report.

Of course, I have also used other tools that I was familiar with, such as Git or the Bash programming language, in which I have some difficulties.

Due to the fact that there aren't many new hardware and/or software tools, one might instinctively think that learning to use these devices is not so complicated, but it is only when we get into the thick of things that we realize the difficulty, which we will analyze directly in the next section.


## What I have done

To successfully carry out my project, I decided to impose a chronology in the development of my work from the beginning of my internship. I noticed, when I was learning in school, that when we started a new "chapter", I tended to rush and didn't really take the time to understand the tools that I would be using. This often led me to quickly become lost in what I was doing and become distracted, and most of the time, it made me less productive than I thought I was.

That's why, for my internship, I decided to start with a solid foundation, without any rush. To do this, I first decided to devote a period of time to research on all the devices I would be using. Only after I judged that I had a "complete" understanding of what I had to do and use, could I move on to the practical phase of implementing this project. I will thus segment the explanation of the work I undertook during this first month into 3 main points. First, I will inform you about the research I undertook and why, then I will present everything I was able to do during the practical phase that I am currently in, and I will finally briefly present where I am in the progress of my project and what I plan to do for this second month.


### Research  

To successfully carry out my project, I decided to impose a chronology in the development of my work from the beginning of my internship. I noticed, when I was learning in school, that when we started a new "chapter", I tended to rush and didn't really take the time to understand the tools that I would be using. This often led me to quickly become lost in what I was doing and become distracted, and most of the time, it made me less productive than I thought I was.

That's why, for my internship, I decided to start with a solid foundation, without any rush. To do this, I first decided to devote a period of time to research on all the devices I would be using. Only after I judged that I had a "complete" understanding of what I had to do and use, could I move on to the practical phase of implementing this project. I will thus segment the explanation of the work I undertook during this first month into 3 main points. First, I will inform you about the research I undertook and why, then I will present everything I was able to do during the practical phase that I am currently in, and I will finally briefly present where I am in the progress of my project and what I plan to do for this second month.


### Practical phases

After properly researching, it is now time to move on to manipulation. As for my subject, the first step of my manipulation phase is to change the code files present in the misp-vagrant folder. In accordance with the above, I started by using VirtualBox with Vagrant, and then continued by modifying the files present in misp-vagrant. We are now getting into the heart of the matter. As I explained to you earlier, MISP is a platform for sharing knowledge about computer attacks and threats. misp-vagrant provides a pre-defined configuration for MISP deployment and contributes to this community by reporting bugs while proposing improvements.

The files that I need to modify in the scope of my project are already several years old. The evolution of recent years has only intensified, particularly in the field of computer science, which is a constantly expanding universe of knowledge. With all the advances that have been made, the new versions of all the tools used, the files that we currently have in our possession present a number of errors. My goal during these two months of internship will be to make the necessary modifications so that there are no more errors, which involves, for example, changing the versions of installed tools. If it were simply a matter of changing the installed versions of different tools, it would be quite fast, but we must take into account that updating these files can impact other linked files, and that is where the complexity of this project lies. Everything must be perfectly coordinated.

Let's go back to the skills I need to acquire or develop. We mentioned the use of bash and Unix scripting, but I haven't talked about it since the description of what I have done so far. Yet, it is one of the skills that I am currently using the most. The files present in the MISP-Vagrant folder that I need to modify are exclusively programmed in bash. Not being an expert in this programming language, I did some research and read a few books to consolidate my knowledge. As we know, having knowledge is very useful, but knowing how to use it correctly is even better.

So it was after that that the many tests really began (although tests had previously been carried out to start manipulating). I first started by locating the errors in order to try to neutralize them one by one. I quickly realized that trying to eliminate the errors one by one without taking into account the rest of the code was a bad idea. Everything is linked, which means that simply modifying a part of the code without taking into account the rest of the code can generate new errors. The work is therefore very meticulous and complex, which explains why file modification is the most time-consuming step.

I essentially need to proceed with the modification of two files, Vagrantfile and bootstrap.sh. So in the Vagrantfile, I tried to change the image in order to have version 20.04 of Ubuntu, which I succeeded in doing. If you are knowledgeable about Ubuntu versions, you must know that the latest version is 22.04 and it would seem more logical to install the latest version, but as I previously stated, the modifications must adapt to the other files in the MISP project and version 20.04 of Ubuntu is the most preferable in this case.

Now let's move on to modifying the bootstrap.sh file. This file is much longer than the Vagrantfile and requires much more modification, as it is from this file that the configuration is made with the installation of the tools, their launch, their configuration, and everything related to them. So I first tried to understand what each piece of code was for and started my tests by trying to modify everything in this list:
- Modification of the version of Python initially installed with an attempt to install versions 3.4, 3.5, 3.6, 3.7 and 3.8
- Code modification enabling the installation of MISP modules
- Code modification enabling the installation of Mitre's STIX
- Code modification enabling the configuration of PHP by default
- Code modification enabling the retrieval of CakePHP as well as the code enabling MISP.


### Progress and program

Regarding my progress, I would personally say that I am halfway through accomplishing my project. The most complex phase for me has been familiarizing myself with these tools and programming in a way that avoids errors. This requires a good mastery and understanding of the code and the tools.

Once this difficult part is completed, we can move on to documenting the code to explain the modifications made and why they were made. Once I have commented on all of these files, I can finally integrate my project into the larger MISP open source project. At that point, I will consider the project finished and, most importantly, successful.

In summary, I cannot say that the organization I have chosen for the smooth running of my internship is the best, but I can say that it is the most suitable for my case and will hopefully allow me to successfully complete my project under good conditions.

![Gantt chart created on HedgeDoc](///home/rawane/Pictures/Screenshots/Screenshot%20from%202023-05-10%2014-51-36.png)

# CONCLUSION

My feeling after this first month of internship is very positive for several reasons. Firstly, it allowed me to discover the world of work in the field in which I am studying. Having worked in the past as a student, I felt a real difference between these two worlds. Working in a field where we have accumulated a certain amount of knowledge that we can use effectively is extremely rewarding and encouraging. Learning new software and participating in the development of "real" projects in the sense that the company that welcomes me wants a result is a challenge that pushes me to excel, even if it can be complicated. Finally, all of this is supported by the fact that I had the chance to be in the middle of a very pleasant team, with colleagues who do not hesitate, from time to time, to come and see what I am doing and to offer me their help if needed. Moreover, some of these people do not speak French but exclusively English, which sometimes pushes me to improve my English while getting help with my work. That is why I can conclude that this first month of internship in the company is going very well for me.



















































