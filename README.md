# Database Systems  CS305

## Midterm: 9 November 2023

## Due: Before 12:20AM on 11 November 2023

Please note that at 4:20PM on 9 November 2023 you will lose `write` access to your exam repository and will no longer be able to commit and push to it. Please make sure all of your work has been submitted before the lab ends at 4:20PM.

![bases](./graphics/testing.png)

Public school students take an average of about 112 standardized tests between pre-K and 12th grade. Many of the collected results are studies by superintendents to get an idea about how well a school is able to teach and pass its students. In this midterm, we utilize data from a small school study to create a database. This database will then used to understand some of the conditions which may be linked with student success at school.

## Instructions

* Write a builder file to build a database from the provided data file: `src/data/StudentsPerformance_d`. 
  * Be sure that this builder file is free or errors and that your instructor can use it to build your database.
  * Please submit your builder file `src/db_build.txt` along with your database `src/school_db.sqlite3`

* Address the questions in the file, `writing/queries.md`. Often, your responses will require writing queries to inform, or to fully complete, the question's challenge.
  * Please submit your queries in `writing/queries.md`.

* You are to submit this work to your GitHub repository at least three (3) times. Please enter all code from class as your deliverable.

* Do not discuss the midterm with each other -- you are bound by the honor code.

## Project Assessment

The grade that a student receives on this assignment will have the following components.

* **GitHub Actions CI Build Status [up to 15%]:**: For the lab repository associated with this assignment students will receive a checkmark grade if their last before-the-deadline build passes. This is only checking some baseline writing and commit requirements as well as correct running of the program. An additional reduction will given if the commit log shows a cluster of commits at the end clearly used just to pass this requirement. An addition reduction will also be given if there is no commit during lab work times. All other requirements are evaluated manually.

* **Mastery of Technical Writing [up to 25%]:**: Students will also receive a checkmark grade when the responses to the writing questions presented in the deliverable Files of the directory `writing/` that reveal a proficiency of both writing skills and technical knowledge. To receive a checkmark grade, the submitted writing should have correct spelling, grammar, and punctuation in addition to following the rules of Markdown and providing conceptually and technically accurate answers.

* **Mastery of Technical Knowledge and Skills [up to 60%]**: Students will receive a portion of their assignment grade when their program implementation reveals that they have mastered all of the technical knowledge and skills developed during the completion of this assignment. As a part of this grade, the instructor will assess aspects of the programming including, but not limited to, the completeness and the correctness of the program and the use of effective source code comments.

## GatorGrade

You can check the baseline writing and commit requirements for this lab assignment by running department's assignment checking `gatorgrade` tool. To use `gatorgrade`, you first need to make sure you have Python3 installed (type `python --version` to check). If you do not have Python installed, please see:

* [Setting Up Python on Windows](https://realpython.com/lessons/python-windows-setup/)
* [Python 3 Installation and Setup Guide](https://realpython.com/installing-python/)
* [How to Install Python 3 and Set Up a Local Programming Environment on Windows 10](https://www.digitalocean.com/community/tutorials/how-to-install-python-3-and-set-up-a-local-programming-environment-on-windows-10)

Then, if you have not done so already, you need to install `gatorgrade`:

* First, [install `pipx`](https://pypa.github.io/pipx/installation/)
* Then, install `gatorgrade` with `pipx install gatorgrade`

Finally, you can run `gatorgrade`:

`gatorgrade --config config/gatorgrade.yml`

## Seeking Assistance

* Extra resources for using markdown include;
  * [Markdown Tidbits](https://www.youtube.com/watch?v=cdJEUAy5IyA)
  * [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
* Do not forget to use git commands to push your work to the cloud for the instructor to grade your assignment. You can go to your GitHub repository using your browser to verify that your files have been submitted. Please see the TL’s or the instructor if you have any questions about assignment submission.

Students who have questions about this project outside of the lab time are invited
to ask them in the course's Discord channel or during instructor's or TL's office hours.
