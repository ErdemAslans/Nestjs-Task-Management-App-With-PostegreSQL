# NestJS Task Management App with PostgreSQL

This is a **Task Management Application** built with **NestJS** and uses **PostgreSQL** as the database. The application allows users to create, read, update, and delete tasks. Each task has a title, description, and status, which can be either `OPEN`, `IN_PROGRESS`, or `DONE`. 

The application demonstrates how to build a simple CRUD (Create, Read, Update, Delete) API using NestJS and TypeORM, with PostgreSQL as the database.

## Features

- **Create a Task**: Users can create a new task with a title, description, and initial status.
- **Get All Tasks**: Retrieve all tasks stored in the database.
- **Get Task by ID**: Retrieve a specific task by its ID.
- **Update Task Status**: Update the status of a task (from `OPEN` to `IN_PROGRESS` or `DONE`).
- **Delete a Task**: Remove a task from the database by its ID.
- **Data Validation**: DTOs (Data Transfer Objects) are used for input validation.
- **Error Handling**: Returns appropriate HTTP status codes and error messages.

## Technologies Used

- **NestJS**: A progressive Node.js framework for building efficient and scalable server-side applications.
- **TypeORM**: An ORM for TypeScript and JavaScript that works with many databases including PostgreSQL.
- **PostgreSQL**: A powerful, open-source object-relational database system.

## Prerequisites

Make sure you have the following installed:

- **Node.js**: v14 or higher
- **NestJS CLI**: Install globally with `npm install -g @nestjs/cli`
- **PostgreSQL**: Make sure PostgreSQL is installed and running on your machine

