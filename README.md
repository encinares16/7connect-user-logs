# 7connect User Logs

This guide will walk you through the steps to clone a repository, install dependencies, and run the application.

## Prerequisites

- **Node.js** (version 14 or later recommended)
- **Git**


# Steps

**1. Run Git Bash**

   Open any folder, right-click, select **Open Git Bash Here** and type the following command on the terminal.

Create a directory
   
```cmd
mkdir application
```

  Go to application directory

```cmd
cd application
```

**2. Clone the project and install dependencies**

   To clone the project, and install dependencies, type the following commands

```bash
git clone https://github.com/encinares16/7connect-user-logs.git 
```

```bash
cd 7connect-user-logs
```

Installing dependencies

```bash
npm install
```

**3. Run the application**

1. Extract specific LOG file (e.g. 7pay.log_2024-01-01.log) and move inside project directory.

Run the application, type

```bash
node app.js
```

Then input, 
```cmd
Enter 7pay.logs date, (month "01-12"): 01
Enter 7pay.logs date, (day "01-31"): 01
```
![add references](guide/guide.png)


