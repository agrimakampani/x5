XTeam 155's x5 Design Proposal 

XTeam Members: Agrima Kampani(kampani@wisc.edu), Isaac Weber(iweber2@wisc.edu), James Watson(jcwatson2@wisc.edu), Tony Zhou(zzhou366@wisc.edu)


Title: Helpful Todo List

Problem: As college students tend to take more than four courses per semester, they need a better system for them to know what assignments they should finish and what are the due dates for those assignments as well.

Primary Stakeholders: Students looking for a good way to stay on top of their course work. 

Graphical User interface:
-First, display a list of courses which the users are currently enrolled
-Then the user can click the desired course icon to read the to do list for this course.
-Inside the to do list, there will be nothing fancy or complicated graph but a list of straight forward bullet-points tasks that need to be done.
 -the name of the assignment
 -due date

Data Structure:
-linked list
  - each node in the linked list will have a key corresponding to the couse code (ex. CS400 or Math222)
  - in this node there will be infomation on homework assignments coming up, exams and a place for you to write notes for yourself
  - the nodes will be stored at an index generated by the course code
----------------------------------------------------------------------------------------------------------------------------------------



Input Data File Format:
-course name: xxxx
-assignmet name: xxxx
-due date: xx/xx/xx:xx xx


Output Example:



Milestones: Describe discrete points or independent units, where parts of the project's functionality can be completed and can be tested or demonstrated independently of the final overall program.  Organize or order your milestones so that you can complete the most independent parts first, and then build on those working parts or prototypes.  
  - Finish implementing the data structure (back end) and be able to load data from a file into the data Structure
  - Implement gui (front end) 
  - tie the back end to the front end to make the app functional

Assign Tasks: 
James and Tony - Setting up the linked list data structure, including the ability for the user to make additions or subractions from the to-do list. This also includes a way to display the information when requested.
Isaac and Agrima - Implementing the data structure into the GUI so that the user has an easy time using the to-do list. This will be done by using the input from the GUI as requests from the user, meaning that information can be displayed, hidden, added, or deleted.
