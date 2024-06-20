## Attendance Logs System

This is a simple attendance logs system that allows users to log in and log out of a system. The system is built using Python.

## Features
- User can log in
- User can log out
- Sync attendance to ERPNEXT

## Technologies
- Python

## Setup
1. Clone the repository
2. Create a virtual environment:
    ```bash
    python -m venv venv
    ```
3. Activate the virtual environment:
    - Windows:
        ```bash
        venv\Scripts\activate
        ```
    - MacOS/Linux:
        ```bash
        source venv/bin/activate
        ```
4. Install the dependencies:
    ```bash
    pip install -r requirements.txt
    ```
5. Run the application:
    ```bash
    python gui.py
    ```
6. To deactivate the virtual environment:
    ```bash
    deactivate
    ```
7. To exit the application:
    - Press `Ctrl + C` in the terminal
    - Close the terminal
    - Click the `X` button on the GUI window
8. To sync attendance to ERPNEXT:
    - fill the necessary information on the form field
    - click the `Set Configuration` button
    - click the `Start Service` button
