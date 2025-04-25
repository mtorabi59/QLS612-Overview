---
layout: default
title: 2023 Lectures and Class Material
description: Links to the pre-recorded lectures and material (2023)
---

# Lectures and Class Material

[Link to the GitHub Repository containing the lecture materials](https://github.com/neurodatascience/QLS-course-materials)

[QLS612 Slack workspace](https://qls612-bhs.slack.com)

---

## 1. Reproducibility in Life Sciences

**Instructor:** [JB Poline](mailto:jean-baptiste.poline@mcgill.ca)

**Outline**

With this lecture, you will get a general introduction to reproducible - or
irreproducible - life sciences. Specifically, you will

- learn what is meant by reproducibility of research results in the life
  sciences
- understand the main causes for irreproducible results
- learn the possible collective and individual actions for curbing
  irreproducibility

**Material:**
[GitHub Link](https://github.com/neurodatascience/course-materials-2023/tree/main/01-Intro_to_Reproducibility)

**Pre-recorded lecture video:**
[YouTube Link](https://www.youtube.com/watch?v=US80s7W4s6o)

**Slides:**
[Slides](https://github.com/neurodatascience/course-materials-2023/tree/main/01-Intro_to_Reproducibility/lecture-content/01-Intro_to_Reproducibility.pdf)

**Lecture Resources**

- Canonical paper:
  [Ten common statistical mistakes to watch out for when writing or reviewing a manuscript](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6785265/)

**Questions you will be able to answer after taking this module:**

- Is the term “replicability” generally applied to obtaining the same results
  with another (new) dataset ?
- Is the root cause of irreproducibility the publication incentive ?
- What is a similar result with the same methodology or pipeline but different
  data ?

---

## 2. Introduction to the Terminal and Bash

**Instructors:** Brent McPherson, Alyssa Dai

**Outline**

To follow most of the other modules, you will have to have some basic
understanding of the command line. In this module we'll take a look at the the
BourneAgainSHell (BASH), the default command line in most Linux systems. You
will learn how to:

- move around on your computer with the command line, create and open
  directories and files
- find things with the command line (files and programs, PATH variables)
- run useful command line programs and find help (`find`, `grep`, `ls`, and
  `man` / documentation)

**Materials**:

- [Github Link](https://github.com/neurodatascience/course-materials-2023/tree/main/02-Terminal_and_Bash)

**Pre-recorded lecture video (by Sebastian Urchs):**
[YouTube Link](https://youtu.be/Sd10Wo5LQls)

**Slides:**
[Slides](https://github.com/neurodatascience/course-materials-2023/tree/main/02-Terminal_and_Bash/introduction-to-shell.pdf)

**Questions you will be able to answer after taking this module:**

- What is a command line shell?
- How would you copy thousands of files with file names starting with
  `"my_good_file..."` to a different directory on your computer?
- Among thousands of files and directories you know there is one where you wrote
  down `"location of my thesis backup"`. How do you find this file?
- What is an environment variable, and how can you change it?

---

## 3. Introduction to Python

**Instructor:** Michelle Wang, Jacob Sanz-Robinson

**Outline**

- This lecture is designed to get students up and running with Python. It is
  expected that Python 3 (preferably 3.7 or later) is installed, and that the
  students have some basic previous experience in a scripting language.
- It will guide students through the fundamental syntax, concepts, and data
  structures required to code in Python 3.
- Topics include: Running your code, commenting, variables, arithmetic, logic,
  strings, lists, tuples, dictionaries, functions, libraries, if statements,
  loops, exceptions, and classes.

**Material:**
[GitHub Link](https://github.com/neurodatascience/course-materials-2023/tree/main/03-Intro_to_Python)

**Pre-recorded lecture video (by Jacob Sanz-Robinson):**
[YouTube Link](https://www.youtube.com/watch?v=ml6VkmtLXpA)

**Lecture Resources**

- [Think Python 2e textbook](https://greenteapress.com/wp/think-python-2e/)

**Questions you will be able to answer after taking this module:**

(1) How does the use of a `break` statement alter the flow of a loop in Python?

(2) What happens if you attempt to append new elements to a Tuple?

(3) Without running the code on your machine, what is the printed output when
the following code is run?

```python
my_dictionary = {"a" : 1, "b" : {"c" : {"d" : [4,5,6,4]}}, "c" : [1,2,3]}
x = my_dictionary["b"]["c"]["d"].append(my_dictionary["c"][-3])
print(my_dictionary.values())
```

- a) [1, {'c': {'d': [4, 5, 6, 4}}, [1, 2, 3]]
- b) [1, {'c': {'d': [4, 5, 6, 4, 1]}}, [1, 2, 3]]
- c) [1, [4,5,6,4,1], [1,2,3]]
- d) [1, [4,5,6,4], [1,2,3]]

(4) Without running the code on your machine, which string is returned by
my_function when called with the specified parameters?

```python
def my_function(x, y, z):
    result = ""
    if len(z) <= 6 and len(z) > 2:
        result = z[-2] + y
    else:
        result = x + y
    return x + x + result

my_function("111", "abc", "0100")
```

- a) ‘1111110abc’
- b) ‘0abc111111’
- c) ‘111111bca0’
- d) ‘1111111110’

---

## 4. Scientific Python: NumPy and Scipy

**Instructor:** Jérôme Dockès

**Outline**

This lecture will introduce NumPy and its ndarray data structure, which are at
the core of most scientific Python packages. At the end of the lecture,
participants will be able to:

- Understand why NumPy enables efficient computation and what are NumPy arrays.
- Manipulate arrays of numbers with NumPy

**Materials:**
[GitHub Link](https://github.com/neurodatascience/course-materials-2023/tree/main/04-NumPy_SciPy)

**Lecture Resources**

- [NumPy User Guide](https://numpy.org/doc/stable/user/basics.html)

## 5. Introduction to Git and GitHub

**Instructor:** Kendra Oudyk

**Outline**

Git and GitHub are key tools for doing version control in both academia and
industry. These tools can help students do more efficient, open, and
reproducible research. Further, knowing these tools can help prepare students
for careers in academia and industry. In this lecture, students will learn

- What is version control and why has it become so important in science and
  industry;
- How to track and share their own work using Git and GitHub; and
- How to collaborate and contribute to open projects using Git and GitHub.

**Materials**:
[GitHub Link](https://github.com/neurodatascience/course-materials-2023/tree/main/05-Git_GitHub)

**Pre-recorded lecture video:** [YouTube Link](https://youtu.be/b0ETTTKfu2Y)

**Slides:**
[Slides](https://github.com/neurodatascience/course-materials-2023/tree/main/05-Git_GitHub/Git-GitHub__lecture-slides.pdf)

**Lecture Resources**

- [Pro Git book by S. Chacon and B. Straub](https://git-scm.com/book/en/v2)
- [The Carpentries course "Version Control with Git"](https://swcarpentry.github.io/git-novice/)

**Questions you will be able to answer after taking this module:**

1.  In a **\_\_\_\_** version control system, individuals have the entire
    repository and its history in their local repository.

- a) Centralized
- b) Distributed

2. What is the basic workflow for tracking a change and sharing it on github?

- a) `git commit`, `git add`, `git push`
- b) `git pull`, `git add`, `git push`
- c) `git add`, `git commit`, `git push`

3. How do you start a parallel line of development, in order to do nonlinear
   version control?

- a) make a tag
- b) start a new branch
- c) create a remote repository

4. How do you make a copy of another GitHub repo on your GitHub account?

- a) `git clone <repo address>`
- b) go to the repo's GitHub page and click "fork"
- c) go to the repo's GitHub page and open an issue to ask for a copy
- d) go to the repo's GitHub page and do a pull request

