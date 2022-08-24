# CSCI 432: Advanced Algorithm Topics, Fall 2022 #

This repository is for class materials for CSCI 432 in Fall 2022, taught by Prof. Fasy.

MSU Course Catalog Description: 
A rigorous examination of advanced
algorithms and data structures. Topics include average case analysis,
probabilistic algorithms, advanced graph problems and theory, distributed and
parallel programming.

From the Instructor: This course is NOT a programming class, and is not
structured like the 132 and 232 courses that precede it.  In this course, we will
do many proofs (especially using induction), and will be writing pseudo-code, not
code.

Prerequisites:
CSCI 246 (Discrete) and CSCI 232 (Data Structures and
Algorithms) are a prerequisite for this course.  
In particular, a student enrolled in CSCI 432
should be familiar with: 
sorting and searching algorithms, big-Oh notation, 
basic recurrence relations,
heaps, queues, lists, hash tables,
proof by induction and by contradiction, and discrete probability.


## Land Acknowledgement

Living in Montana, we are on the ancestral lands of American Indians, including
the 12 tribal nations that call Montana home today: A’aninin (Gros Ventre),
Amskapi/Piikani (Blackfeet), Annishinabe (Chippewa/Ojibway), Annishinabe/Métis
(Little Shell Chippewa), Apsáalooke (Crow), Ktunaxa/Ksanka (Kootenai), Lakota,
Dakota (Sioux), Nakoda (Assiniboine), Ne-i-yah-wahk (Plains Cree), Qíispé (Pend
d’Oreille), Seliš (Salish), and Tsétsêhéstâhese/So’taahe (Northern Cheyenne).
We honor and respect these tribal nations as we live, work, learn, and play in
this state.

