OSSEE Workshop Booking — UI/UX Enhancement
Project: FOSSEE Python Screening Task 1 — UI/UX Enhancement
Author: Anshika Shukla — 11AN-CODE

Overview
This repository contains my submission for the FOSSEE Python Screening Task 1, focused on enhancing the UI/UX of the workshop booking website. The changes were made to the existing Django templates and static files to improve the user experience, particularly for mobile devices, while maintaining the core functionality.

The main page for the project (after running the server) is located at:
http://127.0.0.1:8000/workshop/login

Demo / Preview
<img width="1253" height="614" alt="image" src="https://github.com/user-attachments/assets/da742f71-e98c-4438-9c00-d2962793ffba" />


Guide to Install and Run the Website
Follow these steps to get the website running on your local machine.

NOTE: Use Python 3.

Clone the repository:

Bash

git clone https://github.com/FOSSEE/workshop_booking.git
cd workshop_booking
Create a virtual environment and install dependencies:

Bash

python3 -m venv venv
source venv/bin/activate    # On Linux / macOS
# For Windows, use: venv\Scripts\Activate.ps1
pip install -r requirements.txt
Make migrations and migrate:

Bash

python manage.py makemigrations
python manage.py migrate
Create a superuser:

Bash

python manage.py createsuperuser
Start the development server:

Bash

python manage.py runserver
Admin page: You can access the admin panel at http://127.0.0.1:8000/admin and log in with your superuser credentials.

High-Level Changes
[Briefly describe your main UI/UX changes here, e.g., "Implemented a mobile-first responsive layout."].

[Describe a specific improvement, e.g., "Redesigned the workshop list table for better readability on small screens."].

[Mention another key change, e.g., "Improved form element styling to be more user-friendly on touch devices."].

[Add any other major changes you made.]

Design Reasoning
This section provides the answers to the questions from the task brief, detailing my thought process.

1. What design principles guided your improvements?

[Answer here, e.g., "Mobile-first design" - I designed the smallest screen widths first, ensuring usability and readability before scaling up for larger screens.]

[Answer here, e.g., "Clarity and Simplicity" - I focused on a clean, uncluttered layout with clear visual hierarchy to help users find information and perform actions quickly.]

[Answer here, e.g., "Accessibility" - I used high-contrast colors, legible font sizes, and ensured all interactive elements are easily tappable or clickable.]

2. How did you ensure responsiveness across devices?

[Answer here, e.g., "I used a combination of CSS Flexbox and Grid to create a flexible layout that naturally adapts to different screen sizes.]

[Answer here, e.g., "I used relative units like rem and percentages (%) for fonts and element sizes, allowing them to scale proportionally."]

[Answer here, e.g., "I implemented media queries to apply specific styling rules at different breakpoints, such as transforming the data table into a more readable card-based layout on mobile."]

3. What trade-offs did you make between design and performance?

[Answer here, e.g., "I chose to use custom, lightweight CSS instead of a heavy UI framework to minimize the file size and reduce page load times."]

[Answer here, e.g., "I avoided complex JavaScript animations or excessive visual effects that could slow down the page, especially on older mobile devices."]

[Answer here, e.g., "Instead of using multiple image assets, I relied on CSS for gradients, shadows, and icons where possible, which reduces HTTP requests."]

4. What was the most challenging part of the task and how did you approach it?

[Answer here, e.g., "The most challenging part was making the workshop list table legible and easy to navigate on a small mobile screen."]

[Answer here, e.g., "My approach was to convert the traditional table rows into a card-style layout at mobile breakpoints. Each 'card' stacks the information vertically, with clear labels, making it much easier to read and scan."]

Contact
Repository owner: https://github.com/11AN-CODE

Instructions for you:

Replace all bracketed placeholders like [Your Name] and [YourGitHubUsername] with your actual information.


