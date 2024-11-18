# Overview

This repository contains a Python application designed to manage student, course, and grade data with a user-friendly graphical interface. The program supports key functionalities such as adding students, assigning courses, recording marks, calculating GPAs, and ranking students based on their academic performance. It leverages modular design principles and multithreading for efficient data handling and persistence.
# Key Features

- Data Management: Handles students, courses, and marks using dedicated domain objects.
- User Interaction: Includes a curses-based text input system and a GUI application for ease of use.
- Functionality:
    - Add and manage students, courses, and marks.
    - View detailed marks and GPA calculations.
    - Rank students based on GPA.
- Data Persistence: Uses threading for background import/export of data with file compression to ensure data integrity and efficiency.

# How It Works

The application:
1. Imports student, course, and mark data using a multithreaded background process.
2. Provides a graphical interface (Application) for interacting with the data.
3. Allows users to manage and query data with several utility functions.
4. Exports the updated data in a compressed format for future use.

This project demonstrates the integration of object-oriented programming, GUI design, and multithreading in Python, making it suitable for educational and small-scale management use cases.