To learn more about Montana Indians, I suggest starting with the following
pamphlet:
[Essential Understandings Regarding Montana
Indians](http://opi.mt.gov/Portals/182/Page%20Files/Indian%20Education/Indian%20Education%20101/essentialunderstandings.pdf)

## Course Outcomes and Objectives

This course introduces students to the analysis and design of computer
algorithms. In this course, students will:

* Analyze asymptotic time and space complexity of algorithms.
* Describe algorithmic design paradigms (including dynamic programming,
  greedy algorithms, divide and conquer) and explain when an algorithmic design
  situation calls for it.
* Apply methods of analysis (prove
  correctness, time/space complexity, termination) to new
  problems.
* Use and analyze major graph algorithms and data structures.

## When and Where?

When? MWF 15:10-16:00
Where? Roberts 218 

## How do I contact you?

The preferred method to ask questions relating to this class is a public post on
the group discussion board, or in my office hours.

* Office Location: 363 Barnard Hall
* Office Phone: x4804
* Zoom: see email

Office hours: 

* Prof. Fasy: MW 17:10-18:30, and by appointment.
* TA: TBD 

Note: Please email or call (x4804) in advance if you plan to join.  This will
reduce waiting time for me to wrap up a drop-in appointment that gets there
before you.

## What is in this repository?

The folders in this repository contain all materials for this class.

Subdirectories:

- hw: Homework assignments, as well as a LaTex template for your submissions. 
- lec-notes: Copies of lecture notes, slides, and board photos. 

Files:

- README.md: The course syllabus.

The course schedule is at the bottom of this Markdown file.  If you want to
learn more about Markdown, check out [this
tutorial](https://www.markdowntutorial.com/).

## Creating Your Own Repository 

The repository is set as public, so you can access all course materials easily.
I suggest creating a private repository with this one setup as an upstream git
repo, so that you can use your repository to maintain your own materials for
this class. 

To do so, follow these instructions:
    
    - Going to <https://github.com/new>
    - Enter the name `csci-432-fall2022-name`
    - Select `Private`
    - **DO NOT ADD A README.MD or .gitignore!**

Once your repository is initialized, you can pull it down to your local machine.

Next, you should add the class repository as an upstream git repo:

```bash
$ git remote add upstream https://github.com/msu/csci-432-fall2022.git
$ git pull upstream main
$ git push
```
This will synchronize your private repository with the class repository.  You
only need to run these commands once.  Then, when you want to get an update from
the public class repository you can run this command:

```
$ git pull upstream main
```

As a general workflow on your own repository, I suggest:
```
$ git pull upstream master
[[ do work here ]]
$ git add [[ list filenames edited ]]
$ git commit -m "Descriptive message here"
$ git push origin main
```

## Grading
Your grade for this class will be determined by:

- 35% Homework (individual and group)
- 30% Project 
- 35% Exams

* Homework: All assignments must be submitted by 23:59 on the due date. Late
  assignments will not be accepted.  The lowest homework grade will be dropped.
  The submission should be typeset in LaTex using the provided template, and
  submitted as a PDF both in D2L and Gradescope.
* Project: Groups will be assigned.  The final product will be a video.  More
  details to come.
* Exams: We will have three exams in this course. Each exam will be 10% of the
  grade, with the best exam counting an additional 5%.

A grade of 70\% on exams is required to earn a B- or higher in the class.

## Class Policies

### Policy on Class Attendance

Class attendance and participation is required and expected. If you consistently
miss class, then your final grade may be dropped one letter grade (e.g., from B+
to C+).

### Policy on Homework

***Do not search for answers to the problems.*** You will learn in this class by
solving the problems, not by reading the solutions. Regurgitating solutions you
found elsewhere will not help you learn the material.  If you feel that you need
additional resources, please ask.

### Policy on Collaboration

Collaboration is encouraged on all aspects of the class, except where explicitly 
forbidden. Note:

- All collaboration (who and what) must be clearly indicated in writing on
  anything turned in.  
- Homework may be solved collaboratively except as explicitly forbidden, but
  solutions must be written up **independently**.  This is best done by writing
  your solutions when not in a group setting.  Groups should be small enough
  that each member plays a significant role. (Note, if there is a
  group assignment, each group is treated as an 'individual').

### Classroom Etiquette

Except for note taking and group work requiring a computer, please keep
electronic devices off during class, as they can be distractions to other
students. Disruptions to the class will result in being asked to leave the
lecture, and one half-point will be deducted from your final course grade.

### Withdrawing

After 15 October 2022, I will only support requests to withdraw from this course
with a "W" grade if extraordinary personal circumstances exist.  If you are
considering withdrawing from this class, discussing this with me as early as
possible is advised.  Since this class involves a project, the decision to
withdraw must also be discussed with your group (after groups are formed).

### Special Needs Information

If you have a documented disability for which you are or may be requesting an
accommodation(s), please contact both me and the office of Disabled Student
Services within the first two weeks of class.

### Diversity Statement

Montana State University considers the diversity of its students, faculty, and
staff to be a strength and critical to its educational mission. MSU expects
every member of the university community to contribute to an inclusive and
respectful culture for all in its classrooms, work environments, and at campus
events.  Dimensions of diversity can include sex, race, age, national origin,
ethnicity, gender identity and expression, intellectual and physical ability,
sexual orientation, income, faith and non-faith perspectives, socio-economic
status, political ideology, education, primary language, family status, military
experience, cognitive style, and communication style. The individual
intersection of these experiences and characteristics must be valued in our
community.

If there are aspects of the design, instruction, and/or experiences within this
course that result in barriers to your inclusion or accurate assessment of
achievement, please notify the instructor as soon as possible and/or contact
Disability Services or the Office of Institutional Equity.

### Use of Materials

This syllabus, course lectures and presentations, and any course materials
provided throughout this term are protected by U.S. copyright laws. Students
enrolled in the course may use them for their own research and educational
purposes.  However, reproducing, selling or otherwise distributing these
materials without written permission of the copyright owner is expressly
prohibited, including providing materials (or solutions) to commercial
platforms such as Chegg or CourseHero.  Doing so constitutes a violation of
U.S. copyright law as well as MSU’s Code of Student Conduct.  Instructors from
other universities are free to borrow the material on this website for use in
their own classrooms.

### Special Remarks and Policies for COVID-19

Please follow the current [CDC
guidelines](https://www.cdc.gov/coronavirus/2019-ncov/prevent-getting-sick/prevention.html),
which includes wearing a mask or respirator when the "COVID-19 community level"
is "high".  If you need to miss class to quarantine or isolate due to COVID-19
(or for any other reason), please communicate with the instructor as soon as
possible in order to coordinate a plan for making up the missed classwork.  As a
reminder, attendance is required.  If the instructor is unable to make it to
class, either a substitute will be found for those lectures or the class will be
held via Zoom.

## MSU Policies

### Academic Integrity

The integrity of the academic process requires that credit be given where credit
is due. Accordingly, it is academic misconduct to present the ideas or works of
another as one's own work, or to permit another to present one's work without
customary and proper acknowledgment of authorship. Students may collaborate with
other students only as expressly permitted by the instructor. Students are
responsible for the honest completion and representation of their work, the
appropriate citation of sources and the respect and recognition of others'
academic endeavors.

Plagiarism will not be tolerated in this course. According to the Merriam-Webster
dictionary, plagiarism is "the act of using another person's words or ideas
without giving credit to that person."  Proper credit means describing all
outside resources (conversations, websites, etc.), and explaining the extent to
which the resource was used.  Penalties for plagiarism at MSU include (but are
not limited to) failing the assignment, failing the class, or having your degree
revoked.  This is serious, so do not plagiarize.  Even inadvertent or
unintentional misuse or appropriation of another's work (such as relying heavily
on source material that is not expressly acknowledged) is considered plagiarism. 

By participating in this class, you agree to abide by the Student Code of
Conduct.  This includes the following academic expectations:

- Be prompt and regular in attending classes;
- Be well-prepared for classes;
- Submit required assignments in a timely manner;
- Take exams when scheduled, unless rescheduled under 310.01;
- Act in a respectful manner toward other students and the instructor and in a
  way that does not detract from the learning experience; and
- Make and keep appointments when necessary to meet with the instructor. 

### MSU Drug and Alcohol Policies

Per the Code of Conduct for students, no student may come to class under the
influence of drugs or alcohol, as that would not be `fostering a healthy, safe
and productive campus and community.`  See [Alcohol and Drug Policies
Website](http://www.montana.edu/deanofstudents/alcoholanddrugs.html) for more
information.  In particular, note:

```
Montana State University is tobacco free campus, to include e-cigarettes
(vaping) and an environment where inappropriate use of alcohol and unlawful
possession, consumption, use or distribution of illicit drugs or alcohol is
prohibited. The minimum age to purchase tobacco products in the state of Montana
is 21.  Despite the fact that medical and recreational marijuana use is legal in
the state of Montana for individuals over the age of 21, University policy
prohibits its use and federal and state law prohibit the possession and/or use
of drug paraphernalia at an educational institution.  The university
requirements are found in the Tobacco Free Campus Policy and the Campus Alcohol
and Drug Policy.
```

## Resources

### Technical Resources

- [Git Udacity
  Course](https://www.udacity.com/course/how-to-use-git-and-github--ud775)
- [Forking in Git](https://help.github.com/articles/fork-a-repo/)
- [Markdown](http://daringfireball.net/projects/markdown/)
- [More Markdown](https://www.markdowntutorial.com/)
- [Inkscape Can Tutorial](http://tavmjong.free.fr/INKSCAPE/MANUAL/html/SoupCan.html)
- [Plagiarism Tutorial](http://www.lib.usm.edu/legacy/plag/pretest_new.php)
- [Big-O, Intuitive Explanation](https://rob-bell.net/2009/06/a-beginners-guide-to-big-o-notation/)
- [Discrete Lecture
  Notes](https://courses.cs.duke.edu/spring09/cps102/Lectures/Book.pdf)

### Course Textbook

* (Required) [Algorithms by Jeff Erickson](https://jeffe.cs.illinois.edu/teaching/algorithms/)
* (Suggested) Introduction to Algorithms, Third Edition by Cormen, Leiserson, Rivest, and
  Stein (CLRS). 

## Schedule

Each week, we assign:

- Textbook Reading:  These are readings from [Erickson's
  Algorithms](https://jeffe.cs.illinois.edu/teaching/algorithms/), please skim
  before class, and fully read after class.
- Additional Readings: additional resources that your classmates (current or
  previous) have found helpful. Skim/read as you find appropriate. If you need
  more resources, ask!

## Schedule

### Week 1 (24, 26 August)
- Topics: Intro to Analysis of Algorithms; Induction; Asymptotic Notation 
- Reading: Chapter 0 
- Additional Reading: [Induction Review](https://www.cs.montana.edu/brittany/teaching/algorithms/15_fall/docs/induction.pdf)

### Week 2 (29,31 August; 2 September)
- Topics: Recursion: Runtime and Correctness 
- Reading: Appendix II; Chapter 1

### Week 3 (7,9 September)
- Monday (5 September) is Labor day. No class.
- Topics: More Recursion: Correctness and Master Theorem 
- Reading: Appendix II; Chapter 1

### Week 4 (12,14,16 September)
- Topics: Proof of Termination; Backtracking
- Reading:  Chapter 2

### Week 5 (19,21,23 September)
- Exam on Wednesday!
- Topics: Dynamic Programming
- Reading: Chapter 3

### Week 6 (25,28,30 September)
- Topics: More Dynamic Programming
- Reading: Chapter 3

### Week 7 (3,5,7 October)
- Topics: Greedy Algorithms, Loop Invarints
- Reading: Chapter 4 
- Additional Reading: [Gas Stop
  Problem](https://medium.com/@TheGeekiestOne/greedy-algorithms-the-car-fueling-problem-a35ccc9bb011)

### Week 8 (10,12,14 October)
- Topics: Graph Algorithms 
- Reading: Chapters 5,6 

### Week 9 (17,19,21 October)
- Topics: Graph Algorithms (cont.)
- Reading: Chapters 5,6 

### Week 10 (24,26,28 October)
- Topics: More Graph Algorithms 
- Reading: Chapter 7 

### Week 11 (31 October; 2,4 November)
- Exam on Wednesday!
- Topics: MST and SSSP 
- Reading: Chapter 8 

### Week 12 (7,9 November)
- Friday (11 November) is Veteran's Day. No class.
- Topics: APSP and Flows
- Reading: Chapter 9 and 10.1 

### Week 13 (14,16,18 November)
- Topics: Flows and Cuts
- Reading: Chapter 10-11 

### Week 14 (21,23,25 November)
- Fall Break (no classes)

### Week 15 (28,30 November; 2 December)
- Topics: Randomized Algorithms 
- Reading: TODO 

### Week 16 (5,7,9 December)
- TBD 

### Week 17 (Finals Week)
- We meet Mnday, 12 December, 14:00-15:50. (TODO: someone must confirm!)
- See [Finals Week Schedule](https://www.montana.edu/registrar/Schedules.html)
  for university policies.
--- 

This syllabus was created, using wording from previous courses taught by myself,
as well as my colleagues.  Thanks all!  If you are teaching an algorithms or
related course and wish to use any of the materials, you have permission to do
so, as long as solutions to HW questions are not posted online.
