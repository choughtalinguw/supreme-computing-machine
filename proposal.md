# X-Team 50 Seat Selector

See https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#code for tips on using *Markdown* tags to format __.md__ files

## Goal

Work as a team to create a project proposal for your X-team to complete together.
The project does not have to be extremely difficult,
but there must be work to do for each member of your team.
You may reference figures using "See figure 1".  
Be sure to submit corresponding image files, i.e. figure1.png (or figure1.jpg) for each figure.

## Grading: To earn full credit, your team's proposal must include:

* (md) documentation: [this file] describing purpose and use of your program

* Description of a program that has:

  ** a main Java program class in a file named Main.java
  
  ** a custom data structure designed and built by your team
  
  ** comprehensive testing of individual units
  
 Caution: You are not being asked to implement this program, at least not yet. 
 We just want your group to make a proposal or pitch for your program.
 
 Tip: Your custom data structure can be composed of or extensions of data structures that you have learned and used in previous programming assignments.  We're looking for decisions about how to build a high-level data structure that will likely have lower-level components.

## Problem Description

Students today are facing a big issue: not knowing where to sit in lectures. Many days, students feel like they have to come to lecture extremely early in order to sit in their desired seat. This causes a big pile-up outside of the lecture hall and causes a huge traffic jam when the students in the previous lecture are still attempting to leave and there are other students in the next lecture piled up at the door. In addition, many students reserve seats for their friends, making it hard for others to get their desired seats when a large group of students decides to change the row they are sitting in for a given lecture. Also, many times there are not enough seats open for students or they don't want to distrub others who are already sitting in the seats, so these students will go to the back of the lecture room and sit on the floor. Showing up late to lecture is plays a role in this issue and causes unnecessary stress due to the fact that they have to find a seat or interrupt other students' notetaking in order to work their way to an open seat in the middle of the row. With this program, students will not have to face these issues anymore.

## Questions to answer for Exercise #2

1. Name: Give your project proposal a name (and edit the top line of this file)<br/>
Seat Selector


2. Output: Describe the output your program will produce. Include and example format of the output produced.<br/>
A user interface that displays avaialable and taken seats. Available seats will be in green and taken seats will be in red. There will be a confirmation upon sucessful reservation of your seat. You may also request a list of available or taken seats as a text represenatation. You will be able to lookup where a friend is sitting and request a seat next to them if available.



3. Input: Describe the data that is needed to solve your problem. Include an example format of the input data.<br/>
The layout of the lecture hall will be needed as input, which can also be used as the user interface. A student will be able to sign in and select a seat from the user interface which will automatically load in their name, student ID, and seat selection. When a student is absent, a student will be able to send in an excuse note as input.


4. User Interface: Describe a user interface for your program.  Use text menus or a simple graphic user interface.<br/>
Our interface will mainly consist of an outline of the student's selected lecture hall with information regarding the reservation status of the seats within the lecture hall. The seats that have already been reserved will be in red, and avaliable seats will be shown green. To help students locate their friends in the class, there will be a search bar in the upper right corner. In the upper left corner, there is a box containing seat details when a student chooses a seat. If the student clicks on a green seat, they will be able to see who is sitting there, what seat number they selected, and what time the seat was reserved at (red seats - figure 1). If a student chooses a green seat, they will see what seat number it is and have the option to reserve the seat (green seats - figure 2).


5. Types List: Break your solution idea down into units that you think can be implemented with a single class.<br/>



Name each interface or class and briefly describe its function or purpose.


## Edit and Submit this file and any figures referenced by this document.

