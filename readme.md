# Laravel Skill Test
This is an example application developed for an interview process

## Description
Create a very simple Laravel web application for task management: -Create task (info to save: task name, priority, timestamps) -Edit task -Delete task -Reorder tasks with drag and drop in the browser. Priority should automatically be updated based on this. #1 priority goes at top, #2 next down and so on. -Tasks should be saved to a mysql table.

BONUS POINT: add project functionality to the tasks. User should be able to select a project from a dropdown and only view tasks associated with that project.

You will be graded on how well-written & readable your code is, if it works, and if you did it the Laravel way.

## Installation
step1 create a database on mysql server `tasks_mgr` then run 
```sh
 php artisan migrate

```
if above command is not running well then run step1 command

```sh
composer update
```
step2 then generate vertual host
```sh
 php artisan server

```
on the root of the project

### If you don't have composer
You can download it [here](https://getcomposer.org/download/).
