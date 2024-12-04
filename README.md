# Application Setup and Running Guide

This README provides instructions on how to set up and run the application locally using Docker and Docker Compose.

## Prerequisites

Before you begin, ensure you have the following installed on your local machine:

- [Docker](https://www.docker.com/get-started)
- [Docker Compose](https://docs.docker.com/compose/install/)
- A terminal (e.g., Terminal on macOS/Linux, Command Prompt/PowerShell on Windows)

## Steps to Run the Application

Follow these steps to run the application locally:

### 1. Clone the Project Repository

First, clone the project repository to your local machine:

```bash
git clone https://github.com/iamhuutho/dokuwiki-demo.git
cd dokuwiki
```
### 2. Navigate to the Project Directory
Once you are in the project directory, run the following command to start the application:
```bash
docker-compose up
```
### 3. Access the Application
Once the application is up and running, open your web browser and go to the following URL to access the application:
```bash
http://localhost:8081
```
### 4. Stopping the Application
To stop the application and remove the running containers, use the following command:
```bash
docker-compose down
```