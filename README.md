# Logging Microservice for Project Photon 

- This microservice is a part of the **Project Photon** that is our attempt at making something similar to Google Photos using MERN stack and Microservices Architecture.
- This Logging service communicates directly with the Photo Storage service and everytime an Image is uploaded or deleted it creates a log and stores it in MongoDB.
- The logs created by the logging service are then used by the Frontend to display all the logs for a user. 
