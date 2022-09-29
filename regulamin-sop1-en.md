# Purpose of course

The first goal of the *Operating Systems I* course is to familiarize students with basics of operating system operation and design. The second goal is to develop student skills in correct application of system functions to design and implementation of simple multi-process/multi-thread applications which communicate using standard input/output channels and files.

# Conducting classes

The subject consists of a lecture and a laboratory.

- The lectures introduce students to the course matter, in particular to the topic covered by the laboratory.
   - The course consists of 15 lecture hours in 2-hour blocks. The last lecture is 1 hour long. Lectures take place according to the schedule provided on the course website.
   - The lecture materials are available on the course website.
   - There are no lecture tests. The lecture content will, however, appear in the introductory tests during the laboratory.

- The laboratory consists of five classes denoted as Lab0, Lab1, Lab2, Lab3, Lab4. The laboratory classes take place according to the schedule provided on the course website. The course website also includes preparation materials for classes.

	- L0 classes are classes devoted to the preparation of the environment. During these classes, students have to recall the skills of the Unix Fndamentals class and to configure the development environment. Any deficiencies in the configuration or these skills (e.g. lack of intellisense, underlining errors in the editor, or poor ability to navigate through directories) in all subsequent classes are not an excuse for poor grades and cannot be use as an excuse for less strict grading.
    - Lab1, Lab2, Lab3 and Lab4 classes assess abilities in the topics given in the laboratory schedule. You should prepare on your own for each class, using the materials on the course website and lecture materials. Each of the classes consists of three parts:

	    - questions and answers (approx. 30 minutes): during this part, the teacher answers students' questions and explains any 
		- entry (8 minutes): solving the moodle test
        - programming task (90 minutes)
		
	- In the exam session, there is a retake where you can improve your grades in exactly one topic (Lab1, Lab2, Lab3, or Lab4). You can retake either one part (test, program) or both. Registration for the retakes will start immediately after the last laboratory classes in the semester and will be open for **24 hours** only.


# Course materials

 - Materials provided during the lecture (e.g. slides, code snippets)
 - Literature given at the lecture and available on the subject's website
 - Descriptions of laboratory exercises on the subject page
 - [The GNU C library manual] (http://www.gnu.org/software/libc/manual/)
 - [The Single UNIX specification, Version 3] (http://www.unix.org/version3/online.html) (includes IEEE Std 1003.1 and ISO / IEC 9945)
 - [POSIX FAQ] (http://www.opengroup.org/austin/papers/posix_faq.html)


# Class attendance

- Attendance of the lectures is not obligatory but recommended due to the close connection between the discussed material and the laboratory.
- Attendance at laboratory classes is obligatory. In case of absence, the student receives 0 points for activities carried during the classes in which he was absent.
- Absence from two of the assessed laboratory classes Lab1/Lab2/Lab3/Lab4 results in failure to complete the course.

DOTĄD ZROBIONE

# Verification of achievement of learning outcomes

In-line verification. There are four laboratory classes during the semester, covering 4 topics, marked with the abbreviations L1, L2, L3 and L4.

Methods of verifying the effects in the laboratory:

- Entrance fee
  - Test verifying the knowledge of the lecture and preparation materials for the laboratory. Each entry includes all the lectures preceding and all the preceding laboratory topics and the current laboratory topic.
  - Closed, multiple-choice questions (any number of answers greater than 0 can be correct), performed on the moodle platform.
  - The entrance ticket consists of 4 questions, for each question you can get a score in the range of [0.2] points. In total, for the entire test, a maximum of 8 points.
  - The entry fee is scored as follows. In each multiple-choice question there are * n * correct answers and * m * incorrect answers (each answer is either correct or incorrect). There is 2 / n points for each marked correct answer, and for each marked incorrect answer there are -2 / m points. For each question, the sum of points resulting from the marked incorrect and correct answers is awarded, as long as the sum obtained is not negative. In this case, 0 points are awarded.
  - The admission is 8 minutes.

- Programming task

     - To be obtained from 0 to 17 points
     - There are 90 minutes to complete the task
     - A programming task is divided into stages. Points for each stage are given in the content of the task. The steps must be performed in the prescribed order. It is not allowed to proceed to the next stage without completing the predecessors.
     - Each stage is checked and assessed in class. The ability to use appropriate tools and the correct (including POSIX-compliant) implementation of the required functionality is assessed. Apart from L3, the aesthetics of the code are not assessed.
     - At the end of the class, the code version containing all the steps to be assessed must be copied to the network share (more information at the end of the page). Lack of implementation of any of the functionalities in the code sent means that the points for a given stage are reset.
     - The solution of the L3 task will also be assessed in terms of code aesthetics. The assessment will be made after the class. Penalty points are awarded for problems in the code, which are subtracted from the points obtained during the classes. You can lose up to 10 points, but not more than the number of points obtained during the classes.
     - Laboratory tasks are solved using the Arch Linux system on the computers in the laboratory. It is not allowed to show solutions on your own computer.
- The form of handing over the task

   - The task must be performed in * C * (not C ++)

   - The solution of each task must be sent in the form of an archive in the format `.tar.gz`,` .tar.xz` or `.tar.bz2` so that after unpacking the archive with the flags` -xjf`, `-xJf` or` -xzf` has created a subdirectory named `$ USER` containing all required files. `$ USER` is the department login.
   - The archive must contain only source files (`.c`,` .h`) and a `Makefile`
   - The `Makefile` is supposed to allow you to compile the entire solution with a single * make * command
   - When compiling `gcc` * obligatory * to use the * -Wall * flag and other flags required in the task
   - The ready archive should be uploaded to the directory on the network share indicated in the content of the task.


# Aids acceptable for use in verifying achievement of learning outcomes

- While solving the pass **, you cannot ** use any auxiliary materials. Communication with others is not allowed.
- When solving programming tasks **, you can ** use the tutorial, your own materials, solutions to sample tasks, system documentation and the Internet, however, so that the assessed work is an independent work.

# The rules for passing the course and for calculating the final grade

 - To pass the course, it is necessary to obtain a total of at least 50 points (out of 100 possible), and to attend the number of classes required in Attendance section.
 - The points from retake always replace the result scored during the lab
 - **The final course grade** is based on total points acquired by student during the labs (100p tops):

| Points in total | Grade |
| --------------- | ----- |
| s≥90            | 5     |
| 80≤ s \<90      | 4.5   |
| 70≤ s \<80      | 4     |
| 60≤ s \<70      | 3.5   |
| 50≤ s \<60      | 3     |
| s\<50           | 2     |


# Deadline and procedure for announcing grades

- Partial grades

  - The number of points obtained for the subsequent stages of the laboratory task is given at the time of checking by the teacher and written on a sheet with the content of the task
  - The number of points obtained for entry is displayed in moodle after the test is completed
  - Points from both parts of the laboratory are placed in the nose no later than 24 hours after the class. The number of points inscribed in the usos determines the final grade
- Final evaluation
  - Issued in USOS within 24 hours from the publication of the results of the last L4 laboratory in USOS
  - Corrected during the exam session within 24 hours from the publication of the results of the resit laboratory in USOS


# Rules of repetition of classes due to failure of a subject

A person who did not pass the course must repeat the entire course and write to proceed with all the exams. It is not possible to rewrite partial credits from previous semesters.

# Others

