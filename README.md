<!--
author:   Dr. Mohammed Alshahrani

email:    mshahrani@kfupm.edu.sa

version:  0.0.1

logo:   https://res.cloudinary.com/mshahrani/image/upload/v1609929744/me-in-uot-2018-2.jpg

language: en

narrator: US English Male

comment:  This is MATH102 course website.
          I will publish all material related.

link:   https://cdn.jsdelivr.net/chartist.js/latest/chartist.min.css
        https://cdn.jsdelivr.net/gh/mmogib/lia-math102/custom.css      

script:   https://cdn.jsdelivr.net/chartist.js/latest/chartist.min.js

import:  https://raw.githubusercontent.com/LiaTemplates/Random/master/README.md

import:  https://raw.githubusercontent.com/liaTemplates/rextester/master/README.md

@today
<script>
const event = new Date();
const options = { weekday: 'long', year: 'numeric', month: 'long', day: 'numeric' };
const todays_date = event.toLocaleDateString('en-US', options) + " / " + event.toLocaleDateString('ar-SA', options)
todays_date
</script>

@end
translation: Deutsch  translations/German.md

translation: Français translations/French.md

-->

# MATH102: CALCULUS II
(@today)

Watch this please

[preview-lia](https://raw.githubusercontent.com/mmogib/lia-math102/master/README.md)

!?[introduction](https://youtu.be/2g0bx4OupC0)


--------------
Please make note of the following points

* **Code of Conduct** Please fill in  the [Code of Conduct](https://forms.office.com/Pages/ResponsePage.aspx?id=iLC0KX3SKUG5-YY3tZ6ks3AB3lEKGJFGqOnkl9Bm1nNURjI3TUtUSk5GS0ROVTlKSjVISDNWVkg0Ni4u)<!--
target="_blank"
--> form. If you have any objections on the terms, please change the section to another section of MATH102.
* **Class meetings** All classes will be conducted online via [ZOOM](https://kfupm.zoom.us/)<!--
target="_blank"
-->.
* **Class recordings** All classes will be recorded and published on youtube. The links of the recording will be posted in [HERE](#Lessons).
* **Office Hours** You can book an appointment through [Calendly](https://calendly.com/mshahrani/office-hour)<!--
target="_blank"
-->.
* **CAS**: I will be using a Computer-Algebra-System for this course to help us solve some _CAS_ problems. These are published and can be accessed online here (**Python**: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/mmogib/math102.git/pythonized)<!--target="_blank"-->, **Julia**: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/mmogib/math102.git/julialized)<!--target="_blank"-->.)
* **Communication** __Please do not send me emails__<!-- style="color:red;"-->. All communications will through <span style="color: purple;">slack.com</span>. You should have received an invitation email from slack.
* **Attendance and Grades** You can follow up on your attendance and grades through slack.


## Course Details


**The Course Code and Name:** Math 102, Calculus II

*The Course Credit Hours:* 4-0-4 (Three lectures and one recitation session per week.)

**Textbook:** Calculus: Early Transcendentals, 8th edition, by James Stewart, Cengage Learning,
2016. It is available online through WebAssign. Watch how to reach here

!?[Watch how to reach here](https://youtu.be/bGKTy2q5_C0)

**Course Objective:** The objective of the course is to introduce students to the topics of
definite & indefinite integrals, series, and their applications.

**Course Content:** Definite and indefinite integrals of functions of a single variable.
Fundamental Theorem of Calculus. Techniques of integration. Applications of the definite
integral to area, volume, arc length, and surface area. Improper integrals. Sequences and series:
convergence tests, integral, comparison, ratio and root tests. Alternating series. Absolute and
conditional convergence. Power series. Taylor and Maclaurin series.

**Prerequisite:** Math 101

**Learning Outcomes:**

Upon completion of this course, students should be able to

1. Use Riemann sums to estimate areas and approximate definite integrals.
2. State and apply the Fundamental Theorem of Calculus.
3. Evaluate Integrals using various techniques of integration.
4. Calculate the average value of a function, areas between curves, length of curves, volumes and surface areas of solids of revolutions.
5. Identify and evaluate improper integrals.
6. Compute limits of sequences.
7. Apply convergence tests to determine the convergence and/or the divergence of series.
8. Evaluate the sum of some selected types of series.
9. Find the interval of convergence and radius of convergence of a power series.
10. Express a function as a power series.

## Syllabus
The official Syllabus is [here](https://www.dropbox.com/s/p4nsq6hqukk8t7y/Math102-Syllabus-202%20New.pdf?dl=0)<!--target="_blank"-->
<!--data-type="none"-->
| Week      | Date          | Section   | Topics |
|-----------|---------------|---------- |--------|
|1          |Jan. 17-21     |5.1        | Areas and Distances|
|           |               |5.2        | The Definite Integral|
|2          |Jan. 24-28     |5.2        | Continued|
|           |               |5.3        |The Fundamental Theorem of Calculus|
|3          |<!--style="font-size:smaller;"-->Jan. 31- Feb. 4 |5.4 |Indefinite Integrals and the Net Change Theorem|
|           |           |5.5 |The Substitution Rule|
|4          | Feb. 7-11 |6.1| Areas between Curves|
|           |           |6.2| Volumes|
|5          | Feb. 14-18|6.2| Continued|
|           |           |6.3| Volumes by Cylindrical Shells|
|6          |Feb. 21-25|6.5| Average Value of a Function|
|           |           |7.1| Integration by Parts|
|7          |<!--style="font-size:smaller;"-->Feb. 28- Mar. 4|7.2| Trigonometric Integrals|
|           |       |7.3 |Trigonometric Substitution|
|8          |Mar. 7-11|7.4|<!--style="font-size:smaller;"--> Integration of Rational Functions by Partial Fractions+ Exercise 59|
|           |       |7.5 |Strategy for Integration|
|9          |Mar. 14-18|7.8 |Improper Integrals (Up to end of Example 8)|
|           |           |8.1| Arc Length|
|10| Mar. 21-25|8.2| Area of a Surface of Revolution|
|||11.1| Sequences|
|11| <!--style="font-size:10px;"-->Mar. 28- Apr.1 |11.2| Series|
|12| Apr. 4-8|11.3|The Integral Test and Estimates of Sums|
|||11.4| The Comparison Tests|
|13 |Apr. 11-15|11.5| Alternating Series|
|||11.6| <!--style="font-size:smaller;"-->Absolute Convergence and the Ratio and Root Tests|
|||11.7| Strategy for Testing Series|
|14 |Apr. 18-22|11.8| Power Series|
|||11.9| Representation of Functions as Power Series|
|15| Apr. 25-29|11.9| Continued|
|||11.10|Taylor and Maclaurin Series|

## Grading Policy (Revised)

| | Percentage | Points |
|Midterm (~In-Person~, online)| ~30%~ 25% | ~90~ *75*  points|
|Final (In-Person)| 40% | *120*  points|
|Homework (WebAssign)| 15% | *45*  points|
|Classwork (see below) | ~15%~ 20% | ~45~ *60*  points|

Classwork:
 *  Quizzes:                ~25~ *35* points (through WebAssign)
 *  In Class Activity:      ~20~ *25* points   


## Additional Resources

* [Khan Academy](https://www.khanacademy.org/)<!--target="_blank"-->
 !?[khan Academy](https://youtu.be/QGagl0qW8MA)

## Lessons

All notes used in the recording are available [here](https://www.dropbox.com/sh/srvjzu5tec3nckj/AAAuwXqMJoYP23J-cvboOsQDa?dl=0)<!--target="_blank"-->

- [Chapter 5](#Chapter-5)
- [Chapter 6](#Chapter-6)
- [Chapter 7](#Chapter-7)
- [Chapter 8](#Chapter-8)
- [Chapter 11](#Chapter-11)


## Chapter 5
- [Section 5.1](#Section-5.1)
- [Section 5.2](#Section-5.2)
- [Section 5.3](#Section-5.3)
- [Section 5.4](#Section-5.4)
- [Section 5.5](#Section-5.5)

### Section  5.1
- Sigma Notation
!?[Sigma Notation](https://youtu.be/fTibnyQRPT4)


Questions
========

** Write $√2+√3 +√4 +√5 +√6 + √7$ in sigma notation. (Choose all correct answers)**


    [[ ]] $∑_{k=2}^7 {√i}$
    [[X]] $∑_{i=2}^7 {√i}$
    [[X]] $∑_{k=2}^7 {k^{\frac{1}{2}}}$
    [[ ]] $∑_{k=1}^7 {(1+k)^{\frac{1}{2}}}$
    [[X]] $∑_{k=1}^6 {(1+k)^{\frac{1}{2}}}$

- Area Problem - Part 1
!?[Part 1](https://youtu.be/PMq3GMbGn6A)



- Area Problem - Part 2
!?[Part 1](https://youtu.be/hVqFXOGSGwk)



- Area and Distance Problem - Part 3
!?[Part 1](https://youtu.be/truPbsGnWgo)

- [Problem Set 1:](https://github.com/mmogib/lia-math102/blob/master/problem_sets/ProblemSet1.pdf)<!--target="_blank"-->
Solution
========
!?[Solution Part 1](https://youtu.be/lUml-Rb1Dp8)
!?[Solution Part 2](https://youtu.be/2COqHTAxS_o)



### Section  5.2
* Part 1
!?[5.2 Part 1](https://youtu.be/u_HPKd7pivw)

*Question 1:*  $${\large \int_{-4}^{2}f(x) dx =}$$

[[-5]]
[[?]] area in not the integral in general
***********************************************************************
$${\large \int_{-4}^{2}f(x) dx = -A  + B - C = -5+5-5 = -5}$$
***********************************************************************


*Question 2:* The area between the graph and the x-axis from $x=-4$ to $x=2$ is

[[15]]

* Part 2
!?[5.2 Part 2](https://youtu.be/RyJZv87j7sc)

* [Problem Set (Monday)](https://github.com/mmogib/lia-math102/blob/master/problem_sets/ps/ps2.pdf)<!--target="_blank"-->   |  [Solution](https://github.com/mmogib/lia-math102/blob/master/problem_sets/ps/ps2-solution.pdf)<!--target="_blank"-->

* [Problem Set (Wednesday)](https://github.com/mmogib/lia-math102/blob/master/problem_sets/ps/ps2-2.pdf)<!--target="_blank"--> | [Solution](https://github.com/mmogib/lia-math102/blob/master/problem_sets/ps/ps2-2-solution)<!--target="_blank"--> |
!?[Solution](https://youtu.be/hrNWmkMnNd0)

### Section  5.3
!?[Section 5.3](https://youtu.be/VUeNEleDgLM)

*Question 1*

In reference to the first problem indicated in the video, Choose the correct answer

    [( )] (A) $F(0)$
    [( )] (B) $F(1)$
    [(X)] (B) $F(2)$
    [( )] (B) $F(3)$
    [( )] (B) $F(4)$


*Question 2*
If $\displaystyle y=\int_{\cos x}^{\sin(3x)} \sqrt{t^2+3} dt$  then $\frac{dy}{dx}$ at $x=0$ is equal to

    [( )] (a) $\sqrt{3}$
    [( )] (b) $\sqrt{3}-\sqrt{1+3}$
    [( )] (c) $-\sqrt{1+3}$
    [(X)] (d) $3\sqrt{3}$
    [( )] (e) $3\sqrt{3}-\sqrt{1+3}$


* [Problem Set (Monday)](https://github.com/mmogib/lia-math102/blob/master/problem_sets/ps/ps3-1.pdf)<!--target="_blank"--> | [Solution](https://github.com/mmogib/lia-math102/blob/master/problem_sets/ps/ps3-1-solution.pdf)<!--target="_blank"-->

### Section  5.4
!?[Section 5.4](https://youtu.be/-SUsnt7EIng)

* [Problem Set (Wednesday)](https://github.com/mmogib/lia-math102/blob/master/problem_sets/ps/ps4-1.pdf)<!--target="_blank"--> | [Solution](https://github.com/mmogib/lia-math102/blob/master/problem_sets/ps/ps4-1-solution.pdf)<!--target="_blank"-->

### Section  5.5
!?[Section 5.5](https://youtu.be/y7HpCUWPUPY)

*Question 1:*  $${\large \int 4x^3 dy = x^4 + C}$$.

[( )] True
[(X)] False
[[?]] $dy$ ?
***********************************************************************
$${\large \int 4x^3 dy =4x^3 y + C}$$

Because the antiderivate is with respect to $y$ not $x$.
***********************************************************************


* [Problem Set (Monday)](https://github.com/mmogib/lia-math102/blob/master/problem_sets/ps/ps5-1.pdf)<!--target="_blank"--> | [Solution](https://github.com/mmogib/lia-math102/blob/master/problem_sets/ps/ps5-1-solution.pdf)<!--target="_blank"-->


## Chapter 6

 * [Section 6.1](#Section-6.1)
 * [Section 6.2](#Section-6.2)
 * [Section 6.3](#Section-6.3)
 * [Section 6.5](#Section-6.5)

### Section 6.1
!?[Section 6.1](https://youtu.be/wDZ0_Oakamk)

* [Problem Set (~Wednesday~) (Monday)](https://github.com/mmogib/lia-math102/blob/master/problem_sets/ps/ps6-1.pdf)<!--target="_blank"--> | [Solution](https://github.com/mmogib/lia-math102/blob/master/problem_sets/ps/ps6-1-solution.pdf)<!--target="_blank"-->

!?[Solution Video](https://youtu.be/-F3VA1CEEY8)
### Section 6.2

Please enroll in this online course. Click [HERE](https://blackboard.kfupm.edu.sa/webapps/blackboard/content/listContent.jsp?course_id=_33864_1&content_id=_499550_1)<!--target="_blank"--> to enroll.

* [Section 6.2](https://blackboard.kfupm.edu.sa/courses/1/DAD-MATH-102-VIDEO-ONLINE-production/content/_1133669_1/index.html)<!--target="_blank"--> Watch the video on `Volumes by Method of Cross-Sections` and the exercises after.


* [Problem Set (Wednesday)](https://github.com/mmogib/lia-math102/blob/master/problem_sets/ps/ps7-1.pdf)<!--target="_blank"-->  | [Solution](https://github.com/mmogib/lia-math102/blob/master/problem_sets/ps/ps7-1-solution.pdf)<!--target="_blank"-->

### Section 6.3
Please enroll in this online course. Click [HERE](https://blackboard.kfupm.edu.sa/webapps/blackboard/content/listContent.jsp?course_id=_33864_1&content_id=_499550_1)<!--target="_blank"--> to enroll.

* [Section 6.3](https://blackboard.kfupm.edu.sa/courses/1/DAD-MATH-102-VIDEO-ONLINE-production/content/_1133669_1/index.html)<!--target="_blank"--> Watch the video on `Volumes by Cylindrical Shells` and the exercises after.


* [Problem Set](https://github.com/mmogib/lia-math102/blob/master/problem_sets/ps/ps6.3.pdf)<!--target="_blank"--> | [Solution](https://github.com/mmogib/lia-math102/blob/master/problem_sets/ps/ps6.3-solution.pdf)<!--target="_blank"-->

### Section 6.5

Please enroll in this online course. Click [HERE](https://blackboard.kfupm.edu.sa/webapps/blackboard/content/listContent.jsp?course_id=_33864_1&content_id=_499550_1)<!--target="_blank"--> to enroll.

* [Section 6.5](https://blackboard.kfupm.edu.sa/courses/1/DAD-MATH-102-VIDEO-ONLINE-production/content/_1133669_1/index.html)<!--target="_blank"--> Watch the video on `Average Value of a Function` and the exercises after.


* [Problem Set](https://github.com/mmogib/lia-math102/blob/master/problem_sets/ps/ps6.5.pdf)<!--target="_blank"--> | [Solution](https://github.com/mmogib/lia-math102/blob/master/problem_sets/ps/ps6.5-solution.pdf)<!--target="_blank"-->

## Chapter 7

 * [Section 7.1](#Section-7.1)
 * [Section 7.2](#Section-7.2)
 * [Section 7.3](#Section-7.3)
 * [Section 7.4](#Section-7.4)
 * [Section 7.5](#Section-7.5)
 * [Section 7.8](#Section-7.8)


### Section 7.1

Please enroll in this online course. Click [HERE](https://blackboard.kfupm.edu.sa/webapps/blackboard/content/listContent.jsp?course_id=_33864_1&content_id=_499550_1)<!--target="_blank"--> to enroll.

* [Section 7.1](https://blackboard.kfupm.edu.sa/courses/1/DAD-MATH-102-VIDEO-ONLINE-production/content/_1133669_1/index.html)<!--target="_blank"--> Watch the video on `Integration by Parts` and the exercises after.


* [Problem Set](https://github.com/mmogib/lia-math102/blob/master/problem_sets/ps/ps7.1.pdf)<!--target="_blank"--> | [Solution](https://github.com/mmogib/lia-math102/blob/master/problem_sets/ps/ps7.1-solution.pdf)<!--target="_blank"-->



### Section 7.2

Please enroll in this online course. Click [HERE](https://blackboard.kfupm.edu.sa/webapps/blackboard/content/listContent.jsp?course_id=_33864_1&content_id=_499550_1)<!--target="_blank"--> to enroll.

* [Section 7.1](https://blackboard.kfupm.edu.sa/courses/1/DAD-MATH-102-VIDEO-ONLINE-production/content/_1133669_1/index.html)<!--target="_blank"--> Watch the video on `Trigonometric Integrals` and the exercises after.


* [Problem Set](https://github.com/mmogib/lia-math102/blob/master/problem_sets/ps/ps7.2.pdf)<!--target="_blank"--> | [Solution](https://github.com/mmogib/lia-math102/blob/master/problem_sets/ps/ps7.2-solution.pdf)<!--target="_blank"-->



### Section 7.3

Please enroll in this online course. Click [HERE](https://blackboard.kfupm.edu.sa/webapps/blackboard/content/listContent.jsp?course_id=_33864_1&content_id=_499550_1)<!--target="_blank"--> to enroll.

* [Section 7.3](https://blackboard.kfupm.edu.sa/courses/1/DAD-MATH-102-VIDEO-ONLINE-production/content/_1133669_1/index.html)<!--target="_blank"--> Watch the video on `Trigonometric Substitution` and the exercises after.


* [Problem Set](https://github.com/mmogib/lia-math102/blob/master/problem_sets/ps/ps7.3.pdf)<!--target="_blank"--> | [Solution](https://github.com/mmogib/lia-math102/blob/master/problem_sets/ps/ps7.3-solution.pdf)<!--target="_blank"-->

### Section 7.4

Please enroll in this online course. Click [HERE](https://blackboard.kfupm.edu.sa/webapps/blackboard/content/listContent.jsp?course_id=_33864_1&content_id=_499550_1)<!--target="_blank"--> to enroll.

* [Section 7.3](https://blackboard.kfupm.edu.sa/courses/1/DAD-MATH-102-VIDEO-ONLINE-production/content/_1133669_1/index.html)<!--target="_blank"--> Watch the video on `Integration of Rational Functions By Partial Fractions` and the exercises after.


* [Problem Set](https://github.com/mmogib/lia-math102/blob/master/problem_sets/ps/ps7.4.pdf)<!--target="_blank"--> | [Solution](https://github.com/mmogib/lia-math102/blob/master/problem_sets/ps/ps7.4-solution.pdf)<!--target="_blank"-->

### Section 7.5

* [Problem Set](https://github.com/mmogib/lia-math102/blob/master/problem_sets/ps/ps7.5.pdf)<!--target="_blank"--> | [Solution](https://github.com/mmogib/lia-math102/blob/master/problem_sets/ps/ps7.5-solution.pdf)<!--target="_blank"-->


### Section 7.8
Please enroll in this online course. Click [HERE](https://blackboard.kfupm.edu.sa/webapps/blackboard/content/listContent.jsp?course_id=_33864_1&content_id=_499550_1)<!--target="_blank"--> to enroll.

* [Section 7.8](https://blackboard.kfupm.edu.sa/courses/1/DAD-MATH-102-VIDEO-ONLINE-production/content/_1133669_1/index.html)<!--target="_blank"--> Watch the video on `Improper Integrals` and the exercises after.


* [Problem Set](https://github.com/mmogib/lia-math102/blob/master/problem_sets/ps/ps7.8.pdf)<!--target="_blank"--> | [Solution](https://github.com/mmogib/lia-math102/blob/master/problem_sets/ps/ps7.8-solution.pdf)<!--target="_blank"-->

## Revision: E1
* [Problem Set](https://github.com/mmogib/lia-math102/blob/master/problem_sets/ps/ps.E1.REV.pdf)<!--target="_blank"--> | [Solution](https://github.com/mmogib/lia-math102/blob/master/problem_sets/ps/ps.e1.rev-solution.pdf)<!--target="_blank"-->


## Chapter 8

 * [Section 8.1 & 8.2](#Section-8.1-and-8.2)

### Section 8.1 and 8.2
 Please enroll in this online course. Click [HERE](https://blackboard.kfupm.edu.sa/webapps/blackboard/content/listContent.jsp?course_id=_33864_1&content_id=_499550_1)<!--target="_blank"--> to enroll.

 * [Section 8.1 and 8.2](https://blackboard.kfupm.edu.sa/courses/1/DAD-MATH-102-VIDEO-ONLINE-production/content/_1133669_1/index.html)<!--target="_blank"--> Watch the video on `8.1 Arc Length and 8.2 Surface Area` and the exercises after.

 * [Problem Set](https://github.com/mmogib/lia-math102/blob/master/problem_sets/ps/ps8.1.pdf)<!--target="_blank"--> | [Solution](https://github.com/mmogib/lia-math102/blob/master/problem_sets/ps/ps8-1-solution.pdf)<!--target="_blank"-->


## Chapter 11

* [Section 11.1](#section-11.1)
* [Section 11.2](#section-11.2)
* [Section 11.3](#section-11.3)
* [Section 11.4](#section-11.4)
* [Section 11.5](#section-11.5)
* [Section 11.6](#section-11.6)
* [Section 11.7](#section-11.7)
* [Section 11.8](#section-11.8)
* [Section 11.9](#section-11.9)
* [Section 11.10](#section-11.10)


### Section 11.1
Please enroll in this online course. Click [HERE](https://blackboard.kfupm.edu.sa/webapps/blackboard/content/listContent.jsp?course_id=_33864_1&content_id=_499550_1)<!--target="_blank"--> to enroll.

* Watch the video on `Sequences` and the exercises after.


* [Problem Set](https://github.com/mmogib/lia-math102/blob/master/problem_sets/ps/ps11.1.pdf)<!--target="_blank"--> | [Solution](https://github.com/mmogib/lia-math102/blob/master/problem_sets/ps/ps11.1-solution.pdf)<!--target="_blank"-->


SOLUTION
========
!?[Solution 11.1](https://youtu.be/vX3773SkQSA)



### Section 11.2
Please enroll in this online course. Click [HERE](https://blackboard.kfupm.edu.sa/webapps/blackboard/content/listContent.jsp?course_id=_33864_1&content_id=_499550_1)<!--target="_blank"--> to enroll.

* Watch the video on `Series` and the exercises after.


* [Problem Set](https://github.com/mmogib/lia-math102/blob/master/problem_sets/ps/ps11.2.pdf)<!--target="_blank"--> | [Solution](https://github.com/mmogib/lia-math102/blob/master/problem_sets/ps/ps11.2-solution.pdf)<!--target="_blank"-->


SOLUTION
========
!?[Solution 11.2](https://youtu.be/b1Uc3jLGy6A)


### Section 11.3
Please enroll in this online course. Click [HERE](https://blackboard.kfupm.edu.sa/webapps/blackboard/content/listContent.jsp?course_id=_33864_1&content_id=_499550_1)<!--target="_blank"--> to enroll.

* Watch the video on `Integral Test` and the exercises after.


* [Problem Set](https://github.com/mmogib/lia-math102/blob/master/problem_sets/ps/ps11.3.pdf)<!--target="_blank"--> | [Solution](https://github.com/mmogib/lia-math102/blob/master/problem_sets/ps/ps11.3-solution.pdf)<!--target="_blank"-->




### Section 11.4
Please enroll in this online course. Click [HERE](https://blackboard.kfupm.edu.sa/webapps/blackboard/content/listContent.jsp?course_id=_33864_1&content_id=_499550_1)<!--target="_blank"--> to enroll.

* Watch the video on `Comparison Tests` and the exercises after.


* [Problem Set](https://github.com/mmogib/lia-math102/blob/master/problem_sets/ps/ps11.4.pdf)<!--target="_blank"--> | [Solution](https://github.com/mmogib/lia-math102/blob/master/problem_sets/ps/ps11.4-solution.pdf)<!--target="_blank"-->


### Section 11.5
Please enroll in this online course. Click [HERE](https://blackboard.kfupm.edu.sa/webapps/blackboard/content/listContent.jsp?course_id=_33864_1&content_id=_499550_1)<!--target="_blank"--> to enroll.

* Watch the video on `Alternating Series and Absolute Convergence` and the exercises after.


* [Problem Set](https://github.com/mmogib/lia-math102/blob/master/problem_sets/ps/ps11.5.pdf)<!--target="_blank"-->


### Section 11.6
Please enroll in this online course. Click [HERE](https://blackboard.kfupm.edu.sa/webapps/blackboard/content/listContent.jsp?course_id=_33864_1&content_id=_499550_1)<!--target="_blank"--> to enroll.

* Watch the video on `The Ratio and Root Tests` and the exercises after.


* [Problem Set](https://github.com/mmogib/lia-math102/blob/master/problem_sets/ps/ps11.6.pdf)<!--target="_blank"-->




### Section 11.7
Please enroll in this online course. Click [HERE](https://blackboard.kfupm.edu.sa/webapps/blackboard/content/listContent.jsp?course_id=_33864_1&content_id=_499550_1)<!--target="_blank"--> to enroll.

* Watch the video on `Strategy for Testing Series` and the exercises after.


* Problem Set: Solve as much as you can from the list of exercises.



## Class Video Recordings

### Monday 18-01-2021

* Section 35:
!?[Section 35](https://youtu.be/xeuSTlfqYZM)

* Section 36:
!?[Section 36](https://youtu.be/0fwwW-nRjhQ)


### Wednesday 20-01-2021

* Section 35:
!?[Section 35](https://youtu.be/ndtwFuBpPQY)

* Section 36:
!?[Section 36](https://youtu.be/vW40ntmjFUE)


### Monday 25-01-2021

* Section 35:
!?[Section 35](https://youtu.be/myBRoUiVIZY)

* Section 36:
!?[Section 36](https://youtu.be/nWktQH6lDYU)




### Wednesday 27-01-2021

* Section 35:
!?[Section 35](https://youtu.be/G7pN9e07hGc)


* Section 36: Same as Section 35


### Monday 01-02-2021

* Section 35:
!?[Section 35](https://youtu.be/tClYsraFbm4)

* Section 36:
!?[Section 36](https://youtu.be/0pxgn9rVsqo)


### Wednesday 03-02-2021

* Section 35:
!?[Section 35](https://youtu.be/56JMzGbsOcA)


* Section 36:
!?[Section 36](https://youtu.be/3T6LejPSzRA)
