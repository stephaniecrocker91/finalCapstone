# FINAL CAPSTONE : Task Management Program 
========================================

* * *

## ABOUT THE PROGRAM:
------------------

* * * 

This _Task Management Program_ program is a software application that allows users to create and manage tasks efficiently. Users can input task details, set deadlines, and assign tasks to individuals, and generate reports. This program helps individuals and teams stay organized, prioritize work, collaborate effectively, and ensure tasks are completed on time.



## INSTALLATION: Cloning and installing the project locally
----------------

* * *

*   Investors.
*   Home loan owners.
*   Loan and investor enthusiasts.
*   Ages 18+ 


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

## USING THE PROGRAM: Step by step guide on how to use the program
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

#### Registering a user
1. When inputting "r" the user is selecting Register a new User.
2. The program requests the username, password, and confirm password.

<img width="368" alt="Screenshot 2023-05-12 at 11 14 11" src="https://github.com/stephaniecrocker91/finalCapstone/assets/90976092/549923ec-b18b-4b60-9c5e-7a371f976dec">

If the username is already taken (already exists in our user.txt file) or the passwords do not match, an appropriate error message is displayed and the program requests the new username details again.

<img width="368" alt="Screenshot 2023-05-12 at 11 15 39" src="https://github.com/stephaniecrocker91/finalCapstone/assets/90976092/855ad53d-f471-4707-9051-3c31ad597c96">

4. Once the input is correct, the new user details are written and saved in our user.txt file.

#### Adding a task

1. When inputting "a" the user is selecting Add a new task.
2. The program requests the user assigned to task, task name, task description and task due date.

 <img width="368" alt="Screenshot 2023-05-12 at 11 20 24" src="https://github.com/stephaniecrocker91/finalCapstone/assets/90976092/489b27c0-077d-443d-b46d-8711b7ca5b33">
 
3. The writes and saves these details the task.txt file.

It automatically generate and saved the following details: assigned_date (by assigning the date.today()) and completed (boolean value with a default of False)

Appropriate error messages will be displayed if: task is assigned to a non-existant user, or the date is input in the wrong format. In this case, the program will request task details again.

<img width="368" alt="Screenshot 2023-05-12 at 11 26 57" src="https://github.com/stephaniecrocker91/finalCapstone/assets/90976092/915e1d39-5919-4b9f-bf53-701a38c20b8b">


* * * 
