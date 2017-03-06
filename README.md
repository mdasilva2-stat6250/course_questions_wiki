# Course Questions Wiki

This document contains questions and answers corresponding to reading from the course textbook.

To contribute,

1. fork this repo to your GitHub Account (e.g., using the "Fork" button in the upper-right-hand corner of the GitHub web interface),

2. make appropriate changes/corrections using Markdown (see https://guides.github.com/features/mastering-markdown/), and

3. initiate a pull request using

- the master branch of the stat6250/course_questions_wiki repo as the base fork and

- your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.

********************************************************************************

## Chapter 1 Questions


## Chapter 2 Questions

[Chapter 2, Problem 7]
- Question (IL): What's the difference between starting a SAS program with "data" versus "proc", and why do both end types of programs end with the same "run" command, even though the bodies of the programs look nothing alike?
- Answer (IL): SAS programs are divided into "steps", each step is either a data step or a proc step (as determined by the first word in the step), and all steps are typically terminated by a "run" statement. However, when using a "cards" or "dataline" statement in a data step, then the data step is terminated by a closing semicolon. In addition, some procs (like the interactive proc glm) are only terminated with a "quit" statement.

[Chapter 2, Problem 9]
- Question (IL): What is a "libref", and how does it differ from a "LIBNAME"?  In particular, what fundamental distinction causes one to be written out in lower-case letters and the other in upper-case letters?
- Answer (SG): A libname statement is the syntactical statement used to initiate a particular library. The libref is the actual syntax used to name it.

## Chapter 3 Questions


## Chapter 4 Questions


## Chapter 5 Questions


## Chapter 6 Questions


## Chapter 7 Questions


## Chapter 8 Questions


## Chapter 10 Questions


## Chapter 11 Questions


## Chapter 12 Questions

* **[Chapter 12, Problem 4]**
 * Question (JG): What is the result of submitting the following program?
 ```SAS
        data work.getobs5;
            obsnum=5;
            set company.usa(keep=manager payroll) point=obsnum;
            stop;
        run;
```

 * Answer: TBD

## Chapter 13 Questions


## Chapter 14 Questions


## Chapter 15 Questions


## Chapter 16 Questions


## Chapter 17 Questions


## Chapter 19 Questions


## Chapter 20 Questions