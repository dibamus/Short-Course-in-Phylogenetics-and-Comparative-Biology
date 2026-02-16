A Hands-On Short Course on Phylogenetics and Comparative Biology in R
================
Isaac krone
2025-10-21

# A Hands-On Short Course on Phylogenetics and Comparative Biology in R

I wrote this short course on phyloegenetics and comparative biology as a
three-week lab exercise and final project for students in Dr. Rauri
Bowie’s Ornithology course when I taught it in the spring of 2025. For a
while, Rauri had wanted to replace some of the lab content on passerine
diversity (now split into too many families with too much convergence to
be approachable as an identification problem for students) with a unit
on phylogenetics, and that’s easy enough to do in R now that we could
teach proper comparative biology as well. While the course is written
with birds as a focal group, the workflow and concepts here can be
applied to any group of organisms.

As such, this course is written for advanced college students, but I
have striven to design it to be accessible to almost anyone and not
assume too much biological expertise. It does take for granted that you
know what a phylogeny is because it assumes you want to make one. I’ve
designed this so that minimal coding knowledge is necessary, but it’s
best completed with the help of someone a bit knowledgeable in R so that
they can help you troubleshoot; most of the problems running this happen
because of small mistakes in formatting input files or not having the
right files in the right place, and a working understanding of R, or an
inquisitive mind and a willingness to read some Stack Overflow posts,
will help you get through the hiccups. Making mistakes is an important
part of the learning process.

Experienced comparative biologists will notice the seams here; the code
skips steps, relies on a few simplifying assumptions and
not-universally-recommended procedures to keep the exercises brief while
teaching important concepts, and to keep the code (somewhat) readable
for users. In our first run teaching this course in 2025, the code
itself worked very well; the biggest challenge I had was making sure
students understood where files were in their computer filesystem,
something that should be mitigated by distributing all of the assets to
students in a single .zip download.

You’re free to use, distribute, and modify this project as you see fit:
all of the data are from publicly available sources. If you do
redistribute this, please include a link back to this page in your
materials. If you’re an educator and want to use this for a class, I’d
really appreciate your feedback!

## Structure of the Course

This course contains four tutorials and a final project. in the three
tutorials, you’ll build trees, run analyses, and produce figures that
will all be arranged nicely in the final project document. Students
following along are advised to get all of the figures and analyses
running and nice-looking in the final project, then “knit” that project
to a .docx file that can be completed in a regular word processor.

### Tutorial 0: Getting Started with R

Follow this tutorial to get R and Rstudio installed on your computer,
and save the name of your focal group to a file - you’ll need that
later.

### Tutorial 1: Collecting genetic data

Think a little bit about choosing an outgroup for your study, then
select a gene and start gathering data. At the end of this tutorial,
you’ll have aligned genetic data. This is a place where a practiced eye
can be very helpful. Does your alignment look right? Are there taxa that
seem poorly aligned? You might have to repeat some of this tutorial
multiple times to ensure that you end up with a trustworthy dataset.

### Tutorial 2: Building Trees

This tutorial is split into two parts; in the first part, you’ll learn
the basics of how a few approaches to phylogenetic inference work using
a very small example dataset. In the second part, you’ll use a more
complete alignment - either example data or your own alignment from
tutorial 1 - to build a more advanced tree.

### Tutorial 3: Comparative Methods

Now that you have a tree, you can do some serious comparative biology.
Gather data from the included datasets or other sources and map
character change on trees, then run phylogenetic linear regressions to
investigate evolutionary correlations between characters.

### Final Project

This final project provides students a strong scaffold to present their
results, demonstrate their understanding of the process, and interpret
patterns biologically. It’s pretty easy to grade and gives students
clear guidance. No new analyses are introduced here.
