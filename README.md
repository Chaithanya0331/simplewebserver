# EX01 Developing a Simple Webserver
## Date:22/08/2025

## AIM:
To develop a simple webserver to serve html pages and display the list of protocols in TCP/IP Protocol Suite.

## DESIGN STEPS:
### Step 1: 
HTML content creation.

### Step 2:
Design of webserver workflow.

### Step 3:
Implementation using Python code.

### Step 4:
Import the necessary modules.

### Step 5:
Define a custom request handler.

### Step 6:
Start an HTTP server on a specific port.

### Step 7:
Run the Python script to serve web pages.

### Step 8:
Serve the HTML pages.

### Step 9:
Start the server script and check for errors.

### Step 10:
Open a browser and navigate to http://127.0.0.1:8000 (or the assigned port).

## PROGRAM:
'''
from http.server import HTTPServer, BaseHTTPRequestHandler
content = """
<!DOCTYPE html>
<html>
	<head>
		<title>REVENUE TABLE</title>
	</head>
	<body bgcolor="cyan">
	<h1>TOP FIVE REVENUE GENERATING SOFTWARE COMPANIES</h1>
	<table border='3' cellspacing="4" cellpadding='3'>
		<tr>
			<th>RANK</th>
			<th>ORGANIZATION</th>
			<th>FY</th>
			<th>REVENUE</th>
		</tr>
		<tr>
			<td>1</td>
			<td>MICROSOFT</td>
			<td>2022</td>
			<td>$203.08 billion</td>
		</tr>

		<tr>
			<td>2</td>
			<td>GOOGLE</td>
			<td>2022</td>
			<td>$173.02 billion</td>
		</tr>

		<tr>
			<td>3</td>
			<td>IBM</td>
			<td>2019</td>
			<td>$123.58 billion</td>
		</tr>
		<tr>
			<td>4</td>
			<td>ORACLE</td>
			<td>2019</td>
			<td> $46.07 billion</td>
		</tr>
		<tr>
			<td>5</td>
			<td>SAP</td>
			<td>2019</td>
			<td>$32.97 billion</td>
		</tr>
	</table>
	</body>
</html>
'''

## OUTPUT:
<img width="1919" height="1199" alt="Screenshot 2025-08-22 134306" src="https://github.com/user-attachments/assets/0ae3db34-ac52-4756-82aa-8173d2a841f6" />

<img width="1919" height="1199" alt="Screenshot 2025-08-22 134325" src="https://github.com/user-attachments/assets/051202df-0298-443f-89eb-acb4b011a56a" />

## RESULT:
The program for implementing simple webserver is executed successfully.
