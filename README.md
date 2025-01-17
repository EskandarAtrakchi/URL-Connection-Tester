# HTTP HEAD Checker

A simple Java application that sends an HTTP HEAD request to a specified web server URL and displays the server's response. If no URL is specified, the application defaults to `http://nginx.org/`.
https://eskandar-atrakchi.gitbook.io/socket-ca3-advance-networking-year-3 

## Features
- Sends an HTTP HEAD request to check the status of a URL.
- Alerts the user when the URL format is invalid.
- Handles connection timeouts gracefully.
- Allows users to input a URL via a GUI (JOptionPane).
- Defaults to `http://nginx.org/` if no URL is provided.

## Prerequisites
- Java Development Kit (JDK) 8 or higher.
- An IDE or terminal to compile and run the program.

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/HTTP-HEAD-Checker.git
   cd HTTP-HEAD-Checker
   ```
2. Compile the application:
   ```bash
   javac HeadRequestApp.java
   ```

## Example Usage

### Case 1: User enters a valid URL
    Input: http://httpforever.com/
    Output:
    Connected to: http://httpforever.com/
    Response Code: 200
    Response Message: OK

### Case 2: User leaves input blank
    Input: (blank)
    Output:
    Connected to: http://nginx.org/
    Response Code: 200
    Response Message: OK

### Case 3: User enters an invalid URL
    Input: invalid-url
    Output:
    Error: Invalid URL: invalid-url

## Technologies Used
#### Java
#### JOptionPane for graphical dialogs
#### HttpURLConnection for HTTP requests

## Screenshots

### Default URL: `http://nginx.org/`

| Step | Screenshot |
|------|------------|
| **Step 1: Empty Input** | ![Empty Input Screenshot](https://github.com/EskandarAtrakchi/HTTP-HEAD-Checker/blob/main/Screenshots/Empty%20input.png?raw=true) |
| **Step 2: Confirmation of Default URL** | ![Default URL Confirmation Screenshot](https://github.com/EskandarAtrakchi/HTTP-HEAD-Checker/blob/main/Screenshots/Empty%20input%20confirmation.png?raw=true) |
| **Step 3: Response from Default URL** | ![Default URL Response Screenshot](https://github.com/EskandarAtrakchi/HTTP-HEAD-Checker/blob/main/Screenshots/default%20response.png?raw=true) |

---

### Input URL: `https://www.google.com/`

| Step | Screenshot |
|------|------------|
| **Step 1: User Input** | ![Google Input Screenshot](https://github.com/EskandarAtrakchi/HTTP-HEAD-Checker/blob/main/Screenshots/Google%20input.png?raw=true) |
| **Step 2: Confirmation of User Input** | ![Google Input Confirmation Screenshot](https://github.com/EskandarAtrakchi/HTTP-HEAD-Checker/blob/main/Screenshots/Google%20input%20confirmation.png?raw=true) |
| **Step 3: Response from `https://www.google.com/`** | ![Google Response Screenshot](https://github.com/EskandarAtrakchi/HTTP-HEAD-Checker/blob/main/Screenshots/Google%20response.png?raw=true) |



Made with ❤️ by Eskandar Atrakchi.
