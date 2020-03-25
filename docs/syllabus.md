---
layout: page
title: Syllabus
subtitle: CSCI-4850/5850 High-Performance Computing (Spring 2020)
---

## Overview

### Catalog Description

High-performance computing (HPC) refers to a specialized use of processor features, multiple cores, memory, graphic cards, accelerators, clusters, supercomputers, and everything from software to hardware to speed up computations. This course introduces state-of-the-art HPC technologies and parallel programming skills for them. 

### Class Meeting Time/Location

**Time**: Tue, Thu 12:45 pm - 2:00 pm  
**Where**: Ritter Hall R115 (Linux Classroom)
**Online lectures via Zoom will begin starting with Monday, March 23 by COVID-19**: Join [https://slu.zoom.us/j/583209984](https://slu.zoom.us/j/583209984) or by phone (Meeting ID: 583 209 984)

### Instructor
Tae-Hyuk (Ted) Ahn, Ph.D.  
Assistant Professor  
Department of Computer Science  
Program of Bioinformatics and Computational Biology  
*Email*: taehyuk.ahn@slu.edu  
*Office*: 305 Ritter Hall (Lab: 302 Ritter Hall)  
*Phone*: (314) 977-3633  
*Office Hour*: Mon 10 am - 12 pm, Tue 3 pm - 4 pm or appointment by email

### Credits/Pre-requisites
**Credits**: 3 Credits  
**Pre-requisites**: CSCI 2100 (required); CSCI 3100 and CSCI 3500 recommended.  
(Exceptions if non-cs major students have strong programming skills and computer/numerical concepts with enthusiasm for learning HPC)  
**Overall requirements: Students will be expected to have knowledge of algorithms and data structures, and linear algebra at an undergraduate level. Students are expected to be proficient in either Python, C, C++, or FORTRAN. Students should also be familiar with the Unix/Linux environment.  

### Topical Outline
Main topics include basic HPC hardware architectures, parallel programming languages, new trends of HPC, and more. The contents of the course provide a balance of theoretical and practical aspects in parallel computing. A student of this course is expected to develop the right skills to design parallel applications and to effectively use modern HPC platforms.
* Introduce High-Performance Computing (HPC)
* Profiling applications for run time and parallel speed-up
* Brief introduction of computer organization and HPC architecture
* Shared-memory programming with OpenMP
* Distributed-memory programming with MPI
* MATLAB Parallel Computing Toolbox
* GPU programming with OpenACC (optional: CUDA)
* Cloud Computing and Apache Spark


### Student Learning Outcomes

After successfully complete this course, students are expected to:
* Understand fundamental concepts and new trends of high-performance computing
* Optimize software to take advantage of processor feature
* Design, implement, and analyze programs via OpenMP for shared-memory system
* Design, implement, and analyze programs via MPI for distributed-memory system
* Learn ability to decide optimization or parallelize of existing applications to
* Utilize MATLAB parallel computing toolbox and parallel in R
* Understand the concept and implement simple GPU programs with OpenACC (or CUDA) 
* Learn cutting-edge cloud computing techniques using Amazon AWS and Apache Spark


## Course Materials and Resources

### Textbook
No textbook is required for this course. Assigned materials will be posted on class website. Optional reference books are as below:

* An Introduction to Parallel Programming by Peter Pacheco (Morgan Kaufman, 2011, ISBN:978-0123742605).
* Introduction to High Performance Computing for Scientists and Engineers by Georg Hager and Gerhard Wellein, 1st Edition (Chapman & Hall/CRC Computational Science , ISBN-13: 978-1439811924)
* Introduction to Parallel Computing by Ananth Grama, George Karypis, Vipin Kumar, and Anshul Gupta (Addison-Wesley, 2nd edition, 2003, ISBN:978-0201648652).
* Principles of Parallel Programming by Calvin Lin, and Larry Snyder (Addison-Wesley, 2008, ISBN:978-0321487902).Bioinformatics and Functional Genomics 2nd or 3rd Edition by Jonathan Pevsner (Hoboken, N.J. : Wiley-Blackwell, c2009)


### Course website
[https://biohpc.github.io/CSCI4850S20/](https://biohpc.github.io/CSCI4850S20/) will be used to announce schedules, slides, assignments, and news.

### GitHub
Please follow my GitHub [https://github.com/BioHPC](https://github.com/BioHPC). Course repository is [https://github.com/BioHPC/CSCI4850S20](https://github.com/BioHPC/CSCI4850S20) and Couse Webpage is [https://biohpc.github.io/CSCI4850S20/](https://biohpc.github.io/CSCI4850S20/)

### Jupyter Notebook (Jupyter Lab)
- [https://jupyter.org/](https://jupyter.org/)
- [https://jupyterlab.readthedocs.io/en/stable/](https://jupyterlab.readthedocs.io/en/stable/)

### Blackboard:
Blackboard could be only used for posting grading scores. 

### Email
Face-to-face contact in class and in office hours is most desirable. Yet email is a convenient form of communication as well. I try to respond to email promptly, including at least once each evening when possible. Email contact over the weekend will likely be more sporadic, although I will be sure to check at least once.

If your question involves your progress on a current programming assignment, my response will be more informative if you can point out the specific problem you have encountered, and if I am able to see all of your source code. Therefore I strongly suggest that you either attach all relevant files to the email or submit preliminary versions of such files through git system.

### Computer and Cell Phone Policy
Computers (laptops) will be an integral part of this course, both inside and outside of class. However, out of courtesy to both the instructor and other students, please do not use the laptops or computers for non-class related activity. In particular, you do not need to be using a computer unless an exercise or in class activity requiring them is in progress.  

You are unlikely to need cell phones during the course of lecture. Please ensure that your cell phone is set to vibrate or silent during lecture, and do not send text messages of any kind.

## Grading

### Graded Work
- **Homework Assignments** (40%)
  - There will be written and programming assignments in a variety of format assignments during the course. Maximum points of the assignments could be different.
  - I usually give you a week time frame to submit the homework. Check the due in the online system.

- **Take-home Exams** (30%)
  - Take-home Midterm Exam (15%), Mon 03/16/2020 – Fri 03/20/2020
  - Take-home Final Exam (15%), Mon 05/04/2020 – Fri 05/08/2020

- **Project** (20%)
  - You will also be asked to do a semester-long software project related to some topic we cover in the course. I'll give you some ideas as we approach the middle of the semester. Since we cover a lot of different things, this is a good opportunity for you to explore some particular topic in greater depth. Students enrolled in CSCI 5850 are (1) required to work on a problem in their major area, and (2) their writeup should take the form of a publication-ready research paper, with an introduction, survey of related work, experiments, results, and a bibliography. You can do an individual project or group project (up to 4 people). If you work a group project, you should spcify your contribution in the final report clearly. 
  
- **Quiz** (10%)
  - We will have two quizzes (5% each) a week ahead of midterm and final weeks. The quizzes will be true/false, multiple choice, and some short answer.

### Percentages
Letter grades will be based on each students overall percentage of awarded points according to the following formula.

Student percentage above 93% will result in a grade of A or better.  
Student percentage above 90% will result in a grade of A- or better.  
Student percentage above 87% will result in a grade of B+ or better.  
Student percentage above 83% will result in a grade of B or better.  
Student percentage above 80% will result in a grade of B- or better.  
Student percentage above 77% will result in a grade of C+ or better.  
Student percentage above 73% will result in a grade of C or better.  
Student percentage above 70% will result in a grade of C- or better.  
Student percentage above 60% will result in a grade of D or better.  
Student percentage below 60% will result in a grade of F.  

There will be no opportunity for “extra credit” to improve grades that have already been earned. Bargaining for grades will not be tolerated. 

### Extra Credit
In general, extra credit will not be assigned in this class. 

Upon occasion (and solely at the instructor's discretion), some small extra credit activities may be included, either by announcement in class or as part of an assignment. Please keep in mind that the extra credit is unlikely to significantly affect your grade; if you are concerned about your final grade, it is much better to focus your energy on the regular assignments. Extra credit is solely designed to provide an opportunity to students who wish to explore the topics further.

### Late Homework
Late homework will suffer a penalty of 10% for every day they are late. For example, homework which is submitted two days late is worth at most 80% of the total credit.

In unusual circumstances, such as extreme illness or injury (documented by a doctor's note), family emergencies, etc., please contact the instructor as early as possible to arrange accomidations.

### Regrade Requests
I am happy to regrade any assignmentss or exam problems which you think were unfair or incorrect. Please bring me the original assignment, plus a written explanation of your question or complaint, within two weeks of the time the paper in question is graded and returned to you.


## Policies and Resources


### Academic Integrity
In the context of this course, I encourage students to discuss general course material, which includes studying for exams, sharing notes if a student must miss class, and working on any practice problems which are assigned. You are also allowed to turn in homework assignments in pairs. I also encourage you to discuss problems with other students, but please be careful to write up all solutions separately and do not copy any material from another student. As a good rule of thumb, make sure to write your solutions without using any notes or papers written while talking to anyone other than your partner. Remember, you will be on your own in the exam, so it is in your own best interest to make sure that you really understand the material and can solve each problem on your own!

You are allowed to use outside sources of information in this class, including textbooks and webpages. If the complete and correct answer is on page 263 of the lecture notes, the best solution you can submit is "See page 263 of the lecture notes." Period. However, if you find a solution from any other source, such as a web page, a journal paper, a different algorithms textbook, or your mom, you must rewrite the solution in your own words, and you must properly cite your sources. Assume the grader has access to all the official course material, but nothing else. While we strongly encourge you to use any outside source at your disposal, please remember that the homework is supposed to demonstrate that you understand of the material, not just how to use Google. (In particular, if you blindly copy an incorrect solution, don't expect to get very many points for it!)

Students who violate academic integrity policies will be reported to the department, particularly in cases where relevant sources are not cited or in cases of direct copying of another student's work. First time offenses on homework will result in a minimum of a failing grade on the assignment in question, with egregious or repeated offenses resulting in failure in the course. In addition, students may be referred to the College of Arts and Sciences for further disciplinary action.

A statement of minimum standards for student academic integrity at Saint Louis University is described [here](https://www.slu.edu/arts-and-sciences/faculty-resources/syllabi-statements.php); I expect full compliance with the policies described.

### Attendance
Our course follows university level [attendance policy](https://catalog.slu.edu/academic-policies/academic-policies-procedures/attendance/).

### Title IX
Saint Louis University and its faculty are committed to supporting our students and seeking an environment that is free of bias, discrimination and harassment. If you have encountered any form of sexual misconduct (e.g. sexual assault, sexual harassment, stalking, domestic or dating violence), we encourage you to report this to the University. If you speak with a faculty member about an incident of misconduct, that faculty member must notify SLU's Title IX coordinator, Anna R. Kratky (DuBourg Hall, room 36; anna.kratky@slu.edu; 314-977-3886) and share the basic facts of your experience with her. The Title IX coordinator will then be available to assist you in understanding all of your options and in connecting you with all possible resources on and off campus.

If you wish to speak with a confidential source, you may contact the counselors at the University Counseling Center at 314-977-TALK. To view SLU’s sexual misconduct policy and for resources, please visit the [Office of the General Counsel](https://www.slu.edu/general-counsel/index.php).

Please see the [College of Arts and Sciences Syllabi statements](https://www.slu.edu/arts-and-sciences/faculty-resources/syllabi-statements.php). I am more than happy to accomodate any requested accommodations; come see me or get in touch via email if you have any questions.

### Disability Services
Students with a documented disability who wish to request academic accommodations must contact Disability Services to discuss accommodation requests and eligibility requirements. Once successfully registered, the student also must notify the course instructor that they wish to access accommodations in the course.

Please contact Disability Services, located within the Student Success Center, at Disability_services@slu.edu or 314-977-3484 to schedule an appointment. Confidentiality will be observed in all inquiries. Once approved, information about the student’s eligibility for academic accommodations will be shared with course instructors via email from Disability Services and viewed within Banner via the instructor’s course roster.

Note: Students who do not have a documented disability but who think they may have one are encouraged to contact Disability Services.

### Student Success Center
In recognition that people learn in a variety of ways and that learning is influenced by multiple factors (e.g., prior experience, study skills, learning disability), resources to support student success are available on campus. The Student Success Center assists students with academic-related services and is located in the Busch Student Center (Suite, 331). Students can visit the [Student Success Center](https://www.slu.edu/life-at-slu/student-success-center/index.php) to learn more about tutoring services, university writing services, disability services, and academic coaching.

### University Writing Services
Students are encouraged to take advantage of University Writing Services in the Student Success Center; getting feedback benefits writers at all skill levels. Trained writing consultants can help with writing projects, multimedia projects, and oral presentations. University Writing Services offers one-on-one consultations that address everything from brainstorming and developing ideas to crafting strong sentences and documenting sources. For more information, visit the Student Success Center  or call the [Student Success Center](https://www.slu.edu/life-at-slu/student-success-center/index.php) at 314-977-3484.

### Basic Needs Security
Students in personal or academic distress and/or who may be specifically experiencing challenges such as securing food or difficulty navigating campus resources, and who believe this may affect their performance in the course, are encouraged to contact the Dean of Students Office (deanofstudents@slu.edu or 314-977-9378) for support. Furthermore, please notify the instructor if you are comfortable in doing so, as this will enable them to assist you with finding the resources you may need.
