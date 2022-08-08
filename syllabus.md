---
layout: page
title: Syllabus
description: >-
    Course syllabus, policies, and information.
nav_order: 5
---

# Syllabus
{:.no_toc}

<!-- ## Table of contents
{: .no_toc .text-delta } -->

<details markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
1. TOC
{:toc}
</details>

---

# Course Information

## Course Name and Number

{% if site.honors %}HNRS: {% endif %} {{ site.tagline }} -- {{ site.title }}

## Term 

{{ site.term }}

## Meeting Time and Location 

{{ site.meeting_time }} in {{ site.meeting_location }}

## Instructor Information

- Instructor Name and Preferred Title: [Prof. Matthew (Matt) Ballard](staff.md)
- Preferred pronouns: He/Him/His
- Office : {{ site.office }} 
- E-mail: [ballard@math.sc.edu](mailto:ballard@math.sc.edu)

## Office Hours

{{ site.office_hours }} 

## Academic Bulletin Description 

{{ site.bulletin_desc }}

## Full Course Description 

Figure out all values of $x,y,z$ that solve the equations
 $$ 
    5x - 2y + z = 1 \\
    -x + y - 3z = 0 \\
    2x - y + z = -1 
 $$
The most direct attack would perhaps be to repeatedly substitute and simplify to reach only a single variable equation. Are there easier ways? More efficient ways? What if we had 256 equations and 128 variables? 

In this class, we study the structure of linear equations from both very concrete and mildly abstract perspectives. We will develop tools that allow us to both gain a conceptual understanding of systems of linear equations and underpin robust computational tools. 

