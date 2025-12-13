# Task Bot for Zoho Cliq

A lightweight task management bot built for Zoho Cliq that helps teams create, track, and manage tasks directly from their chat interface.

## What is Task Bot?

Task Bot is a simple yet powerful task manager that lives inside Zoho Cliq. Instead of switching between multiple apps, your team can create tasks, check their status, and mark them complete without leaving their conversations. Every task gets a unique ID, making it easy to reference and manage.

## How It Works

The bot uses slash commands that you type directly in any Zoho Cliq chat. When you create a task with `/addtask`, it's automatically assigned a unique ID and stored in a database. You can view all tasks with `/listtasks`, mark them complete with `/completetask`, or delete them with `/deletetask`. All tasks are visible to everyone in your organization, making it perfect for team collaboration.

## Key Features

- **Quick Task Creation**: Add tasks instantly with a simple command
- **Task Tracking**: View all tasks, filter by status, or see only your tasks
- **Search & Filter**: Find tasks by keyword or view pending/completed tasks separately
- **Task Details**: Add descriptions, edit titles, and view full task information
- **Team Collaboration**: Everyone in your organization can see and manage tasks
- **Statistics**: Get insights on task completion rates and team productivity

## Common Commands

- `/addtask [task name]` - Create a new task
- `/listtasks` - See all tasks
- `/completetask [task ID]` - Mark a task as done
- `/deletetask [task ID]` - Remove a task
- `/mytasks` - View only your tasks
- `/searchtasks [keyword]` - Search for specific tasks



---

Built with Zoho Cliq and Zoho Creator.
