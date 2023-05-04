# day3
CREATE DATABASE todo_list;  USE todo_list;  CREATE TABLE tasks (   task_id INT AUTO_INCREMENT PRIMARY KEY,   task_name VARCHAR(255) NOT NULL,   description TEXT,   is_completed BOOLEAN NOT NULL DEFAULT 0 );

CREATE DATABASE todo_list;

USE todo_list;

CREATE TABLE tasks (
  task_id INT AUTO_INCREMENT PRIMARY KEY,
  task_name VARCHAR(255) NOT NULL,
  description TEXT,
  is_completed BOOLEAN NOT NULL DEFAULT 0
);
