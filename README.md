# Client-Server Interaction using Flask and HTTPX

## Overview
This project demonstrates the interaction between a client and a server using Flask on the server-side and HTTPX for making HTTP requests from the client-side. The server listens on port 5000, accepts login credentials for authentication, and echoes messages back to the client upon successful login.

## Steps to Run the Project

### 1. Make Port 5000 Public
To allow access to the server running on port 5000:
- Ensure that your Codespace or VM allows public access to port 5000.
- Change the visibility of port 5000 to `Public`.

### 2. Run the Server Python File
Start the server on your Codespace or local environment:
```bash
# Install required dependencies (Flask)
pip3 install Flask

# Run the server script
python3 my-server.py
```
### 3. Run the Client Python File
On your local machine, use the client script to make HTTP requests to the server:
```bash
# Run the client script
python3 my-calls.py
```
