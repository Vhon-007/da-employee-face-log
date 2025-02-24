# da-employee-face-log
FACIAL RECOGNITION TIME LOG SYSTEM 
# Facial Recognition Time Log System (DA)

## Overview

This system leverages facial recognition technology to accurately and efficiently track employee time and attendance for the Department of Agriculture. It integrates with a camera system or webcam to capture images, processes these images to identify individuals, and logs their clock-in/clock-out times.

## Features

* **Facial Recognition:**
    * Processes camera images.
    * Identifies faces and matches them against an employee database.
    * Returns employee IDs for recognized individuals.
    * Indicates if a face is unrecognized.
* **Time Logging Module:**
    * Records employee clock-in and clock-out times.
    * Provides a user-friendly interface for viewing time logs.
* **Database Management:**
    * Stores employee information (names, IDs, etc.).
    * Stores facial recognition data (face embeddings).
    * Stores employee time logs.
* **Authentication:**
    * Secure user logins using bcrypt for password hashing.

## Technologies Used

* **FrontEnd:**
    * Python
    * PyQt (for the graphical user interface)
* **BackEnd:**
    * Python
    * MySQL (for database management)
    * DeepFace (for facial recognition)
* **Authentication:**
    * Bcrypt
