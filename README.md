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
The view functionality of the project is completed by two .fxml files, main-window-view.fxml and edit-students.fxml. Screenshots of the graphical user interface demonstrating various functions of the programme can be seen below. 

#### Screenshot showing main-window-view on startup:

<img width="702" alt="Screenshot 2022-03-28 at 23 08 47" src="https://user-images.githubusercontent.com/65253959/160495810-04496d1b-f054-425a-a4ac-c2fca6220a8b.png">



#### Screenshot showing edit-students on startup:

<img width="583" alt="Screenshot 2022-03-28 at 23 09 58" src="https://user-images.githubusercontent.com/65253959/160495869-73ec2a59-316e-4f2f-9e7f-fcc56801bc83.png">



#### Screenshot demonstrating deleting a student:

<img width="701" alt="Screenshot 2022-03-28 at 23 10 23" src="https://user-images.githubusercontent.com/65253959/160495942-6d59306d-25f4-4d2b-a7a8-d24f78316210.png">



#### Screenshot demonstrating an error occuring:

<img width="701" alt="Screenshot 2022-03-28 at 23 11 11" src="https://user-images.githubusercontent.com/65253959/160495994-197721cb-009a-4b63-8125-00edc75ea291.png">


