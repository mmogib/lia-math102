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

## Grading Policy

coming soon

## Additional Resources

* [Khan Academy](https://www.khanacademy.org/)<!--target="_blank"-->
 !?[khan Academy](https://youtu.be/QGagl0qW8MA)

## Lessons


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

### Section  5.2

1. Start watching this video.
!?[Lesson](https://youtu.be/wJyVuDICljI)<!--
style = "border: 1px solid red;
        filter: grayscale(20%);"
-->

### Section  5.3

### Section  5.4

### Section  5.5

## Chapter 6
 ...


## Chapter 7
  ...


## Chapter 8
   ...

## Chapter 11
    ...