Our pen, paper, and mental work will be supplemented with a working knowledge of [Sage](https://www.sagemath.org/). 
 
## Prerequisites 

{{ site.prereqs }}

## Learning Outcomes 

After successful completion of this course, you will be able to: 

- Determine the complete solution to $Ax = b$
- Relate linear transformations, matrices, and change of basis
- Recognize linearly dependent and independent collections of vectors
- Compute bases and dimensions of vector spaces
- Orthogonalize vectors using Gram-Schmidt
- Know and use the properties of determinants
- Compute eigenvalues and eigenvectors
- Appreciate the ubiquity of linear algebra across science

## Course Materials 

The main resources for materials are the [course website](https://544.f21.matthewrobertballard.com) and the [Microsoft Team](https://teams.microsoft.com/l/channel/19%3aJgLzdLZpFCbmrJptHxrA2E7bvjwXsxJFPmFdJmn1-CI1%40thread.tacv2/General?groupId=5ff176b0-5dbd-44cb-a436-ec0c668e897e&tenantId=4b2a4b19-d135-420e-8bb2-b1cd238998cc) for the course. 

Some supplemental (and optional) resources:
- K. Kuttler. [A first course in linear algebra](https://www.oercommons.org/courses/first-course-linear-algebra/view) (Open Access)
- J. Hefferon. [Linear algebra](https://joshua.smcvt.edu/linearalgebra/) (Open Access)
- G. Strang. [Introduction to linear algebra](http://math.mit.edu/~gs/linearalgebra/) 

All course materials comply with copyright/fair use policies. 

# Course Requirements 

## Course Format  

To wholly and successfully engage with the course, you will need to be need to [attend](#attendance-policy-and-covid-reporting) class, attempt lots of problems, and engage both with me and your fellow classmates. All course materials are will be made available online so regular Internet access is essential for successful completion of the course. 

It is expected that much of this material will be unfamiliar to you. (If not, more power to you.) The course is structured to guide every student to mastery in terms of conceptual understanding and computational fidelity by the end of the semester.

Class time will be spent working in small groups and presenting solutions to problems. It is expected you will have consumed the relevant material ahead of each course. It is not expected you will be comfortable with the material. Class time is for learning through doing and working through your 
misunderstandings. 

Each class will end with a short quiz to diagnose any problems. 

At the end of the class, a project will be due in place of a final exam.  

## Course Communication 

I will be communicating with you regarding grades and assignments. If you need to get in touch with me, the best method is via Microsoft Team chat or email. Generally, I will reply within 24 hours and will provide feedback on assignments within one week. 

You may also post questions pertaining to the course in the Questions channel in the course team. These questions will be answered within 24 hours. I encourage all students to take a stab at answering any question. 

If you are having trouble with this course or its material, you should contact me via Microsoft Team chat or email to discuss the issues. 

Announcements will be posted to this course whenever necessary. If there is any other information I think is important, I will send it to your preferred university email address. It is your responsibility to ensure that your email account works properly in order to receive email. 

If you are unsure of your preferred email, check your account at [myaccount.sc.edu](https://myaccount.sc.edu). For more information on setting your preferred university email, please see the Knowledge Base Article [How To Change Your Primary University Email Address](https://scprod.service-now.com/sp?id=kb_article_view&sysparm_article=KB0011464). 

## Technology 

To participate in learning activities and complete assignments, you will need: 

- Access to a working computer that has a current operating system with updates installed with a modern web browser installed; 

- Reliable Internet access and a USC email account; 

- If you plan to submit handwritten assignments, a scanning device such as a smartphone with the Microsoft Office Lens app.  

- The main hub for this course is the Microsoft Teams team [COTEAM-BALLARMR-MATH-544-H01-FALL-2021](https://teams.microsoft.com/l/channel/19%3aJgLzdLZpFCbmrJptHxrA2E7bvjwXsxJFPmFdJmn1-CI1%40thread.tacv2/General?groupId=5ff176b0-5dbd-44cb-a436-ec0c668e897e&tenantId=4b2a4b19-d135-420e-8bb2-b1cd238998cc) run through UofSC’s Microsoft Teams account. To access the team for the first time on your desktop/laptop, you can use the join link including in your welcome email.   

- We will be using a computer algebra system called [Sage](https://www.sagemath.org/) to aid our learning. It blows your graphing calculator out of the water and is ideally suited to STEM work. Built as a super-set of the popular programming language [Python](https://www.python.org/), Sage skills will translate into Python skills. There are three main ways to access Sage: 
    - [SageMathCell](https://sagecell.sagemath.org/) is ideal for a computation involving a few lines. 
    - [CoCalc](https://www.cocalc.com/) provides a free plan for more complicted porgrams. 
    - [A local installation](http://doc.sagemath.org/html/en/installation/binary.html) will never be required of anyone. But, it might be valuable for a power-user. 
 
## Minimal Technical Skills Needed  

Minimal technical skills are needed in this course. All work in this course must be completed and submitted online. Therefore, you must have consistent and reliable access to a computer and the Internet. The minimal technical skills you have include the ability to: 

- Organize and save electronic files; 

- Check and use the Microsoft Teams site daily; 

- Download and upload documents; 

- Locate and enter information with a browser. 

## Technical Support  

If you have problems with your computer, technology, IT-related questions, support, including Microsoft Teams, please contact the Division of Information Technology (DoIT) Service Desk at (803) 777-1800 or submit an online request through the [Self-Service Portal](https://scprod.service-now.com/sp) or visit the [Carolina Tech Zone](https://www.sc.edu/about/offices_and_divisions/university_technology_services/support/ctz.php). The Service Desk is open Monday – Friday from 8:00 AM – 6:00 PM (Eastern Daylight Time). The Thomas Cooper Library at USC has computers for you to use in case you encounter computer issues/problems. 

# Course Assignments and Grading 

## Homework	 

Homework will need to be completed in groups of 3-4 that will be randomly assigned each week. The assignments will be available in and must be returned through Microsoft Teams. All homework assignments are due by 11:59 pm (Eastern Time) on the day indicated on the course schedule. Homework will be graded for correctness. You will be allowed up to two revisions on each homework assignment. 

## Quizzes 

Each course will end with a short quiz. The goal of the quiz is to diagnose any gaps in the understanding and make sure we all stay on the same page. Quizzes are graded for correctness. You will be allowed up to two revisions on each quiz. 

## Presentations 

All students are expected to regularly present solutions to in-class work group problems. Your target should be to present one solution every two weeks. Presentations are graded simply for completion. If you attempt it, it counts. 

## Project 

A list of project topics will be released on October 1. These can be done in groups of 1-4 of your own choosing. Projects are due by December 9 at 9:00 am (EST). 

## Evaluation and Grading Scale 

All grades will be posted on Teams. You are strongly encouraged to check you scores in Teams regularly. A final letter grade will be assigned based on the weighting below. 

### Assignment Weights 

| Component     | Percent of total      |
| :---------:   | :---------:    |
| Homework      |      25%       |
| Quizzes       |      25%       |
| Presentations |      25%       |
| Project       |      25%       |

### Grading Scale 

| Final total intervals   | Letter  Grade  |
| :-------: | :-----:   |
| [90,100]   | A         | 
| [85,90)    | B+        | 
| [80,85)    | B         | 
| [75,80)    | C+        | 
| [70,75)    | C         | 
| [65,70)    | D+        | 
| [60,65)    | D         | 
| [0,60)     | F         | 

## Assignment Submission 

All written assignments are required to be submitted through Teams. Unless otherwise specified in the problem, you will be able to enter text directly through Teams or upload a scan of handwritten work. If you choose to upload a scan, then  

- the handwriting must be clear and legible – otherwise you will receive no credit 

- you will need to use the Office 365 Lens app to scan and upload you work to your university OneDrive account before attaching to the assignment. No HEIC extensions are allowed.    

## Revisions 

All homework turned in on-time is eligible for revision at full credit. All quizzes taken on-time are eligible for revision at full credit. Each assignment can undergo at most two revisions. Revisions must be resubmitted within one week of receiving a marked assignment or revision.

# Academic Success 

## Accessibility 

The [Student Disability Resource Center](http://www.sa.sc.edu/sds/) (SDRC) empowers students to manage challenges and limitations imposed by disabilities. Students with disabilities are encouraged to contact me to discuss the logistics of any accommodations needed to fulfill course requirements (within the first week of the semester). In order to receive reasonable accommodations from me, you must be registered with the Student Disability Resource Center (1705 College Street Close-Hipp, Suite 102 Columbia, SC 29208, 803-777-6142). Any student with a documented disability should contact the SDRC to make arrangements for appropriate accommodations. 

## Student Success Center 

In partnership with USC faculty, the [Student Success Center](https://www.sc.edu/success) (SSC) offers a number of programs to assist you in better understanding your course material and to aid you on your path to success. SSC programs are facilitated by professional staff, graduate students, and trained undergraduate peer leaders who have previously excelled in their courses. Resources available to you in this and other courses may include: 

Peer Tutoring: You can make a one-on-one appointment with a [Peer Tutor](https://www.sc.edu/success). Drop-in Tutoring and Online Tutoring may also be available for this course. Visit their website for a full schedule of times, locations, and courses.  

<!-- Supplemental Instruction (SI): SI Leaders are assigned to specific sections of courses and hold three weekly study sessions. Sessions focus on the most difficult content being covered in class. The SI Session schedule is posted through the SSC website each week and will also be communicated in class by the SI Leader. There is no SI for Math 300 but this might be useful for your other classes.   -->

Peer Writing: Improve your college-level writing skills by bringing writing assignments from any of your classes to a Peer Writing Tutor. Similar to Tutoring, you can visit the website to make an appointment, and to view the full schedule of available drop-in hours and locations. 

Success Consultations: In Success Consultations, SSC staff assist you in developing study skills, setting goals, and connecting to a variety of campus resources. Throughout the semester, I may communicate with the SSC via Success Connect, an online referral system, regarding your progress in the course. If contacted by the SSC, please schedule a Success Consultation. Success Connect referrals are not punitive and any information shared by me is confidential and subject to FERPA regulations. 

SSC services are offered to all USC undergraduates at no additional cost. You are invited to call the Student Success Hotline at (803) 777-1000, visit [SSC website](https://www.sc.edu/success), or stop by the SSC in the Thomas Cooper Library on the Mezzanine Level to check schedules and make appointments. 

## Writing Center 

This course has many writing assignments. The [University Writing Center](http://artsandsciences.sc.edu/write/university-writing-center) is an important resource you should use! It's open to help any USC student needing assistance with a writing project at any stage of development. The main Writing Center is in Byrnes 703. 

## University Library Resources 

[University Libraries](sc.edu/libraries) has access to books, articles, subject specific resources, citation help, and more. If you are not sure where to start, please Ask a Librarian!  Assistance is available at sc.edu/libraries/ask.   

Remember that if you use anything that is not your own writing or media (quotes from books, articles, interviews, websites, movies – everything) you must cite the source in MLA (or other appropriate and approved) format.  

## Teams and Technology 

[Teams and Technology](https://sc.edu/about/offices_and_divisions/division_of_information_technology/end_user_services/available_technology_resources/). As a student in this course, you have access to support from the Division of Information Technology (DoIT) for Teams and computer issues. The service desk can be reached at 803-777-1800. 

## Counseling Services 

The University offers [counseling and crisis services](https://sc.edu/about/offices_and_divisions/student_health_services/medical-services/counseling-and-psychiatry/index.php) as well as outreach services and self-help. 

# Course Policies and Procedures 

## Attendance Policy and COVID Reporting 

You are expected to participate actively in each course. If you anticipate an excused absence, you need to contact me in advance. You should submit a request in writing (email is acceptable) stating the dates of the anticipated absence, explaining the reason for absence, providing supporting documentation as required above, and including any request for make-up work. You should submit this request no later than the end of the second week of regularly scheduled classes in a full fall or spring semester term and within twice the length of the drop/add period for any other term. 

If regularly attending class becomes difficult for any reason, please contact me to discuss the issue.  

In accordance with [university policy](https://sc.edu/about/offices_and_divisions/faculty_senate/faculty-toolbox/documents/attendance_policy_approved_for_21_22.pdf), a grade penalty of 10% may be imposed if a student has unexcused absensces exceeding 5% of the total number of courses. For this course, that means missing TWO courses without excuse. 

All absences due to documented illness or quarantine will be excused, and no grade penalty will be assessed for missing classes for this reason. If you experience COVID-19 symptoms, please stay home, contact the COVID-19 Student Health Services (SHS) nurse line (803-576-8511), complete the COVID-19 Student Report Form and select the option allowing the Student Ombuds to contact your professors. When talking with the SHS nurse, be sure to ask for documentation of the consult as you will need this to document why you missed class. You will also use the COVID-19 Student Report Form if you have tested positive for COVID-19 or if you have been ordered to quarantine because of close contact with a person who was COVID-19 positive. In each of these situations you will be provided appropriate documentation that can be shared through the Student Report Form. 

## COVID Policies 

As of 8/17/2021, UofSC requires face coverings, including in the class. For more information on this semester's COVID policies see the [guidance](https://sc.edu/about/offices_and_divisions/provost/academicpriorities/keepteaching/guidance/index.php) from the Provost. 

**I strongly encourage getting vaccinated**. 

**I encourage physical distancing**. While not always possible, I will strive to keep everyone at least three feet apart, even when working in groups, which we will do regularly. If you feel uncomfortable with group work in my class, please come talk with me and I don’t mind letting you work independently at all.

**I have been requested to keep a seating chart**. I have been urged to keep this seating chart for contact tracing purposes and will do my best to abide by the University policy.

### Questions You May Have
**What if I get sick with COVID?** Two things have to occur: Isolation: Students who have been diagnosed with COVID-19 are released from isolation when a medical professional has determined, based on the current CDC and DHEC guidelines, that they have recovered. Currently, these guidelines include being fever-free for at least 24 hours and at least 10 days from their first symptom or positive test if they are asymptomatic. Quarantine: Unvaccinated students who are deemed a close contact with a confirmed COVID-19 case will be quarantined for 7-14 days from their last contact with the infected individual. More specifically, students who test negative on day 5, 6, or 7 can leave quarantine after 7 full days; individuals who did not test but remain asymptomatic can leave after 10 full days. Individuals who are symptomatic or have other health concerns may be advised to remain under quarantine for 14 days. 

**What is the attendance policy if I get COVID?** In brief, I must provide make-up course work including content and assignments when students have excused absences which include (but are not limited to) being in quarantine or isolation, religious holidays, medical conditions related to pregnancy, and military duty. However, recorded classes and hybrid/online options are not required and should not be expected. All excused absences must have documentation.  See syllabus for further attendance policies.

**How will the Dr. Ballard know if I am absent due to quarantine or isolation?** COVID-19 related absences must be document through the Student Ombudsman.  Students who have been diagnosed with COVID-19 or have been exposed and require quarantining should complete the COVID-19 Student Report Form and instructors should request this form in order to excuse the absence. 

**Can I inquire about classmates condition with COVID?** Sadly, not with me. These are health issues and the information is protected by state and federal law. If an individual student has questions about whether they should quarantine or believe that they have been in close contact, have them reach out to the COVID Phone Bank (803-576-8511).

**Would we ever change to go online if too many people are sick?** Only in the rare instance that 30% or more of students have documented excused absences may I take the course online. This is not to be expected and very complicated according to the current policies. 

**What if Dr. Ballard gets sick with COVID?** I have been fully vaccinated and breakthrough infection symptoms most often resemble the common cold. In the event of a breakthrough infection, I will enter the self-isolation period and the course will switch modality to synchronous online temporarily. 

In the rare circumstance I am unable to teach remotely, a substitute instructor will take over the course. 

## Academic Integrity 

You are expected to practice the highest possible standards of academic integrity. Any deviation from this expectation will result in a minimum academic penalty of your failing the assignment, and will result in additional disciplinary measures. This includes improper citation of sources, using another student's work, and any other form of academic misrepresentation. 

The first tenet of the Carolinian Creed is, "I will practice personal and academic integrity." 

Below are some websites for you to visit to learn more about University policies: 

- [Carolinian Creed](http://www.sa.sc.edu/creed) 

- [Academic Responsibility](http://www.sc.edu/policies/staf625.pdf) 

- [Office of Student Conduct and Academic Integrity](https://www.sa.sc.edu/academicintegrity/) 

- [Information Security Policy and Standards](https://sc.edu/about/offices_and_divisions/division_of_information_technology/security/policy/universitypolicy/) 

## Plagiarism 

Using the words or ideas of another as if they were one’s own is a serious form of academic dishonesty. If another person’s complete sentence, syntax, key words, or the specific or unique ideas and information are used, one must give that person credit through proper citation. You should in particular cite any resources, person, text, or otherwise, you used to assist in preparation of your work. Copying proofs or problem solutions is strictly forbidden.  

## Group Work 

Group work should be performed in safe manner. Remote work will certainly form a larger component of a career going forward. You are encouraged to take advantage of Microsoft Teams video and chat abilities to aid in collaboration.  

## Class Conduct 

Professionalism will be expected at all times, but most especially with your interactions online and in person. Because the university classroom is a place designed for the free exchange of ideas, we must show respect for one another in all circumstances. We will show respect for one another by exhibiting patience and courtesy in our exchanges. Appropriate language and restraint from verbal attacks upon those whose perspectives differ from your own is a minimum requirement. Courtesy and kindness is the norm for those who participate in the class. 

Mistakes, in particular during the running phase, are expected and natural. Mistakes are how learning happens. All students should recognize and respect the bravery of a student presenting a proof or solution. If you ever feel uncomfortable beyond the intellectual challenge of the course, please contact me.  

Teams is a way for you to share your ideas and learning with your colleagues in this class. We do this as colleagues in learning, and the online space is meant to be a safe and respectful environment for us to conduct these discussions. 

Some general netiquette rules: 

- Treat one another with respect. It will be expected that we will not attack one another personally for holding different opinions. 

- Do not use all CAPITAL LETTERS in emails or discussion board postings. This is considered "shouting" and is seen as impolite or aggressive. 

- Begin emails with a proper salutation (Examples: Dr. Name; Ms. Name; Hello Professor Name; Good afternoon Mr. Name). Starting an email without a salutation or a simple "Hey" is not appropriate. 

- When sending an email, please include a detailed subject line. Additionally, make sure you reference the course number (Ex. ENGL 287) in the message and sign the mail with your name. 

- Use proper grammar, spelling, punctuation, and capitalization. Text messaging language is not acceptable. 

- Use good taste when communicating. Profanity should be avoided. 

- Re-Read, think, and edit your message before you click "Send/Submit/Post." 

- Please remember when posting to be respectful and courteous to your colleagues, and limit your communication to topics of this course and the assignments. 

## Late Work/Make-up Policy 

All assignments due by the deadline as posted on the course schedule. Late work is not accepted and not eligible for revision.  

Please plan accordingly, and complete these assignments in advance of their deadlines to ensure any unanticipated circumstances do not result in a missed assignment. User error does not qualify you for any kind of makeup or retake opportunity.  

Completing and submitting the assignments by the due date is the sole responsibility of you. If you fail to submit the assignment or test by the due date, then your score for that assignment will be recorded as "zero." 

You will be allowed to access the assignments an unlimited number of times until the due date/time. If you are concerned about missing a deadline, post your assignment the day before the deadline. 

Be Careful: The clock on your computer may be different than the clock in Teams. If the clock is different by one second, you will be locked out of the assignment. Plan accordingly.  

## Incomplete Grades 

The grade of Incomplete will be granted only in accordance with university policy. 

## Diversity and Inclusion 

The university is committed to a campus environment that is inclusive, safe, and respectful for all persons, and one that fully embraces the Carolinian Creed: “I will discourage bigotry, while striving to learn from differences in people, ideas and opinions.” Likewise, the Student Code of Conduct stresses, “The University of South Carolina strives to maintain an educational community that fosters the development of students who are ethical, civil and responsible persons.” 

To that end, all course activities will be conducted in an atmosphere of friendly participation and interaction among colleagues, recognizing and appreciating the unique experiences, background, and point of view each student brings. You are expected at all times to apply the highest academic standards to this course and to treat others with dignity and respect. 

## Title IX and Gendered Identity  

This course affirms equality and respect for all gendered identities and expressions. Please don’t hesitate to correct me regarding your preferred gender pronoun and/or name if different from what is indicated on the official class roster. Likewise, I am committed to nurturing an environment free from discrimination and harassment. Consistent with Title IX policy, please be aware that I as a responsible employee am obligated to report information that you provide to me about a situation involving sexual harassment or assault. 

## Expectations of the Instructor 

I am expected to facilitate learning, answer questions appropriately, be fair and objective in grading, provide timely and useful feedback on assignments and treat you as I would like to be treated. 

## Copyright/Fair Use Statement 

I will cite and/or reference any materials that I use in this course that I do not create. 

Anything that appears on this website is copyright &copy; 2021 Matthew Ballard and is distributed by an <a href="https://github.com/UofSC-Fall-2021-Math-544-H01-UofSC-Fall-2021-Math-544-H01.github.io/tree/master/LICENSE.txt\">MIT license.

Course materials that do not appear on this website are copyright &copy; 2021 Matthew Ballard and all rights are reserved. In particular, you may not distribute any of these course materials in any fashion. 

# Tentative Schedule 

This is the (ambitious) plan for the semester. But it is only a plan. The successful progression of each student is the most important guide to through the material. As such, you should expect revisions as we go. 

## Week 1
- 8/19 welcome and orientation

## Week 2
- 8/24 addition and multiplication of matrices and vectors
- 8/26 solving linear systems: row reduction 

## Week 3
- 8/31 row echelon form and LU decompositions  
- 9/2 geometry and solvability of linear systems 

## Week 4
- 9/7 ranges and null spaces of matrices - implicit and parametric representations
- 9/9 linear dependence and spans of collections of vectors - dimensions and bases

## Week 5
- 9/14 row rank, column rank  
- 9/16 invertibility 

## Week 6
- 9/21 vector spaces
- 9/23 subspaces

## Week 7
- 9/28 bases again
- 9/30 linear transformations 

## Week 8
- 10/5 kernels and images

## Week 9
- 10/12 isomorphisms 
- 10/14 determinants: the idea

## Week 10
- 10/19 determinants: computations
- 10/21 the complex number system

## Week 11
- 10/26 eigenvalues and eigenvectors 1
- 10/28 eigenvalues and eigenvectors 2

## Week 12
- 11/2 symmetric matrices
- 11/4 positive definite matrices 

## Week 13
- 11/9 diagonalizability
- 11/11 diagonalizability 2 

## Week 14
- 11/16 orthogonality and projections
- 11/18 least squares approximations

## Week 15
- 11/23 gram-schmidt and QR factorization

## Week 16 
- 11/30 singular value decomposition
- 12/2 selected applications 
