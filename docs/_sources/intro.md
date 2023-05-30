
# Welcome to MT3510

## What is mathematical computing and why is it important?

Mathematics and computing have a long and intertwined history, many branches of each subject could not exist without the other. The theory of algorithms requires strong mathematical knowledge. Likewise the solutions of many mathematical problems are vastly enhanced by computational techniques. Some mathematical problems can even be proven to have no simple *closed form solution* (i.e. a solution that can be written down) and so our only course of action is to compute a solution numerically.

The range of applications of mathematical computing is vast. From encrypting data online, to automatically searching and sorting data. From numerically predicting the weather to modelling the spread of infectious diseases, computing is used in almost every area of mathematics and statistics. 

## What's in the module?

This module aims to take your basic knowledge of programming combined with your expanding mathematical understanding and teach you how to transfer a mathematical problem into a computational one. On the way we will consider best practice when writing code, touch on some more advanced areas of Python and demonstrate the application of computational thinking into each of the three domains of our subject; applied mathematics, pure mathematics and statistics.

## Overview of course content

- **Review of the prerequisites from MT2000** (week 1)
  - A refresh of the common Python syntax, functions and algorithm control.

- **Introduction to computational thinking** (week 2) 
  - A guide for obtaining a computational solution to a mathematical problem.

- Demonstration of some advanced plotting features of matplotlib
- An introduction to symbolic computing through `sympy`

- **Introduction to computational complexity** (week 3)
  - How do we characterise an algorithm? 
  - What makes certain methods better than others?
  - How do we write efficient code?

- **Introduction to computational geometry**  (week 4)
  - How do we solve geometrical problems on the computer?
- How can we make our code more readable and usable?
- An introduction to statistical computing & data handling with `pandas`
  
- **Applied Mathematics: Interpolation** (weeks 5 & 6)
  - Introduction to interpolation
  - Polynomial interpolation
  - Runge's phenomenon
  - Spline interpolation & the B-spline
  - Error analysis
  
- **Pure Mathematics: Computational graph theory** (weeks 7 & 8)
  - Introduction to graph theory and `networkx`
  - Graph traversal and search
  - Recursion and complexity
  - Backtrack search
 
- **Statistics:** (weeks 9 & 10) 
  -	Advanced data wrangling and cleaning
  -	Introduction to pseudo random number generation
  -	Simulation and basics of statistical modelling in Python
  -	Statistical data visualisation
 
## Who's who
The module has three lecturers:
* Dr Dan Lucas (dl21@st-andrews.ac.uk) **module coordinator and applied mathematics lecturer.**
* Dr Finn Smith (fls3@st-andrews.ac.uk) **pure mathematics lecturer.**
* Dr Ben Swallow (bts3@st-andrews.ac.uk) **statistics lecturer.**

There will be a rotating cast of instructors helping in the laboratory sessions. 

## Course delivery

