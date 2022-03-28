# StudentSystem
University assignment to create a system for students to make and edit choices of modules. The system makes use of a Model-View-Controller software design pattern, utilising JavaFX to create and display a Graphical User Interface.

### Model

##### Student
The Student class creates a data structure to store the details and module choices for individual students. Getters are included to return the students student Id number, year of study, and three module choices.

##### StudentData
The StudentData class is a singleton class which includes an ArrayList to store all instances of Student to be included on the system. Various methods are included to update the data structure either for adding new students, amending students, or deleting students.

### Controller
##### Controller
The controller class is responsible for carrying out actions when a user interacts with the main window view. Event listeners are initialised and methods included to complete the functionality of adding, editing and deleting student data in conjunction with StudentData.

##### EditStudentController
The EditStudentController class performs similar functions to Controller, however instead controls a view window for editing student details. 

### View




