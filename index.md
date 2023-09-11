---
name: BMEG3105-Fall-2023
title: ""
title-heading: false
layout: default
---


## BMEG3105: Data analytics for personalized genomics and precision medicine — Fall 2023

[<a href="https://forms.gle/4RaHuiuvmMsXau3f8">Pre-course survey</a>, <a href="http://piazza.com/cuhk.edu.hk/fall2023/bmeg3105">Piazza</a>, 
<a href="https://docs.google.com/spreadsheets/d/13zLvC_PHo3qkD-Fj7eMEjdt6e96Hq8f8LJg8x79KEiE/edit?usp=sharing">Scribing preference</a>,
<a href="#logistics">Logistics</a>, <a href="#schedule_materials">Course schedule and materials</a>, <a href="#assignments">Assignments</a>]

### <a>Course description</a>
With social-economic development, people are increasingly caring about health. 
Consequently, in the field of genomics and healthcare, especially personalized genomics and precision medicine, we have accumulated a tremendous amount of data, which are waiting to be analyzed. 
This course is designed to equip students with the ability to analyze such data, which would benefit both the students' personal development and society. 
In the course, we will cover high-throughput experimental methods, standard data processing pipelines, sequence alignment and mapping, 
foundational concepts of data analytics, data exploration and visualization, clustering and classification, dimension reduction, and their applications in personalized genomics and precision medicine. 
For personalized genomics, we will also cover the integration of heterogeneous sequencing and non-sequencing data, single-cell data analysis, multi-omics analysis methods, and cancer genomics.
For precision medicine, we will cover protein-RNA interactions, biological graph analysis, and a gentle introduction to biomedical imaging and electronic health records.

#### Teaching team
Lecturer:
<ul>
<li>Yu LI (<span style="color: #0099e6">liyu@cse.cuhk.edu.hk</span>), SHB-106. Office hour: 3pm-5pm, Friday</li>
</ul>
TA:
<ul>
<li>Qinze YU (<span style="color: #0099e6">qzyu22@cse.cuhk.edu.hk</span>), SHB-116. Office hour: 2pm-4pm, Monday </li>
<li>Yixuan WANG (<span style="color: #0099e6">yxwang@cse.cuhk.edu.hk</span>), SHB-116. Office hour: 1pm-3pm, Tuesday</li>
<li>Jiuming WANG (<span style="color: #0099e6">jmwang9@cse.cuhk.edu.hk</span>), SHB-122. Office hour: 2pm-4pm, Thursday</li>
</ul>

#### Time and location
Wednesday: <b>9:30am-11:15am</b>, MMW 703 <br>
Friday: <b>9:30am-10:15am</b>, MMW 703 <br>
Friday: <b>10:30am-11:15am</b>, MMW 703 (Tutorial) <br>

#### Format
In-person. Slides will be available the day before the lecture.

### <a id="logistics">Logistics</a>

#### Communications
<b>Blackboard</b> is the main software to manage the course, and grading will be through Blackboard. 
We will use <b>Piazza</b> (<a href="https://piazza.com/cuhk.edu.hk/fall2023/bmeg3105">BMEG3105</a>) for discussion. 
You can ask questions and discuss on Piazza, even anonymously. 
For personal matters, please use the private post to the instructor and the TA. 
You are also very welcomed to send emails to the teaching team.

#### Grading
<ul>
<li><b>Homework (20%)</b>: Three graded homework (A1, A2, A3; 5%, 5%, 5%) and one non-graded programming assignment (PA1; 5%, to ensure you can learn something from it).</li>
<li><b>Scribing (10%)</b>: Graded scribing. Summarize one of the lectures. Submit it within one week after the course. Each student should do at least one lecture. You can sign for at most two, for additional 1%.</li>
<li><b>In-class quiz (10%)</b>: Two in-class quizzes. The questions will be simple, mainly for checking the participation. The exact date is in the schedule below.</li>
<li><b>Midterm exam (20%)</b>: A graded midterm exam with one bonus question (extra 2%). </li>
<li><b>Project (20%)</b>: A graded individual project with a pre-defined or self-proposed topic. The project has four components: a midterm report (5%), a final report (7%), presentation (3%), and the implementation (5%). </li>
<li><b>Final exam (20%)</b>: A graded final exam.</li>
</ul>

