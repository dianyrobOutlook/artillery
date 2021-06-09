# Project Performance with Artillery by Diana Hernandez
## Workshop project session: Performance
### Steps to run tests:
#### 1.Clone this repository
#### 2.Open the terminal and go to the project's folder performance
#### 3.Once you are in the folder performance, from the terminal execute the next commands to install the required libraries: 
*    npm init -y
*    npm install --save-dev artillery
#### 4.To execute each test and see the result, from the terminal run the next commands:
*    artillery run create_task.yml
*    artillery run delete_task.yml
*    artillery run update_task.yml
*    artillery run get_active_tasks.yml
*    artillery run get_an_active_task.yml
*    artillery run complete_task.yml
*    artillery run reopen_task.yml
