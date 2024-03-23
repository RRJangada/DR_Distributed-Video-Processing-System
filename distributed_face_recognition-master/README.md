# Distributed Face Recognition System
______________
***Installation Instructions:***

**Front End Setup:**
1.	Install Required Node Packages:
Navigate to the *Front_End* folder and execute the following command:
	```npm install```
2.	Start React App:
Move to the *Front_End/React* directory and initiate the React app with:
	```npm start```
3.	Start Node.js Server:
In another terminal, navigate to the nodeJs folder and commence the server:
	```node server.js```
4.	Environment Configuration:
Ensure there is a *.env* file with the necessary configurations, particularly the path to the shared folder.

**Face Detection System Setup:**
1.	Install Required Libraries:
Navigate to the Face_Detection_System folder and install the required libraries using:
	```pip install -r requirements.txt```
2.	Start Producer (Master Node):
Run the producer script with Python 3:
	``` python3 producer.py ```
3.	Start Consumers (Worker Nodes):
Open two separate terminals and execute the following commands in each:
	``` python3 consumer1.py ``` & ``` python3 consumer2.py ```
4.	Environment Configuration:
Ensure there exists a *.env* file containing the username, password for the PostgreSQL database, and the path to the shared folder.

Docker Containerization:

•	For Docker container creation, refer to the *dockerfiles* folder located inside the *Face_Detection_System* directory.
______________