<b>Bonus (up to 6%)</b>: 
<ul>
<li>One bonus question in the Midterm exam.</li>
<li>One additional scribing: 1%.</li>
<li>Pre-course survey and post-lecture surveys: 0.5% for each, and the maximum is 3%. I do encourage you to complete all of them so that to let me know your feedback and adjust the course accordingly. Send your names to the TAs after completion. </li>
</ul>

#### Open-book quiz and exam policy
All exams and quizzes are open-book. You are allowed to take any <b>paper-based materials</b>. However, no phone or computer is allowed. Other communication tools are also not allowed. Discussion is not allowed.

#### AI tools use policy
You can use AI tools including ChatGPT in the project to polish your report.
However, you are required to submit both your own version and the one polished using AI tools.
You are required to make it clear how you used AI tools and which part in the report.
We will grade on the one you would like us to grade, but if you do not hand in your own version, we would not consider the submission complete.

#### Programming
Python (the TA will prepare a recitation class to introduce it, mainly for the non-grading homework and your project) or any other languages that you are familiar with. 
For python, we suggest you to use <a href="https://colab.research.google.com/notebooks/intro.ipynb">Colab</a>. <br>

The programming assessments include a non-graded programming assignment (10%) and the implementation in the project (5%). 
The bonus is sufficient to cover all the programming credit in the project, if you really do not want to try hand-on experiments at all. 
We do encourage you try.

#### Scribing
Please sign up the <a href="https://docs.google.com/spreadsheets/d/13zLvC_PHo3qkD-Fj7eMEjdt6e96Hq8f8LJg8x79KEiE/edit?usp=sharing">scribing preference</a>. 
We should have at least one student for each lecture. We may adjust the assignment if necessary. 
Notice that your note and scribing will be posted online, for others reference. 
You can choose to remove your name or not. Deadline for signing the scribing: **<span style="color:red;">11:59 pm on 12th Sep</span>**. 
After that, the Google sheet will be closed. 
For students assigned to the first two lectures, you have additional one week to submit the scribing. 

#### Projects
We will have individual projects.
You can propose your project to us and seek our help, or we will predefine some projects for you to choose from. 
Some potential project topics:
<ul>
<li>From reads to gene expression matrix processing pipeline</li>
<li>Gene expression matrix processing pipeline</li>
<li>Single-cell RNA-seq processing pipeline </li>
<li>Bio-image classification</li>
<li>Cancer gene identification</li>
<li>Gene enrichment analysis</li>
</ul>
Both a midterm report (1 page) and a final report should be submitted.

#### Late days
Each student will have <b>6 late days</b> to turn in the assignments, which can be used on A1, A2, A3, PA1, and the project midterm report. 
They cannot be used on the project final report and the scribing note. 
A maximum of 2 late days can be used for each assignment. Grades will be deducted by 25% for each additional late day. 

#### Post-lecture survey 
Deadline for each survey: <span style="color: red; font-weight: bold">11:59pm on the day before the next lecture</span>. 
We do this because we could have time to answer the questions you mentioned in the survey. 
Please enter a "1" in the Google sheet: <a href="https://docs.google.com/spreadsheets/d/1plkeGORUchj93L16yo6DCzptws9nHcKRCmDpjW4yo-Y/edit?usp=sharing">Survey results</a>, once you have finished one survey. 
Usually, we will trust the 1s you fill in the Google sheet. 
But we will check the things in detail if the number of survey forms we received and the number of 1s on the Google sheet is not consistent.


### <a id="schedule_materials">Course schedule and materials</a>



