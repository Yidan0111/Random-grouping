# Random-grouping
random grouping mode


!!!!!!!!!!! https://youtu.be/JQw4wbvtxcc 
This is the link to download the guide video, which is part of the tool ( but it is not neccessary) 


The tool is built using HTML for the user interface and JavaScript for the functionality. Here's a breakdown of the key components:

- HTML: Defines the structure of the web page, including input fields, buttons, and placeholders for displaying groups and unassigned members.

- JavaScript: Provides the functionality to shuffle names, toggle grouping modes, apply grouping rules, and generate groups that satisfy the specified criteria.

- CSS: Adds styling to the web page, including background images and text color.
Enter student name:
Users can enter student names separated by commas. For example: “Alice, Bob, Cindy.”

 Grouping method:


Number of groups (medium mode):
Users specify the number of groups they want, and the tool distributes students evenly (or as fairly as possible) within the specified number of groups.
Number of people (fixed mode):
Users specify the size of each group, and the tool divides  students into groups of that size.
Custom number of people (custom mode):
Users specify the number of people in each group by providing a comma-separated list of numbers. For example: “5,6,7” means the first group will consist of 5 people, the second group will consist of 6 people and the third group will consist of 7 people.
Filter group options:


Must be together:
Users can specify pairs of students to be grouped together. These pairs are separated by commas, and different pairs are separated by semicolons. For example, "Alice, Bob; Eve, Frank" ensures that Alice and Bob are in the same group, as are Eve and Frank.
We can't be together:
Conversely, users can specify pairs of students that should not be grouped together using the same format as above. Create random groups:
Once the parameters are set,  the user clicks the “start pool” button, which activates the randomization process. This tool will:


Shuffle the list of student names.
Create groups based on selected mode and constraints.
Make sure the  groups created meet the “must be together” and “cannot be together” rules.
Show results:


The created groups will be displayed on the screen.  If there are students who cannot be assigned to any group due to anticipated limitations, they will be marked in red.
Multimedia integration:


There is a built-in audio player that automatically plays and repeats a specified audio file.
There is also a built-in video player that allows users to watch  related videos.
Essentially, your tool provides a flexible and intuitive solution for generating random groups while taking into account specific user-defined constraints. 