This course is delivered in a flipped format. This means that video lectures will be released each week for you to watch *before* attending class. Videos are available on the module [Panopto page](https://st-andrews.cloud.panopto.eu/Panopto/Pages/Sessions/List.aspx?folderID=1195cf32-a452-423b-88ca-aec200eb7401). There will be an interactive notebook (& static reference webpage, linked in this booklet, see below and in the menu bar) to accompany each video.

### Jupyterhub
As with the 2000-level Python workshops and projects we are using a JupyterHub server to carry out the practical side of the module. There is a link to the server on the Moodle which will automatically load the materials for the module including practical notebooks (see below). Remember this server is accessible anywhere, you do not need to be in the computer lab to access it. As noted before, it is possible to have Jupyter and Python installed locally on your own machine (e.g. via [anaconda](https://www.anaconda.com/)) but materials will need to be downloaded to your personal machine and we will be unable to assist with any issues relating to your installation. 

### Tutorial laboratory sessions
Each week you are required to attend a "tutorial" laboratory session for which you have signed up. During these sessions you will work on a weekly tutorial notebook. These weekly exercises **contain assessed questions** (weeks 2-10) which together contribute 30% of the module mark. You should attempt the notebook before attending the lab, but the lab sessions are there to assist you in completing the tasks within the exercises. The deadline for each week's graded exercises is the following Monday at 9am, e.g. the week 1 tutorial is due on Monday 23rd January. 

### Moodle quizzes
Each week a short quiz will be made available on the course Moodle page. These questions are not for credit but are a helpful checkpoint for your progress and allow the instructors to establish if any concepts are causing particular difficulty. Please attempt each quiz before attending the laboratory sessions.

### Virtual drop-in
Your timetable includes one hour per week for an online drop-in help session at 1pm on Mondays. Staff will be online to answer questions via the [module team on MS Teams](https://teams.microsoft.com/l/team/19%3aEi0LjCNkrsuZmZqwdXtnABIrdKS8YA9APckM3HhaFdw1%40thread.tacv2/conversations?groupId=3aa7e196-9697-4b27-ad46-e33c5a40cc77&tenantId=f85626cb-0da8-49d3-aa58-64ef678ef01a). If you have no questions, this hour should be used for watching lecture videos or working on practicals/projects. Please also use the Teams channels to ask questions at any time, we will use the Team as a forum for asynchronous discussion as well as the synchronous Monday drop-in.

### Attendance monitoring
As with all 3000-5000 Level taught modules in the School of Mathematics and Statistics attendance will be monitored at various points over the semester. This is to comply with UKVI regulations and to monitor student wellbeing.  For MT3510, Introduction to Mathematical computing, attendance will be taken at the laboratory sessions of weeks 6 and 8.
 
These tutorials are no more or less academically important than others and, in general, we expect you to attend all classes. If you cannot attend a compulsory class you should complete a self-certificate of absence (available on MySaint) to explain why. 
 
You must complete at least 90% of assessment in a module to have the opportunity to gain credit in the module. If you do not complete at least 90% of assessment you will be given a FINAL academic alert in the module and receive a grade of 0X. 

### Projects
There are three projects as part of the assessment in this module, one each associated with each of the divisions; Applied, Pure and Statistics. The first project will be a team project, worth 20% of your overall mark, and be associated with the Applied content (weeks 5 & 6). The deadline for the team project will be 5pm on Friday 10th March (week 7). The second and third projects are individual, worth 25% each, the Pure project deadline will be 5pm of Friday 24th March (week 9) and the Statistics project deadline will be 5pm of Friday 7th April (week 11). Detailed instructions for each project will be released later.

### Assessment submission
When you have completed a piece of work for assessment you need to download that notebook to your local machine (lab computer or your own laptop) and then upload the notebook to the relevant MMS section. Please make sure that your notebook is downloaded as a *.ipynb* file, i.e. do **not** export as pdf, html or similar. Please also make sure that your notebook is identified only with your student number so that we are able to mark anonymously. 


### Assessment recap

- **30% weekly exercise notebooks**
- **20% Applied team project, deadline week 7**
- **25% Pure individual project, deadline week 9**
- **25% Statistics individual project, deadline week 10**

[School late submission policy applies.](https://www.st-andrews.ac.uk/mathematics-statistics/students/taught-modules/late-work/)

## Recommended texts


Links to further reading will be interspersed within the lecture content, however following texts, available online via the library, are recommended for general further reading.

- [Johansson, R., *Numerical Python : scientific computing and data science applications with Numpy, SciPy and Matplotlib*](https://encore.st-andrews.ac.uk/iii/encore/record/C__Rb2712425),
     Apress, SpringerLink (2019).

- [Hetland, M. L., *Python Algorithms : mastering basic algorithms in the python language*](https://encore.st-andrews.ac.uk/iii/encore/record/C__Rb2225149),
     Apress, SpringerLink (2014).
  
- [Stepanek, H., *Thinking in Pandas: how to use the Python data analysis library the right way*](https://encore.st-andrews.ac.uk/iii/encore/record/C__Rb3109499),
     Apress, SpringerLink (2020).
      

### Further resources


- [Downey, A. B., *Think Python: How to Think Like a Computer Scientist*](https://greenteapress.com/thinkpython2/html/index.html)
- [Ham, D. A., *Object-oriented Programming in Python for Mathematicians*](https://object-oriented-python.github.io/index.html)
- [Vanderplas, J. *Python data science handbook : essential tools for working with data*](https://encore.st-andrews.ac.uk/iii/encore/record/C__Rb2511660)
- [Unpingco, J. *Python programming for data analysis*](https://encore.st-andrews.ac.uk/iii/encore/record/C__Rb3159496)
- [learnpythonwithjupyter.com/](https://learnpythonwithjupyter.com/)

## Contents

```{tableofcontents}
```