| Lecture | Date         | Location | Topic                                           | Slides| Notes | Reading | Important dates (All due at <span style="color:red;">11:59 pm</span>)      |
|---------|--------------|----------|-------------------------------------------------|--------------|-------|---------|----------------------------------------------------------------------------|
| 1       | Sep 6 (Wed)  | MMW703   | Introduction                                    | <a href="https://www.dropbox.com/scl/fi/33m42g2b5msgtykrenayi/lec1-Intro.pdf?rlkey=63nlsxqhi7tlb0ie8uzh5g9hc&dl=0">Lec-1</a>              |       |  <a href="https://www.dropbox.com/scl/fi/wj0c5t685ifh066c89kls/BMEG3150_Course-Outline_1st-Term_2023-24.doc?rlkey=bty4qjfrhrtc04kzua931ov3l&dl=0">Course outline</a>       |                                                                            | 
| 2       | Sep 8 (Fri)  | MMW703   | Data & Python                                   | <a href="https://www.dropbox.com/scl/fi/twgrp7qjud4vpju8e61y6/lec2-data-and-python.pdf?rlkey=b97a6chd6lqywic57nli0es1a&dl=0">Lec-2</a>        |       | <a href="https://colab.research.google.com/drive/1BQXW4m04kkXwTGnkfV8RwRpJ20Yct279?usp=drive_link">Tut-1</a>        | PA0 posted                                                                   |
| 3       | Sep 13 (Wed) | MMW703   | Sequence and DP                                 |              |       |         | <span style="color:red;">PA0 due</span>                                    |
| 4       | Sep 15 (Fri) | MMW703   | Assembly & Mapping                              |              |       |         | A1 posted                                                                  |
| 5       | Sep 20 (Wed) | MMW703   | Data exploration                                |              |       |         |                                                                            |
| 6       | Sep 22 (Fri) | MMW703   | Distance and clustering                         |              |       |         |                                                                            |
| 7       | Sep 27 (Wed) | MMW703   | Classification                                  |              |       |         | <span style="color:red;">A1 due</span>                                     |
| 8       | Sep 29 (Fri) | MMW703   | Classification                                  |              |       |         |                                                                            |
| 9       | Oct 4 (Wed)  | MMW703   | Perf evaluation                                 |              |       |         | A2 posted                                                                  |
| 10      | Oct 6 (Fri)  | MMW703   | Feature selection                               |              |       |         |                                                                            |
| 11      | Oct 11 (Wed) | MMW703   | Dim reduction                                   |              |       |         |                                                                            |
| 12      | Oct 13 (Fri) | MMW703   | Overfitting                                     |              |       |         |                                                                            |
| 13      | Oct 18 (Wed) | MMW703   | Midterm review                                  |              |       |         | <span style="color:red;">Quiz</span>, <span style="color:red;">A2 due</span> |
| 14      | Oct 20 (Fri) | MMW703   | Midterm                                         |              |       |         | <span style="color:red;">8:30am-11:15am, Midterm exam</span>               |
|         |              |          | <span style="color:blue;">Module 2 start</span> |              |       |         |                                                                            |
| 15      | Oct 25 (Wed) | MMW703   | Multi-omics overview                            |              |       |         | PA1 posted                                                                 |
| 16      | Oct 27 (Fri) | MMW703   | Cancer genomics overview                        |              |       |         |                                                                            |
| 17      | Nov 1 (Wed)  | MMW703   | Genomics data analysis                          |              |       |         |                                                                            |
| 18      | Nov 3 (Fri)  | MMW703   | Single cell genomics                            |              |       |         |                                                                            |
| 19      | Nov 8 (Wed)  | MMW703   | Data visualization                              |              |       |         | <span style="color:red;">Project M-report (Proposal)</span>                |
| 20      | Nov 10 (Fri) | MMW703   | Tutorial                                        |              |       |         |                                                                            |
|         |              |          | <span style="color:blue">Module 3 start</span>  |              |       |         |                                                                            |
| 21      | Nov 15 (Wed) | MMW703   | Deep learning/CNN                               |              |       |         | <span style="color:red;">PA1 due</span>, A3 posted                         |
| 22      | Nov 17 (Fri) | MMW703   | EHRs & Text                                     |              |       |         |                                                                            |
| 23      | Nov 22 (Wed) | MMW703   | Drug & Presentation                             |              |       |         |                                                                            |
| 24      | Nov 24 (Fri) | MMW703   | Project Presentation                            |              |       |         | <span style="color:red;">A3 due</span>                                     |
| 25      | Nov 29 (Wed) | MMW703   | Course review                                   |              |       |         | <span style="color:red;">Quiz</span>                                       |
| 26      | Dec 1 (Fri)  | MMW703   | Project Presentation                            |              |       |         | <span style="color:red;">Project report</span>                             |

### <a id="assignments">Assignments</a>
<ul>
  
<li>Programming Assignment 0: Get yourself familiar with <a href="https://colab.research.google.com/notebooks/intro.ipynb">Colab</a>, set up the environment and run a sample code.

<li>Assignment 1: Basic concept of data analytics-1</li>

<li>Assignment 2: Basic concept of data analytics-2</li>

<li>Programming Assignment 1: Application of DA to biology</li>

<li>Assignment 3: DA in Personalized Genomics and Precision Medicine</li>

</ul>
