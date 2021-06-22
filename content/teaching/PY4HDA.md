+++
date = "2018-08-23T14:45:00+02:00"
external_link = ""
title = "Python for Health Data Analytics(PY4HDA)"    
subtitle = "Session: 2021"    
participants_block_position = "down"
type = "teaching"

[blackfriday]
    fractions = false

[[participants]]
    name = "Jubayer Hossain"
    is_member = true
    id = "jubayer"
    position = 1

[[participants]]
    name = "Wouter Kouw"
    is_member = true
    id = "wouter"
    position = 2

+++

<!--- 
<h2 style="color:red;">
Note: This site is currently under construction.
</h2>
--->

The "Python for Health Data Analytics" will start in July 2021.  


<img src="/img/teaching/5SSD0-banner.png" width="1200px">

### Course Info 
| Item | Description| 
|------|------------| 
|Program|Health Data Analytics| 
|Course Title| Python for Health Data Analytics| 
|Course Number| HDA101| 
|Course Level| Undergraduate/Basic|
|Course Start-End| July 1 - July 16| 

### Course summary
This course covers the fundamentals of a Bayesian (i.e., probabilistic) approach to machine learning and information processing systems. The Bayesian approach allows for a unified and consistent treatment of many model-based machine learning techniques. We focus on Linear Gaussian systems and will discuss many useful models and applications, including common regression and classification methods, Gaussian mixture models, hidden Markov models and Kalman filters. We will discuss important algorithms for parameter estimation in these models including the Expectation-Maximization (EM) algorithm and Variational Bayes (VB). The Bayesian method also provides tools for comparing the performance of different information processing systems by means of estimating the ``Bayesian evidence’’ for each model. We will discuss several methods for approximating Bayesian evidence. Next, we will discuss intelligent _agents_ that learn purposeful behavior from interactions with their environment. These agents are used for applications such as self-driving cars or interactive design of virtual and augmented realities. Indeed, in this course we relate synthetic Bayesian intelligent agents to natural intelligent agents such as the brain. You will be challenged to code Bayesian machine learning algorithms yourself and apply them to practical information processing problems.

### Course Goal and Course Learning Objectives
This course provides an introduction to Bayesian machine learning and information processing systems. The Bayesian approach affords a unified and consistent treatment of many useful information processing systems.

<h2 style="color:red;">
News and Announcements
</h2>

