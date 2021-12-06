# Syllabus - CMPEN 472, Microprocessors and Embedded Systems

## Staff

### Instructor: [Kyusun Choi](www.cse.psu.edu/~kxc104)

|              |                                         |
| ------------ | --------------------------------------- |
| Office       | 325 Leonhard Building                   |
| Phone        | (814) 863-1268                          |
| Email        | [kxc104@psu.edu](mailto:kxc104@psu.edu) |
| Office Hours | 2:30 PM -> 4:00 PM Tuesdays             |
|              | 3:45 PM -> 5:15 PM Wednesdays           |

### Teaching Assistant: Samuel Abrams

|              |                                          |
| ------------ | ---------------------------------------- |
| Office       | [Zoom](https://psu.zoom.us/j/9549749872) |
| Email        | [sba6@psu.edu](mailto:sba6@psu.edu)      |
| Office Hours | 3:30 PM -> 5:00 PM Mondays               |
|              | 3:10 PM -> 4:40 PM Thursdays             |

### Course Material Written by Vins Sharma

|       |                                           |
| ----- | ----------------------------------------- |
| Email | [vms5391@psu.edu](mailto:vms5391@psu.edu) |

## Required Material

In order to complete this course, students will need a **Raspberry Pi** to
develop on. Any version (2, 3, 4) is fine, but the Raspberry Pi Model 4b is what
teaching material is tested and developed on.

Students will also need a **USB-C cable** to connect their Raspberry Pi to their
computer.

In order to set up the Raspberry Pi, a **Micro-SD card** is required to transfer
the serial monitor. Students who do not have this may speak with the instructor.

Finally, a **tester board** is required. This board contains several LEDs,
switches, and 2 7-segment displays in order to show functionality of assembly
programs. _More on this later._

## Laboratory Access

- Students can perform all laboratory assignments with their own laptops. More
  on required material will be below.
- Students can also access the CSE Windows PC Lab in _Room W136 Westgate._
  Please see the instructor if you need remote access.

## Textbooks

This course does not have traditional textbooks - Instead, we have datasheets.

- [The course site](www.cse.psu.edu/~kxc104/class/cmpen472/22s/index.html) has
  most of the learning and teaching material.
- The
  [ARMv8 Instruction Set Architecture](https://documentation-service.arm.com/static/613a2c38674a052ae36ca307?token=)
  is a simplified instruction set architecture, and is the easiest way to learn
  instructions from ARM.
- The
  [BCM2711 ARM Peripherals Manual](https://datasheets.raspberrypi.org/bcm2711/bcm2711-peripherals.pdf)
  is a full manual detailing the various peripherals on the Raspberry Pi board
  that can be used. We'll use a few of these for the course.
- The
  [ARM Cortex-A Series Programmer's Guide for ARMv8-A v1.0](https://developer.arm.com/documentation/den0024/a)
  has a lot more information in the form of technical documentation.
- The
  [ARM Architecture Reference Manual Armv8, for Armv8-A Architecture Profile](https://developer.arm.com/documentation/ddi0487/ga)
  contains a PDF of all ARM instructions. It's a PDF that's 8,538 pages long.

## CMPEN 472 Web Page

The [course's web page](www.cse.psu.edu/~kxc104/class/cmpen472/22s) contains all
announcements, homeworks, and course material.

---

## Grading Scale

The course will be graded as follows:

| Type              | Percent   |
| ----------------- | --------- |
| Homeworks         | 40%       |
| Quizzes           | 10%       |
| Research Projects | 50%       |
| Special Projects  | 10% Bonus |
| **Total**         | **110%**  |

Based on what score students receive, the following (tentative) grading scale
will be in place:

| Grade | Percent Range |
| ----- | ------------- |
| A     | 93% -> 100%   |
| A-    | 90% -> 92%    |
| B+    | 87% -> 89%    |
| B     | 83% -> 86%    |
| B-    | 80% -> 82%    |
| C+    | 77% -> 79%    |
| C     | 70% -> 78%    |
| D     | 60% -> 69%    |
| F     | 0% -> 59%     |

## Homeworks

Ten homework assignments will be given throughout the semester. **Late homework
will not be accepted.** Each homework assignment will be 4% of the overall
course's grade.

Every homework assignment will be graded out of 100 points based on a rubric,
specified in the assignment's description.

All homework assignments are to be completed as a strictly individual effort. No
homework assignments will be dropped.

## Quizzes

Approximately twelve pop quizzes will be given during the semester. Every quiz
will be graded out of 10 points. Each quiz will make up 1% of the final grade.

**Missed quizzes cannot be remade.** However, the two lowest quiz grades will be
dropped.

## Research Projects

In lieu of exams, 5 research projects will be given throughout the semester.
**Late project submissions will not be accepted.** In these, students will
generally watch videos or research topics specified and answer questions.

Each research project will be 10% of the final grade. No research projects will
be dropped.

## Special Projects

Special projects are guided watered down variants of the homework assignments,
that are assigned before each homework assignment. Students can complete them
and receive up to 10 points on the paired homework assignment.

**Late project submissions will not be accepted.** No project submissions will
be dropped, though special project submissions will not lose credit if students
fail to submit them. However, students who complete these special projects will
tend to learn more about the paired homework assignment and will tend to get
better grades on the homework assignments as a result.

---

## Course Objectives

This course primarily has two focuses:

### Focus 1: Microcontroller Programming

Many electronic devices now include microprocessors inside in what is known as
an "embedded" processor system. After taking this course, students should have
the tools and knowledge needed to learn about more embedded systems (or apply
their skills in the ARM assembly language.)

Students should be able to design both the software and the hardware of such
systems. In addition, the knowledge of ARM assembly programming will enable
students to be better prepared to use other microprocessors and microcontrollers
as desired.

Students may even be able to design their own microprocessors and
microcontrollers.

### Focus 2: Embedded Systems Courses

Students will learn the background required to take on future embedded systems
courses, such as the embedded systems laboratory course CMPEN 473. In addition,
students will learn about various related topics to tackle courses as graduate
or senior electives.

---

## Academic Integrity

Unless explicitly stated, collaboration on assignments and quizzes is **not
permitted.** However, feel free to discuss with anyone at all, ever, following
two simple rules:

1. Make a solid effort to solve a problem on your own before discussing it with
   classmates and/or googling,
2. Write up the solution completely on your own, without having their answers in
   front of you.

Be sure to follow the following academic integrity guidelines:

- [Academic Administrative Policies and Procedures Manual](https://undergrad.psu.edu/aappm/G-9-academic-integrity.html):
  Penn State's academic integrity page
- [Academic Integrity Standards for CMPSC, CMPEN, and CSE Programming Courses](https://www.eecs.psu.edu/students/resources/EECS-CSE-Academic-Integrity.aspx):
  Penn State's Department of CSE academic integrity page

**Do not** post your CMPEN 472 work online. **Do not** share your CMPEN 472 work
with others during this semester. **Do not** share your CMPEN 472 work with
others after this semester.

## Penn State Health Guidelines and Other Policies

Be sure to follow the Penn State health guidelines and other policies listed
below:

- [Penn State Health Guidelines](https://virusinfo.psu.edu/health-guidelines/)
- [Penn State Policies](https://policies.psu.edu/)
