---
name: BMEG3105-Fall-2023
title: ""
title-heading: false
layout: default
---


## BMEG3105: Data analytics for personalized genomics and precision medicine — Fall 2023

[<a href="https://forms.gle/RjKZaLafeDtEus2p9">Pre-course survey</a>, <a href="http://piazza.com/cuhk.edu.hk/fall2022/bmeg3105">Piazza</a>, 
<a href="https://docs.google.com/spreadsheets/d/1lA_eLCQawKLG2IWNPJ3gDa9bKp9adOZcQMdb_ciLgEg/edit?usp=sharing">Scribing preference</a>,
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
Yu LI (<span style="color: #0099e6">liyu@cse.cuhk.edu.hk</span>), SHB-106. Office hour: 3pm-5pm, Friday <br>
TA: <br>
Qinze YU (<span style="color: #0099e6">qzyu22@cse.cuhk.edu.hk</span>), SHB-116. Office hour: 2pm-4pm, Monday <br>
Yixuan WANG (<span style="color: #0099e6">yxwang@cse.cuhk.edu.hk</span>), SHB-116. Office hour: 1pm-3pm, Tuesday <br>
Jiuming WANG (<span style="color: #0099e6">jmwang9@cse.cuhk.edu.hk</span>), SHB-122. Office hour: 2pm-4pm, Thursday <br>

#### Time and location
<b>Wednesday</b>: <b>9:30am-11:15am</b>, <b>MMW-703</b>. <br>
<b>Friday</b>: <b>9:30am-10:15am</b>, <b>MMW-703</b>. <br>
<b>Friday</b>: <b>10:30am-11:15am</b>, <b>MMW-703</b> (Tutorial). <br>

#### Format
Mixed. Slides will be available the day before the lecture day. Video recordings will be available after the lecture.

### <a id="logistics">Logistics</a>

#### Communications
<b>Blackboard</b> is the main software to manage the course, and grading will be through Blackboard. 
We will use <b>Piazza</b> (<a href="http://piazza.com/cuhk.edu.hk/fall2022/bmeg3105">BMEG3105</a>) for discussion. 
You can ask questions through Piazza, even anonymously. 
For a personal matter, please use the private post to the instructor and the TA. 
You are also very welcomed to send <b>emails</b> to the instructor and TAs.

#### Grading
<ul>
<li><b>Homework (20%)</b>: Three graded homework (A1, A2, A3; 5%+5%+5%) and one non-graded programming assignment (PA0; 5%, to ensure you can learn something from it).</li>
<li><b>Scribing (10%)</b>: Graded scribing. Summarize one of the lectures. Submit it within one week after the course. Each student should do at least one lecture. You can sign for at most two, for additional 1%.</li>
<li><b>In-class quiz (10%)</b>: Two in-class quizzes. The questions will be simple. Mainly for checking the participation. The exact date are in the schedule below.</li>
<li><b>Midterm exam (20%)</b>: A graded midterm exam with one bonus question (2%). </li>
<li><b>Project (20%)</b>: A graded individual project. You can give us your project and seek our help, or we will predefine some projects for you to choose from. The project has four components: a midterm report (5%), a final report (7%), presentation (3%), and the implementation (5%). </li>
<li><b>Final exam (20%)</b>: A graded final exam.</li>
</ul>

<b>Bonus (up to 6%)</b>: One bonus question in the Midterm exam. One additional scribing: 1%. <b>Pre-course survey</b> + <b>Post-lecture survey</b>: 0.5% for each, and the maximum is 3%. I do encourage you to complete all of them so that to let me know your feedback and adjust the course accordingly. Send your names to the TA. 

#### Open-book quiz and exam policy
All exams and quiz are open-book. You are allowed to take any <b>paper-based materials</b>. However, no phone or computer is allowed. Other communication tools are also not allowed. Discussion is not allowed.


#### Programming
Python (the TA will prepare a recitation class to introduce it, mainly for the non-grading homework and your project) or any other languages that you are familiar with. 
For python, we suggest you to use <a href="https://colab.research.google.com/notebooks/intro.ipynb">Colab</a>. <br>

The programming assessments include a non-graded programming assignment (10%) and the implementation in the project (5%). 
The bonus is sufficient to cover all the programming credit in the project, if you really do not want to try hand-on experiments at all. 
We do encourage you try.

#### Scribing
Please sign up the <a href="https://docs.google.com/spreadsheets/d/1lA_eLCQawKLG2IWNPJ3gDa9bKp9adOZcQMdb_ciLgEg/edit?usp=sharing">scribing preference</a>. 
We should have at least one student for each lecture. We may adjust the assignment if necessary. 
Notice that your note and scribing will be posted online, for others reference. 
You can choose to remove your name or not. Deadline for signing the scribing: **<span style="color:red;">11:59 pm on 12th Sep</span>**. 
After that, the Google sheet will be closed.

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
Deadline for each survey: **<span style="color:red;">11:59pm on the day before the next lecture</span>**. 
We do this because we could have time to answer the questions you mentioned in the survey. 
Please enter a "1" in the Google sheet: <a href="https://docs.google.com/spreadsheets/d/1D6fW_VH6zv6gjejbQ6u5PGJIWbgWpFe-sDG-TuiFnsI/edit?usp=sharing">Survey results</a>, once you have finished one survey. 
Usually, we will trust the 1s you fill in the Google sheet. 
But we will check the things in detail if the number of survey forms we received and the number of 1s on the Google sheet is not consistent.


### <a id="schedule_materials">Course schedule and materials</a>



| Lecture | Date         | Location | Topic                                           | Slides/Video | Notes | Reading        | Important dates (All due at **<span style="color:red;">11:59 pm</span>**)                      |
|---------|--------------|----------|-------------------------------------------------|--------------|-------|----------------|------------------------------------------------------------------------------------------------|
| 1       | Sep 7 (Wed)  | MMW703   | Introduction                                    | Lec 1        |       | Course outline |                                                                                                |
| 2       | Sep 9 (Fri)  | MMW703   | Data & Python                                   | Lec 2        |       |                | PA0 posted                                                                                     |
| 3       | Sep 14 (Wed) | MMW703   | Sequence and DP                                 | Lec 3        |       |                | **<span style="color:red;">PA0 due</span>**                                                    |
| 4       | Sep 16 (Fri) | MMW703   | Assembly & Mapping                              | Lec 4        |       |                | A1 posted                                                                                      |
| 5       | Sep 21 (Wed) | MMW703   | Data exploration                                | Lec 5        |       |                |                                                                                                |
| 6       | Sep 23 (Fri) | MMW703   | Distance and clustering                         | Lec 6        |       |                |                                                                                                |
| 7       | Sep 28 (Wed) | MMW703   | Classification                                  | Lec 7        |       |                | **<span style="color:red;">A1 due</span>**                                                     |
| 8       | Sep 30 (Fri) | MMW703   | Classification                                  | Lec 8        |       |                |                                                                                                |
| 9       | Oct 5 (Wed)  | MMW703   | Perf evaluation                                 | Lec 9        |       |                | A2 posted                                                                                      |
| 10      | Oct 7 (Fri)  | MMW703   | Feature selection                               | Lec 10       |       |                |                                                                                                |
| 11      | Oct 12 (Wed) | MMW703   | Dim reduction                                   | Lec 11       |       |                |                                                                                                |
| 12      | Oct 14 (Fri) | MMW703   | Overfitting                                     | Lec 12       |       |                |                                                                                                |
| 13      | Oct 19 (Wed) | MMW703   | Mid-term review                                 | Lec 13       |       |                | **<span style="color:red;">ParticipationQ,</span>** **<span style="color:red;">A2 due</span>** |
| 14      | Oct 21 (Fri) | MMW703   | Mid-term                                        |              | -     |                | **<span style="color:red;">8:30am-11:15am, Mid-term</span>**                                   |
|         |              |          | <span style="color:blue;">Module 2 start</span> |              |       |                |                                                                                                |
| 15      | Oct 26 (Wed) | MMW703   | Multi-omics overview                            | Lec 15       |       |                | PA1 posted                                                                                     |
| 16      | Oct 28 (Fri) | MMW703   | Cancer genomics overview                        | Lec 16       |       |                |                                                                                                |
| 17      | Nov 2 (Wed)  | MMW703   | Genomics data analysis                          | Lec 17       |       |                |                                                                                                |
| 18      | Nov 4 (Fri)  | MMW703   | Single cell genomics                            | Lec 18       |       |                |                                                                                                |
| 19      | Nov 9 (Wed)  | MMW703   | Data visualization                              | Lec 19       |       |                | **<span style="color:red;">Project M-report (Proposal)</span>**                                |
| 20      | Nov 11 (Fri) | MMW703   | TUT                                             | Lec 20       |       |                |                                                                                                |
|         |              |          | <span style="color:blue">Module 3 start</span>  |              |       |                |                                                                                                |
| 21      | Nov 16 (Wed) | MMW703   | Deep learning/CNN                               | Lec 21       |       |                | **<span style="color:red;">PA1 due</span>**, A3 posted                                         |
| 22      | Nov 18 (Fri) | MMW703   | EHRs & Text                                     | Lec 22       |       |                |                                                                                                |
| 23      | Nov 23 (Wed) | MMW703   | Drug & Presentation                             | Lec 23       |       |                |                                                                                                |
| 24      | Nov 25 (Fri) | MMW703   | Project pres                                    |              |       |                | **<span style="color:red;">A3 due</span>**                                                     |
| 25      | Nov 30 (Wed) | MMW703   | Course review                                   | Lec 25       |       |                | **<span style="color:red;">ParticipationQ</span>**                                             |
| 26      | Dec 2 (Fri)  | MMW703   | Project pres                                    |              |       |                | **<span style="color:red;">Project report</span>**                                             |

### <a id="assignments">Assignments</a>
<ul>
<li>Programming Assignment 0: Get yourself familiar with <a href="https://colab.research.google.com/notebooks/intro.ipynb">Colab</a>, set up the environment and run a sample code.

<li>Assignment 1: Basic concept of data analytics-1</li>

<li>Assignment 2: Basic concept of data analytics-2</li>

<li>Programming Assignment 1: Application of DA to biology</li>

<li>Assignment 3: DA in Personalized Genomics and Precision Medicine</li>

</ul>