- As much as possible we use the [Piazza course site](https://piazza.com/class/kgp8llbdmx84s9) for new announcements. 

### Course Prerequisites
There are no prerequisites, and we do not assume any prior background in computer programming or statistics. Students should, however, have installed R and R Studio, and worked through a basic tutorial on R Studio.


## Instructors

- [Prof.dr.ir. Bert de Vries](http://bertdv.nl) (email: bert.de.vries@tue.nl) is the responsible instructor for this course and teaches all [lectures with label B](#lectures).
- [Dr. Wouter Kouw](https://biaslab.github.io/member/wouter/) (w.m.kouw@tue.nl) teaches all [practical sessions on probabilistic programming with label W](#lectures).                           
- [Ismail Senoz, MSc](https://biaslab.github.io/member/ismail/) (i.senoz@tue.nl),  and [Magnus Koudahl, MSc](https://biaslab.github.io/member/magnus/) (m.t.koudahl@tue.nl) are teaching assistants. Mr. Koudahl presents the ["What is Life?"](#bonus-lecture) bonus lecture. 


## Materials

In principle, you can download all needed materials from the links below.

### Books

Please download the following books/resources:

1. [Christopher M.
Bishop](http://research.microsoft.com/en-us/um/people/cmbishop/index.htm) (2006), [Pattern Recognition and
Machine
Learning](https://www.microsoft.com/en-us/research/people/cmbishop/prml-book/). You can also buy a [hardcopy, e.g. at bol.com](https://tinyurl.com/thj7euq).
2. [Ariel Caticha](https://www.albany.edu/physics/acaticha.shtml) (2012), [Entropic Inference and the Foundations of Physics](https://github.com/bertdv/BMLIP/blob/master/lessons/notebooks/files/Caticha-2012-Entropic-Inference-and-the-Foundations-of-Physics.pdf).
3. Bert de Vries et al. (2020), [PDF bundle of lecture notes for lessons B0 through B12 (Ed. Q3-2019/20)](https://github.com/bertdv/BMLIP/blob/master/lessons/notebooks/files/5SSD0-Mar2020-Lecture-notes.pdf?dl=0). 
    - The lecture notes may change a bit during the course, e.g., to process comments by students. A final PDF version will be posted after the last lecture.
4. Wouter Kouw (2020), [Julia and Jupyter Install Guide](https://github.com/bertdv/BMLIP/blob/master/lessons/notebooks/files/WKouw-Mar2020-JuliaJupyterInstallGuide.pdf?dl=0). 
    - Use this guide if you need help to install [Julia](https://julialang.org) and [Jupyter](https://jupyter.org/), so that you can open and run the course notebooks on your own machine.
    - You can test your installation by running the notebook called "Probabilistic-Programming-0.ipynb", which can be downloaded from [github](https://github.com/bertdv/bmlip) (under `lessons/notebooks/probprog`). [Here](https://www.youtube.com/watch?v=BWGTudg3xlI) is a video with step-by-step instructions on opening course notebooks.

### <a name="lectures">Lecture Notes and Videos</a>

The [source files for the lecture notes are accessible on github](https://github.com/bertdv/bmlip). If you want to download them, click the green `Code` button and then `Download ZIP`. The theory lectures are under `lessons/notebooks` and the programming notebooks are under `lessons/notebooks/probprog`. Note that you don't have to download them, you can view all lecture notes online through the links below:

<table border = "1">
         <tr>
            <th rowspan = "2"; style="text-align:center">Date</th>
            <th rowspan = "2"; style="text-align:center">Lessons</th>
            <th colspan = "3"; style="text-align:center">Materials</th>
         </tr>
         <tr>
            <th style="text-align:center">Video</th>
            <th style="text-align:center">Lecture Lotes</th>
            <th style="text-align:center">Readings</th>
         </tr>
         <tr>
            <td>01-July-2021</td>
            <td>M0: Course Syllabus and Python Environment Setup <br/>
            M1: Python Overview for Health Research</td>
            <td><a href="#">M0, M1</a></td>
            <td><a href="">M0</a>, <a href="#">M1</a></td>
            <td><a href="#">Reading Resources</a></td>
         </tr>
         <tr>
            <td>02-July-2021</td>
            <td>M2: Variables, Operators<br/>
            M1: Python Overview for Health Research</td>
            <td><a href="#">M0, M1</a></td>
            <td><a href="">M0</a>, <a href="#">M1</a></td>
            <td><a href="#">Chapter 1</a></td>
         </tr>


 </table>

### Q&A

Q&A for each lesson can  be accessed at the [Piazza course site](https://piazza.com/class/kgp8llbdmx84s9).

### Exercises

<!--- Prior to 2020, this course was evaluated by a written exam. In an written exam, the focus is a bit more on computational skills than in an oral exam.--->

In preparation for the exam, we recommend that you work through the following exercises to test your understanding of the materials:

  - [Exercises (without solutions)](http://nbviewer.ipython.org/github/bertdv/BMLIP/blob/master/lessons/exercises/Exercises.ipynb)
  - [Exercises (with solutions)](http://nbviewer.ipython.org/github/bertdv/BMLIP/blob/master/lessons/exercises/Exercises-with-Solutions.ipynb)

Please feel free to consult the following matrix and Gaussian cheat sheets (by Sam Roweis) when doing the exercises.
  - [Gaussian Identities](https://github.com/bertdv/BMLIP/raw/master/lessons/notebooks/files/Roweis-1999-gaussian-identities.pdf?dl=0)
  - [Matrix Identities](https://github.com/bertdv/BMLIP/raw/master/lessons/notebooks/files/Roweis-1999-matrix-identities.pdf?dl=0)



## Exam Guide

Each year there will be two exam opportunities. Check the official TUE course site for exam schedules.  In the Q2-2020 course, your performance will be assessed by a <span style="color:red;">WRITTEN EXAMINATION</span>, which (very likely) will be offered both online (with proctoring software) and offline (on campus, if the situation allows it). 

**You cannot bring notes or books to the exam. All needed formulas are supplied at the exam sheet**.

<!--- An exam session lasts about 30 minutes and will be recorded (and later deleted, following GDPR rules). At the beginning of the session, the examiner needs to check your identity, preferably by your campus card. 

The style of the examination is conversational. We like to engage in a conversation with you about what you learned in the class. In general, oral exams do not lend themselves well to proofing theorems or other deep mathematical manipulations. Instead, the focus is more on testing if you understand the conceptual ideas in this class. In principle, everything that has been presented in the lecture notes and videos is fair game as an exam question, including programming questions from the probabilistic programming sessions. 

Please review the [Oral Exam Example notebook](https://nbviewer.jupyter.org/github/bertdv/BMLIP/blob/master/lessons/exercises/Oral-Exam-Example.ipynb (Links to an external site.)) to get an idea of what kind of questions will be asked.

The first question of the exam will be an open question: "You get 5 minutes to tell me about what you learned in this class. You can fill in the 5 minutes as you like but try to impress me with your knowledge or insights. E.g., talk about probabilistic modelling, how it works, what are strong aspects or weak aspects of the approach, etc." After the first question, the rest of the exam will be focused at topics selected by the examiner. 
--->