---

## 6. Data Wrangling with Pandas

**Instructor:** Jacob Sanz-Robinson

This module is designed to introduce students to the Pandas Python library for
manipulating data in tables and time series (not to be confused with the
[bear of the same name](https://mcdn.wallpapersafari.com/medium/8/55/Wv7BhD.jpg)).
It aims to build a basic understanding of what happens underneath the hood in
Pandas, and arm you with the essential practical knowledge to fearlessly tackle
the next CSV file you encounter in the wild.

**Outline**

1. Introduction

- a) What is Pandas?
- b) (Very) Brief History
- c) Why should I care about Pandas?
- d) Features & Docs

2. Pandas Objects

- a) The Series Object
- b) The DataFrame Object
- c) The Index Object

3. Pandas Wrangler Essentials

- a) Data I/O
- b) Selection and Indexer
- c) Filtering
- d) Combining DataFrames
- e) Inbuilt Aggregations

**Materials**:
[GitHub Link](https://github.com/neurodatascience/course-materials-2023/tree/main/06-Data_Wrangling_with_Pandas)

**Pre-recorded lecture video:** [YouTube link](https://youtu.be/S8bYQ7YmrOQ)

**Lecture resources**

- [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/index.html)
- [Neurohackademy lecture on Pandas](https://neurohackademy.org/course/complex-data-structures/)

**Questions you will be able to answer after taking this module:**

1. Which of the following is an immutable Pandas Object?

- a) Index
- b) DataFrame
- c) Series
- d) Array

2. What function would you use to combine two Pandas DataFrames if you wanted to
   align their rows based on common column values?

