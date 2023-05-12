# FINAL CAPSTONE : Task Management Program 
========================================
## Table of Contents:

* About the Program
* Installing the Program: Cloning and installing the project locally
* Languages
* How to use the Program: step by step instructions
* Credits

* * *

## ABOUT THE PROGRAM:
------------------

* * * 

This _Task Management Program_ program is a software application that allows users to create and manage tasks efficiently. Users can input task details, set deadlines, and assign tasks to individuals, and generate reports. This program helps individuals and teams stay organized, prioritize work, collaborate effectively, and ensure tasks are completed on time.



## INSTALLING THE PROGRAM: Cloning and installing the project locally
----------------

* * *


1. Open your web browser and go to the GitHub repository page of the project you want to clone.

2. Look for the green "Code" button on the right side of the page, and click on it revealing a dropdown menu.

3. In the dropdown menu, you will see a URL of the repository. Make sure the URL is set to "HTTPS" if you want to clone using HTTPS. Alternatively, you can click on the clipboard icon next to the URL to copy it manually.

4. Open a terminal or command prompt on your computer.

5. Navigate to the directory where you want to clone the project. You can use the cd command followed by the directory path to navigate.

6. Once you are in the desired directory, use the git clone command followed by the repository URL you copied or the one provided on the GitHub page. For example:

bash
Copy code
git clone https://github.com/username/repository.git
Press Enter to execute the command. Git will start cloning the repository into a new directory.

7. Once the cloning process is complete, you will have a local copy of the project in the specified directory.

8. Navigate into the cloned directory using the cd command:

bash
Copy code
cd repository

9. Ensure the necesary dependencies are installed. In this case: Python only.



## LANGUAGES:
----------------

* * *

*   Python

* * * 

## HOW TO USE THE TASK MANAGEMENT PROGRAM: Step by step instructions
----------------

* * *

1. Run the program. 
2. The console will display and request a username & password. 

<img width="502" alt="Screenshot 2023-05-12 at 11 01 23" src="https://github.com/stephaniecrocker91/finalCapstone/assets/90976092/9d09c2c5-f200-43c3-a6ab-007feb46bd31">

-  These details are stored in the user.txt file generated when running the program. When the program is run for the first time, the admin user and password is created: admin; password

<img width="362" alt="Screenshot 2023-05-12 at 11 05 49" src="https://github.com/stephaniecrocker91/finalCapstone/assets/90976092/27abdd11-3053-4a05-9d72-e5eb2bcecd86">

- If username does not exist or password does not match, appropriate error message will appear and the console will request details again. See example below: 

<img width="368" alt="Screenshot 2023-05-12 at 11 08 23" src="https://github.com/stephaniecrocker91/finalCapstone/assets/90976092/3d760d07-3e33-4ab5-b9d6-344888fedf3e">

3. Once user is logged in, the main menu is displayed.

<img width="368" alt="Screenshot 2023-05-12 at 11 10 19" src="https://github.com/stephaniecrocker91/finalCapstone/assets/90976092/dc16be43-37cd-4eb8-943e-d363f0dcb320">

Program requests a user input from the options above. 
If the entry is invalid, appropriate error message is displayed, and the menu options are presented once again.

<img width="368" alt="Screenshot 2023-05-12 at 11 12 05" src="https://github.com/stephaniecrocker91/finalCapstone/assets/90976092/5feec1ba-a530-47ae-83f1-16c507ba70eb">

### MENU OPTIONS:

#### Registering a user - r
1. When inputting "r" the user is selecting Register a new User.
2. The program requests the username, password, and confirm password.

<img width="368" alt="Screenshot 2023-05-12 at 11 14 11" src="https://github.com/stephaniecrocker91/finalCapstone/assets/90976092/549923ec-b18b-4b60-9c5e-7a371f976dec">

If the username is already taken (already exists in our user.txt file) or the passwords do not match, an appropriate error message is displayed and the program requests the new username details again.

<img width="368" alt="Screenshot 2023-05-12 at 11 15 39" src="https://github.com/stephaniecrocker91/finalCapstone/assets/90976092/855ad53d-f471-4707-9051-3c31ad597c96">

4. Once the input is correct, the new user details are written and saved in our user.txt file.

#### Adding a task - a

1. When inputting "a" the user is selecting Add a new task.
2. The program requests the user assigned to task, task name, task description and task due date.

 <img width="368" alt="Screenshot 2023-05-12 at 11 20 24" src="https://github.com/stephaniecrocker91/finalCapstone/assets/90976092/489b27c0-077d-443d-b46d-8711b7ca5b33">
 
3. The writes and saves these details the task.txt file.

It automatically generate and saved the following details: assigned_date (by assigning the date.today()) and completed (boolean value with a default of False)

Appropriate error messages will be displayed if: task is assigned to a non-existant user, or the date is input in the wrong format. In this case, the program will request task details again.

<img width="368" alt="Screenshot 2023-05-12 at 11 26 57" src="https://github.com/stephaniecrocker91/finalCapstone/assets/90976092/915e1d39-5919-4b9f-bf53-701a38c20b8b">

4.Once finialised, program returns to main menu.

