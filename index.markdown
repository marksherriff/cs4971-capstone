---
layout: default
title: Home
nav_order: 1
description: "CS 4971: Capstone Practicum II"
permalink: /
---

# CS 4971 - AY '25-'26
## Capstone Practicum II

Capstone Practicum II serves as one of the three options for completing the CS Capstone and SEAS Senior Thesis requirement for students graduating in within the next two semesters.  For more information about the capstone, please go to [https://uvacsadvising.org/bscs.html#capstone-information](https://uvacsadvising.org/bscs.html#capstone-information).

{: .note }
__CS 4970 will NOT be a prerequisite for this class in Fall or Spring. It will be waived.__  Prerequisites are: 1) BSCS Major; 2) Graduating in the next two semesters; 3) C- or better in CS 3240.  Indicate your major, graduation semester, and semester you completed CS 3240 in your SIS enrollment permission request.

__Overview__

From Fall 2013 through Spring 2020, the Computer Science department offered a two-course sequence for completing the CS Capstone and SEAS Senior Thesis requirement - CS 4970: Capstone Practicum I and CS 4971: Capstone Practicum II.  Originally created by Prof. Aaron Bloomfield, the course was an opportunity for students to build projects for non-profits around Charlottesville over the full year.  Overall, the courses were well-liked and students enjoyed building software for real customers.

However, in Spring 2020... well... we all know what happened :-(.  After that, not only was it impossible to find any non-profits to work with, the current instructor schedule for Fall 2020 (Prof. Bloomfield had handed the course off to someone else a few years before) left suddenly that summer for another position.  So the department had to figure out something in roughly a month ahead of the Fall 2020 semester that would work during... well... "you know what."  

This is how CS 4991: Capstone Technical Report came to be.  We needed both three credits for students (hence, taking a 6th CS elective) and a way to track a technical report.  While this system has been working reasonably well and we have a wonderful instructor teaching it (Prof. Vrugtman), it's gotten a bit too big.

__Rebooting the Practicum__

So, for AY 2025-2026, we are rebooting CS 4971 and trying the independent capstone project system again, with a few changes:

- The course will run over one semester, not two as it was before with CS 4970 and CS 4971.
- The course will not be strictly limited to service learning / building apps for non-profits.  This can be an option, but is not required.
- The projects will be up to the student teams.  The main guiding principle is that the team shows that what they are building "fulfills a need."
- Example projects from Fall 2026: augmented reality tour of the Lawn, AI-guided web browser, ride sharing app for students, minigames to teach people about basic cybersecurity, guided tours of Grounds for incoming first years.
- The platform is up to you.  Web, mobile, game... whatever makes sense for your project.  The technology is up to you too!  (The danger in this is NO support will be offered for many platforms / technologies...)
- Teams will be three to four students.  Students are highly encouraged to enroll for the class as a team as you will be able to choose your teammates.  Solo students can enroll, but you will be placed on a team with other solo students.
- Project management and deliverables will closely mirror what is done in CS 3240, including requirements elicitation, a requirements document, a design document, sprint reports, etc.  Basically, picture the CS 3240 project, but with most of the guardrails taken off.
- Student teams will jointly co-author the SEAS Technical Report, due at the end of the semester.  Papers will follow standard ACM conference formatting and guidelines.

__How does this course work with STS 4500/4600?__

There are two major papers you will write as a team in CS 4971: the Project Proposal & Plan and the Technical Report.  

The Project Proposal document will contain a lot of the same information that is in the STS Prospectus paper that is due at the end of STS 4500.  If you take CS 4971 at the same time as STS 4500, then you can submit large portions of the Project Proposal document as a part of your Prospectus.  If you take CS 4971 after you have completed STS 4500, you can reuse much of the information from your Prospectus for your Project Proposal (if you decide to build that project).  In both scenarios, the Project Proposal for CS 4971 and the Prospectus for STS 4500 can be related or completely different from each other.  Further, you can build a different project in CS 4971 than what you propose in STS 4500/4600.  

The Technical Report you write as a team at the end of CS 4971 can be submitted directly as your Technical Report for STS 4600 as a part of your Senior Thesis Portfolio.

__Logistics__

- Will be offered both F25 and S26 with roughly 140 seats each semester.
- Will ONLY use CS 4971 as the course number (as this is programmed in SIS to satisfy the capstone requirement).
- Prereqs are 0) must be a BSCS major; 1) will graduate within the next two semesters; 2) C- or better in CS 3240.  CS 4970 will be waived (hence the permission of instructor required to enroll).
- _Most weeks_ you will only meet once.  Many weeks we will alternate which teams come to which day.
- Lecture will be 1) project status updates (with presentations to the class) or 2) industry guest speakers.
- Attendance will be required and taken.

## Staff Information

{% for professor in site.data.professors %}

__Instructor:__ {{ professor.name }}   
Office: {{ professor.office }}      
Email: [{{ professor.email }}]({{ professor.email }})   
Website: [{{ professor.website }}]({{ professor.website }})     

{% endfor %}