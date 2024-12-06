# PrioritizeMe-Code-Directory

# Description:

PrioritizeMe is an application developed to guide and help students in managing their time and tasks more effectively. As we found its a recurring problem that student cant manage their time efficiently, we developed this application to help them optimize their productivity.  Our app has two main functions:

1- Allow students to categorize their tasks and prioritize them based on importance. 

2- help students manage their time efficiently using advanced features like distraction blockers, called “Focus Mode” and priority queues

With PrioritizeMe, students can stay organized, meet deadlines, and achieve their goals.

# Installation and Execution:

In order to use the PrioritizeMe, clone the repository to your local machine. Since the application only relies on standard Python libraries, only this installation is needed one time in python. Navigate to the project directory and execute the AppCode file to run the application. The program’s functionality is interactive, making sure it allows users to insert and view tasks, manage their urgent priorities, look for tasks, put the tasks as complete, and start distraction-blocking sessions through the terminal commands.

# Features:

The application includes different features:

Firstly, it categorizes tasks into Exam, Project, Homework, and Extracurricular. Tasks are ranked and shown  based on its priority. Urgent tasks are highlighted using a priority queue, allowing users to focus on this kind of tasks first. 

When a task is finished it can also be marked as completed, removing it from active lists, where only tasks to be done are shown. 

Afterwards, the application suggests the next most critical and urgent task to work on using a custom scoring algorithm. Also distraction-free mode can be enabled to help users focus on one task for a set period.

# Usage:                                                                                           
When a student enters the app, the first thing they can see is a list of actions to choose from:                   

1- Task: This feature allows students to create a new task to add it to their schedule.                                              
    Input: The user provides details about the task: Task name, due date, category , and status.      
    Output: The task is added to the schedule depending on their priority and with an estimated time. A confirmation message is displayed.  

2- View All Tasks: This option allows users to view their schedule with their tasks as well as their details.                             
    Output: The app show the tasks ordered by priority and other characteristics like category and deadline.
    
3- Suggesting the Next Task: The application will recommend the user which tasks they should focus on based on the weighted priority of the task and its status.        Output: A suggested task is displayed by the app. If there are no tasks to do, a message will be visible.                                                     

4- Work Session: When the user chooses a task, they can activate a distraction-free environment using the DistractionBlocker feature.                                   Input: The task title and the estimated duration of the session.                                                                                        
     Output: A timer for the session, and distraction-blocking mode will be activated.

5- Exiting the Program: When the user wants to end the session and exit the app.                                                                               


Key Functionalities of the code:                                                                                                                                       
- Task Prioritization: The application assigns priority levels based on the task category, status, and time until the deadline. 

- DistractionBlocker: The app has a focus mode that works by blocking all distractions for a specific time.

- Task Search and Suggestions: It suggests tasks based on priority, and allows the users to search for specific tasks. 

# Further Improvements:

The application has a massive range for improvement:

- Developing a graphical user interface (GUI) will make the app more visual and user-friendly, improving customer service.

- Development of notification and pop up reminders will also help the students be more up to date with the schedules.
  
- Saving tasks and schedules in a database would ensure that the data is constant.

# Credits:

This project was created for the Algorithms and Data Structures course at IE University. It was developed by:

- Cristian Reboredo
- Miguel Romero
- Nicolas Pestaña
- Jaime Longo
- Pablo Gómez
