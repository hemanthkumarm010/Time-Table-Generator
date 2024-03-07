# Time-Table-Generator
The given code is a Java program that generates a timetable for classes based on the  availability of rooms, teachers, and their respective courses.
The detailed explanation and flow of the code: 
1. The program starts by defining a class named `JAVAPROJECTFINAL` with the `main` 
method calling the `timeTable` method. 
2. The `timeTable` method contains the main logic for generating the timetable. It 
initializes various ArrayLists and arrays to store room capacities, class capacities, class 
details, teacher details, and timetables. 
3. It prompts the user to input the number of available rooms and their capacities. It then 
sorts the rooms based on their capacities. 
4. It asks for the strength of each class and initializes the timetables for teachers, classes, 
and rooms. 
5. The program then iterates over each teacher, day, and period to assign classes to 
available slots based on various constraints such as teacher availability, class capacity, 
room capacity, etc. 
6. After generating the timetable, it prints the timetable in a tabular format showing the 
schedule for each teacher along with the corresponding rooms. 
7. It also identifies classes that could not schedule all their lectures due to room 
unavailability and prints a message for each such class. 
8. The program contains several helper methods like `input`, `inputInt`, `index`, 
`searchList`, `searchArray`, `countNull`, `countFill2d`, `count1d`, and `count2d` to 
perform specific tasks like handling user input, searching for elements in arrays, counting 
null values, etc.
