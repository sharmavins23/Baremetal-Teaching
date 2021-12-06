# 01-00 Overview and Topics

_What are we doing in this course? What are we hoping to accomplish?_ This page
hopes to solve some of those questions (and possibly more!)

## What are we programming?

We're programming a Raspberry Pi (4, 3, 2, whatever you have.)

### No, really?

In all seriousness, we're programming on the actual metal. Hence, the term
**"baremetal"**. The idea is to program a microcontroller by itself (so, without
any of the higher-level abstractions.)

EE students will remember (and possibly shudder at) taking the course EE 200. In
this course, students programmed Atmel microcontrollers to emulate state
machines. However, in that course, students generally used the C programming
language, which was compiled down to some sub-language of assembly (AVR) and
eventually written into the registers as machine code.

In this course, we hope to skip those steps and write assembly directly to the
registers, such that code can be compiled and executed quickly and without
significant delay. We can also learn a lot about the programming process by
working from the ground up, rather than the top down (as is customary in most
CMPSC programs.)

### So what is a Raspberry Pi?

Unlike the Atmel controllers that EE students are used to, or Arduino
microcontrollers, Raspberry Pi sets itself apart in that you can run an
operating system (Raspbian) directly from the controller. This means that
everything about the OS is already baked into the controller and board (that is,
a kernel and all of the protected registers alongside it.)

This course isn't focusing on that - Actually, we'll be purposefully avoiding it
for the remainder of the course. As such, a Raspberry Pi is functionally
equivalent to any other microcontroller:

- It uses some language of Assembly (in this case, ARMv8)
- It has some form of registers (we'll talk more on these later)

That's really it.

### Why not any other microcontroller?

CMPEN 473 is the pair course to this one, and in that course, we go a step up
from Assembly and program Raspberry Pi to control robots. As such, it's handy to
use the same microcontroller for both courses.

Otherwise, ¯\\\_(ツ)\_/¯

## How are we programming it?

We're going to be loading a serial terminal onto the Raspberry Pi in order to
write terminal-style code. Otherwise, all ARM assembly will be loaded directly
to the registers and memory of the device.

## What projects will we be doing?

The first portion of the course will focus on projects related to LED light
control in a software context.

The second portion will focus on terminal integrations, such as interactive GUI
programs and writing code that responds to the user in a text-based format.

At the end of the course, we'll combine the two.