- a) Append
- b) Concat
- c) Merge
- d) Map

---

## 7. Classical statistics pitfalls and remedies

**Instructor:** [JB Poline](mailto:jean-baptiste.poline@mcgill.ca)

**Outline**

Most of published results still rely on some statistical inference. With this
lecture, you will

- get a reminder of the classical statistical framework and learn about the
  issues brought by the use of statistical inference
- learn (or be reminded of) the notion of effect size, power, positive
  predictive values and the consequences of low powered studies
- understand the file drawer effect, p-hacking, and know about some solutions.

**Materials:**
[GitHub Link](https://github.com/neurodatascience/course-materials-2023/tree/main/07-Statistics)

**Pre-recorded lecture video:** [YouTube Link](https://youtu.be/lRLtWjkBOzQ)

**Slides:**
[Slides](https://github.com/neurodatascience/course-materials-2023/tree/main/07-Statistics/10-classical-statistics-issues.pdf)

**Lecture Resources**

- [Think Stats](https://greenteapress.com/thinkstats2/thinkstats2.pdf)

---

## 8. Introduction to Machine Learning part 1: supervised learning

**Instructor:** Nikhil Bhagwat

**Outline**

- Define machine-learning nomenclature
- Describe basics of the “learning” process
- Explain model design choices and performance trade-offs
- Introduce model selection and validation frameworks
- Explain model performance metrics

**Materials:**
[GitHub Link](https://github.com/neurodatascience/course-materials-2023/tree/main/08-Machine_Learning_1)

**Pre-recorded lecture video:**
[YouTube Link](https://www.youtube.com/watch?v=vsp7c-f3cvg)

**Slides:**
[Slides](https://docs.google.com/presentation/d/1rxR237_F95cfQsA7ZPicQa2w-r-LVOdGwm1xpgosE8o/edit?usp=sharing)

**Lecture Resources**

- [Linear Algebra Review and Reference](https://www.cs.mcgill.ca/~dprecup/courses/ML/Materials/linalg-review.pdf)
- [Review of Probability Theory](https://www.cs.mcgill.ca/~dprecup/courses/ML/Materials/prob-review.pdf)

**_IMPORTANT!_** To fully understand the material taught in this module, you
should make sure that you are already familiar with the following concepts
(please take some time to review them if needed):

- Basics of linear algebra (check out
  [these videos](https://youtu.be/fNk_zzaMoSs) if you need a refresher)
  - Do you know how to use vectors?
  - Do you know how to multiply two matrices?
- Basics of linear regression
  - Do you know what a mean-square error is?
  - How to fit linear regression or GLMs?

**Questions you will be able to answer after taking this module:**

- When is ML a useful approach?
- Supervised learning
  - Model training - what is under/over-fitting?
  - Model selection - what is (nested) cross-validation?
  - Model evaluation - what are type-1 and type-2 errors?
- What NOT to do when using ML models in your research

**Things you will NOT learn in this module (if you are an advanced ML student)**

- In-depth review of unsupervised learning approaches (e.g. clustering)
- How train deep-learning models
- How to use and/or defeat chatGPT

---

## 9. Introduction to Machine Learning part 2: Model selection & validation; dimensionality reduction

**Instructor:** Jérôme Dockès

**Outline**

In this module, you will:

- Learn how to properly select a machine-learning model, set hyperparameters,
  and evaluate prediction performance.
- Understand the challenges of learning from high-dimensional data and learn
  about tools to mitigate the issue.

**Materials:**
[GitHub Link](https://github.com/neurodatascience/course-materials-2023/tree/main/09-Machine_Learning_2)

**Pre-recorded lecture video:**
[YouTube Link](https://www.youtube.com/watch?v=t8D9qwTqEbc)

**Slides:**
[Link](https://github.com/neurodatascience/course-materials-2023/tree/main/09-Machine_Learning_2/lecture-content/09-Machine_Learning_2.pdf)

**Lecture Resources**

- [Scikit-learn guide on feature selection](https://scikit-learn.org/stable/modules/feature_selection.html)
- [Scikit-learn guide on cross-validation](https://scikit-learn.org/stable/modules/cross_validation.html)
- [Scikit-learn guide on model evaluation](https://scikit-learn.org/stable/modules/model_evaluation.html)

**Questions you will be able to answer after taking this module:**

- I am predicting continuous cognitive scores of 1,000 participants using 20,000
  brain imaging features. I use least-squares regression. What is regularization
  and why do I need it?
- I decide to use ridge regression (l2 regularization). How can I set the
  regularization hyperparameter?
- I also add a dimensionality reduction step to my model: PCA. I do 5-fold
  cross-validation, and I perform a full grid-search, using 3 folds for the
  inner validation loop. I use a grid of 3 options for the number of PCA
  components and 6 options for the ridge hyperparameter. How many times (at
  least) will I need to fit a PCA?

## 10. Introduction to Data Visualization in Python

**Instructor:** Kendra Oudyk

**Outline**

- Data visualization is an essential skill for scientists.
- At the grad student level, you're probably already familiar with basic plots
  (e.g., bar plot vs pie chart), as well as types of data (e.g, ordered vs
  categorical).
- With that in mind, I hope to take you a bit deeper into the technicalities of
  planning and executing and effictive Figure.

**Materials:**
[GitHub Link](https://github.com/neurodatascience/course-materials-2023/tree/main/10-Intro_to_Data_Visualization)

**Pre-recorded lecture video, Part 1 Decoding:**
[YouTube link](https://youtu.be/dqf5gmY7vE0)\
**Pre-recorded lecture video, Part 2 Encoding:** [YouTube link](https://youtu.be/DrOICNoOfEA)

**Slides for Part 1 Decoding:**
[Slides](https://github.com/neurodatascience/course-materials-2023/tree/main/10-Intro_to_Data_Visualization/lecture_slides__data_vis_pt1_decoding.pdf)\
**Slides for Part 2 Encoding:** [Slides](https://github.com/neurodatascience/course-materials-2023/tree/main/10-Intro_to_Data_Visualization/lecture_slides__data_vis_pt2_encoding.pdf)

---

## 11. Virtualization of computing environments

**Instructor:** Sebastian Urchs

**Outline**

- Learn why containerization and virtualization are important for research
  projects.
- Have an overview of different solutions to create isolated environments.
- Get some basic hands on experience with and Docker.

**Materials:**
[GitHub Link](https://github.com/neurodatascience/course-materials-2023/tree/main/11-Containers)

**Pre-recorded lecture video:**
[YouTube Link](https://www.youtube.com/watch?v=KolUIDOynls)

**Slides:**
[Slides](https://github.com/neurodatascience/course-materials-2023/tree/main/11-Containers/11_Containerization_Slides.pdf)

**Questions you will be able to answer after taking this module:**

- When working with the file system inside a Docker container, which statements
  are true?
  - I cannot see files on the host system from inside the container
  - files written into the container file system are lost with the container
  - I can mount paths on the host system into the container to expose their
    contents to it
- What is an advantage of Docker over a Virtual Machine?
  - a Docker container can run any operating system, independently of the host
    operating system
  - Docker is a good choice for shared systems because of its high level of
    security
  - Docker containers are easier to specify, build, and manage and have better
    sharing infrastructure
- What is the difference between a Docker container and a Docker image?
  - A Docker container is a registry service to store and share Docker images
  - A Docker image is a read-only snapshot and a Docker container is a running
    instance of it
  - A Docker container is a read-only snapshot that can be easily shared (e.g.
    on Dockerhub) and from it, many live Docker images can be spawned
- What is an advantage conda has over pip for Python environments?
  - conda is usually prepackaged with Python, so you don't have to install
    anything
  - conda has more Python packages than pip because of the Anaconda distribution
  - conda can resolve non-Python dependencies and can also create virtual
    environments

---

## 12. High Performance Computing (HPC)

**Instructor:** Brent McPherson

**Outline**

- Learn the key facts about High Performance Computing (HPC) and Cloud computing
- Understand the advantages and the constraints of HPC
- Learn the key concepts and practical bash commands to get started on the
  Compute Canada HPC

**Materials:**
[GitHub Link](https://github.com/neurodatascience/course-materials-2023/tree/main/12-High_Performance_Computing)

**Pre-recorded lecture video (by Darcy Quesnel):**
[YouTube Link](https://youtu.be/5iTgIt_ZSyk)

**Slides:**
[Slides](https://github.com/neurodatascience/course-materials-2023/tree/main/12-High_Performance_Computing/Lecture-12-High-Performance-Computing.pdf)

**Lecture Resources**

- [Compute Canada wiki](https://docs.alliancecan.ca/wiki/Getting_started)

**Questions you will be able to answer after taking this module:**

1.  Choose the area that Advanced Research Computing traditionally does **not**
    include

- a) HPC/Clusters
- b) Research Data Management
- c) Cloud Computing
- d) Video Games

2. Choose all components that are part of an HPC Compute Node

- a) Processor/Core
- b) Display/Monitor
- c) Memory
- d) Mouse
- e) Local Disk

3. Choose all ways to access an HPC Cluster

- a) Secure shell to a Login Node
- b) Secure shell to a Compute Node
- c) Secure transfer to a Data Transfer Node

---

<a href="{{ site.url }}"><button>BACK</button></a>
