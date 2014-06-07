AsanaSubtaskSequenceCreator
===========================

Script to create a sequence of subtasks in Asana

###Overview
The script can create N number of subtasks automatically. For example, a list of chapters: "Chapter 1", "Chapter 2", etc.
This can simplify the manual effort needed to create hundreds of subtasks.

It can be modified to create tasks instead of subtasks. Read the Asana API docs for more information: http://developer.asana.com/documentation/

###Usage instructions
* Checkout the package and open the subtaskgenerator file.
* Edit the file and add all the required information such as account API key, parent task id, number of subtasks.
* Optional fields are START_DATE which is the due date for the first sub task, INTERVAL DAYS which is the time interval between each subtask and the ASSIGNE ID.
* Run the script using "bash subtaskgenerator < SUBTASK NAME >".

###Note
Tested only on Mac OS X.
The syntax for the date field might be different in other linux distributions.
