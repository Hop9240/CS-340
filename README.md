# CS 340 Portfolio — Grazioso Salvare Dashboard

## Project Overview
This project provides an interactive dashboard that helps Grazioso
Salvare identify shelter animals that meet rescue training requirements.
This dashboard reads animal records from MongoDB through a reusable
Python CRUD module.

Users can filter animals by rescue category, inspect their records,
view breed proportions in a pie chart, and select an animal to display
its location on a map.

## Writing Maintainable, Readable, and Adaptable Programs
I write maintainable, readable, and adaptable programs by separating
database operations from the rest of the application and using clear
names for methods and parameters. In Project One, I created a CRUD
Python module that served as a reusable foundation for Project Two.
The dashboard could call its methods and pass in queries instead of
repeating the database code for each widget.

This approach made the program easier to maintain because I could
update the database operations in one place. As I learn more efficient
techniques, I can improve the CRUD module while keeping its methods
compatible with the code that uses them. In the future, I could reuse
this foundation for another dashboard or application that needs to
create, read, update, and delete MongoDB records.

## My Approach to Solving Problems
I approach computer science problems by making them real to me.
I put the problem into a situation I understand and ask myself:
What is the problem? What do I already know? What do I still need
to learn? What is the benefit of solving it?

For example, I understood MongoDB by comparing a database to a
filing cabinet. A collection is a drawer, a document is one file
inside that drawer, and a field is a labeled piece of information
within the file. This comparison helped me understand how the
animal records were organized and how queries could retrieve
the information Grazioso Salvare needed.

## The Role and Impact of Computer Scientists

I believe the role of a computer scientist is similar to that of
a scientist studying the natural world. Both require patience,
determination, and a willingness to study complex subjects in depth.
Like a marine biologist who studies ocean life, a computer scientist
explores systems and uses that knowledge to solve problems and make
them easier for others to understand.

People often understand their work and have a vision for improving
it, but they may not have the technical knowledge to build the tools
they need. Our job as computer scientists is to understand that vision
and turn it into something useful. We make information easier to
access and create tools that help people navigate complicated tasks.

For Grazioso Salvare, this means providing a dashboard that helps
staff find shelter animals that meet rescue training requirements.
Instead of needing to write database queries themselves, staff can
filter records and explore the results through a clear interface.
This helps them spend less time searching for information and more
time evaluating animals for rescue training.






