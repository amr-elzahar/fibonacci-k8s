# Fibonacci Sequence

An application that calculates the value corresponding to a specific index in fibonacci series.

# Description

This is a full-stack application that consists of a React client, a Node.js server, a Postgres DB container. The application allows users to input an index value for the Fibonacci series and receives back the corresponding value from either Redis. The init.sql file is a script that will run when the postgres container starts to create the database and the table.

# Installation

To install and run this application, you need to have minikube and kubectl installed on your local machine. Once you have them installed, you can proceed with the following steps:

1. Clone this repository to your local machine.

```
git clone https://github.com/amr-elzahar/fibonacci-sequence.git
```

2. Navigate to the root directory of the project and open the terminal:

```
cd fibonacci-k8s/
```

3. Run the command to create deployment files:

```
kubectl create -f deployment/
```

4. Run this command to access the application through your browser:

```
minikube service client
```

# Usage

Once you run the last command, the application will open automatically in you local browser. Now you can enter any index value in the text field and click on the "Calculate" button. After clicking on the "Calculate" button, you will see the corresponding value of the index in the Fibonacci series.
