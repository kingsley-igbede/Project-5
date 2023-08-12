# Project-5: Implementation Of A Client Server Architecture Using  MYSQL Database Management Syetem (DBMS).

*To demonstrate a basic client-server using MySQL Relational Database Management System (RDBMS), follow the below instructions^

## Step 1:

Create and configure two Linux-based virtual servers (EC2 instances in AWS).

1. Server A Name: Project5-server
2. Server B Name: Project5-client

## Step 2:

On Project5-server Linux Server install MySQL Server software

## Step 3:

On Project5-client Linux Server install MySQL Client software.

## Step 4:

Since by default, both of my EC2 virtual servers are located in the same local virtual network, so they can communicate to each other using local IP addresses. 

Use mysql server's local IP address to connect from mysql client. 

MySQL server uses TCP port 3306 by default, so to open it, create a new entry in ‘Inbound rules’ in ‘Project5-server’ Security Groups. 

NOTE: For extra security, i did not allow all IP addresses to reach the ‘Project5-server’ – allowed access only to the specific local IP address of your ‘Project5-client’.

## Step 5:

Configured Project5-server to allow connections from remote hosts.

## Step 6:

From Project5-client Linux Server connect remotely to Project5-server Database Engine without using SSH. 

I used the mysql utility to perform this action.

## Step 7:

Checked that i have successfully connected to a remote Project5-server and can perform SQL queries

