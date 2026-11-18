# Personal Task manager

![Static Badge](https://img.shields.io/badge/python-blue?logo=python&logoColor=white)
  
A simple task manager built with Python

## Features
- Add multiple tasks
- save tasks
- load aved tasks
- Admin mode
- set task priority

## Task priority
each task can have one of these priority levels:
- low
- medium
- high

## Requirements
- python
- python-dotenv

## Project Structure

```text
personal_task_manager/
│   .env.example
│   .gitignore
│   main.py
│   README.md
│   requirements.txt
│
├───Images
│       Screenshot1.png
```

## Installation
Install the required packages

```bash
python -m pip install -r reqirements.txt
```

## Environment Setup
Create an `.env` file in the project folder

Use `.env.example` as a template

Add your admin password
```env
admin_pass=your_password_here
```
Replace `your_password_here` with your admin password

## Run the Programe
Run the main file
```bash
python main.py
```



## Screenshot
![Screenshot](Images\Screenshot.png)