#### View all tasks - va
1. When inputting "va" the user is selecting View all Tasks.

<img width="368" alt="Screenshot 2023-05-12 at 11 30 12" src="https://github.com/stephaniecrocker91/finalCapstone/assets/90976092/e623b2e5-04f1-482f-9112-626068b6b444">

2. The tasks are read from the task.txt file and displayed in the format above.
3. Once displayed, program returns to main menu.

#### View my tasks - vm
1. When inputting "vm" the user is selecting View my Tasks.

<img width="441" alt="Screenshot 2023-05-12 at 11 33 10" src="https://github.com/stephaniecrocker91/finalCapstone/assets/90976092/f6cc0afe-43db-4c11-8778-987c15c05580">

2. The tasks are read and filtered from the task.txt file and displayed in the format above.

#### View my tasks - vm
1. When inputting "vm" the user is selecting View my Tasks.

<img width="441" alt="Screenshot 2023-05-12 at 11 33 10" src="https://github.com/stephaniecrocker91/finalCapstone/assets/90976092/f6cc0afe-43db-4c11-8778-987c15c05580">

2. The tasks are read and filtered from the task.txt file and displayed in the format above.

3. Message displayed below requesting user input: go back to menu (-1) or select a task to edit/mark as completed (task number)

If input number is invalid, appropriate error message is displayed and input request is made again.

<img width="441" alt="Screenshot 2023-05-12 at 11 37 19" src="https://github.com/stephaniecrocker91/finalCapstone/assets/90976092/4d671cd9-b594-46ee-8568-660826d40ad7">

4. Once user inputs task number, the program requests user to select: edit task, mark as completed or go back to menu

<img width="441" alt="Screenshot 2023-05-12 at 11 37 48" src="https://github.com/stephaniecrocker91/finalCapstone/assets/90976092/fcbca1f5-7db0-4183-90fc-10e352c08df6">

If user requests to edit a completed task, or mark as completed a completed task, or enters an invalid input => appropriate error message is displayed, and input request is repeated.

<img width="441" alt="Screenshot 2023-05-12 at 11 40 20" src="https://github.com/stephaniecrocker91/finalCapstone/assets/90976092/9f13c072-2fb7-4b7b-ba8f-6aa318c2b4fd">

##### Complete task - c
5. If user selects to complete task (c), the value for completed is changed to True, and these details are written and saved to the task.txt file

##### Edit task - e
6. If user selects to edit task (e), the following options are displayed:

<img width="441" alt="Screenshot 2023-05-12 at 11 42 31" src="https://github.com/stephaniecrocker91/finalCapstone/assets/90976092/ce0390bb-a794-4372-afee-d8b0623c2c9a">

7. User can select to edit the username assigned to task or the due date. Upon selection, the new value of user/due date are saved to the task.txt

Appropriate error messages appear if the user does not exist, the date format is incorrect, or the input is invalid.

8. Once completed, program returns to main menu.

#### Generate reports - gr
1. When inputting "gr" the user is selecting Generate Reports.

<img width="441" alt="Screenshot 2023-05-12 at 11 47 23" src="https://github.com/stephaniecrocker91/finalCapstone/assets/90976092/193ca4f6-2857-4c4a-a3b6-956912bdca56">

Reports are generated and confirmation message is displayed.

2. The program reads data from user.txt file and task.txt file, performs calculations with this data, and writes them into a user_overview.txt and task_overview.txt

##### task_overview.txt file

<img width="466" alt="Screenshot 2023-05-12 at 11 49 26" src="https://github.com/stephaniecrocker91/finalCapstone/assets/90976092/d1329fa3-f1d3-42c4-b935-95cc628af6c5">

##### user_overview.txt file

<img width="581" alt="Screenshot 2023-05-12 at 11 52 17" src="https://github.com/stephaniecrocker91/finalCapstone/assets/90976092/de50b23b-e34e-4d7e-b78d-d7ca5da44247">

3. Once finished, the program returns to main menu.

#### Display Statistics - ds
1. When inputting "ds" the user is selecting Display Statistics. These are the generated reports (as in menu selection "gr")
2. If these reports have not been generated yet (for example: this is the first time you run the program locally), the program will generate the reports first.
3. The program reads files user_overview.txt and task_overview.txt and displays it on our console.

<img width="581" alt="Screenshot 2023-05-12 at 11 55 57" src="https://github.com/stephaniecrocker91/finalCapstone/assets/90976092/7c738468-8bb8-4af2-909b-3a65ba87bc91">
4. Once displayed, program returns to main menu.

#### Exit program - e
1. When inputting "e" the user is selecting Exit Program. Confirmation message is displayed, and program ends.


<img width="581" alt="Screenshot 2023-05-12 at 11 57 13" src="https://github.com/stephaniecrocker91/finalCapstone/assets/90976092/1bbd72ad-33dc-48fd-b05e-42b177476f57">

* * * 

## CREDITS:
------------------

* * * 

This program was created as part of a capstone project with the Hyperion Dev Software Engineering bootcamp, so the concept is theirs. The orginal code was created by them. This included the intial creation of admin user, initial sample task, and a template main menu with no functionality. All functionality was then created by myself.


