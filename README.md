# Software Documentation

## Introduction

This document serves as the software documentation for the implemented feature in assignments 4 and 5. It outlines the purpose of the document, the scope of the software, the software architecture, design, models, test cases, and the tools, languages, frameworks, and platforms used in the development process.

## Scope of the Software

The software aims to assist users in creating and following 
personalized workout plans. The application provides a user-friendly interface for logging 
in, creating workout routines, and accessing predefined workout plans for various fitness 
goals. Users can navigate between different workout plans, including Strength Training, 
Cardio, and Yoga, to meet their specific fitness objectives.

## Used Software Architecture

The software architecture follows a modular and layered approach, ensuring scalability, maintainability, and flexibility. It contains multiple layers such as presentation layer, business logic layer, and data access layer, facilitating separation of concerns and enabling easier maintenance and updates.

## Software Design and Model

The software design is represented using UML diagrams, including class diagrams, sequence diagrams These diagrams illustrate the structure, behavior, and interactions within the system.

- **Class Diagram:** ![Class Diagram](https://github.com/NatyLegesse/HEALTH-AND-FITNESS-TRACKER/blob/main/Screenshot%202024-02-10%20204440.png)
- **Sequence Diagram:** ![Sequence Diagram](https://github.com/NatyLegesse/HEALTH-AND-FITNESS-TRACKER/blob/main/Screenshot%202024-02-10%20204539.png)


## Test Cases

Test cases have been devised to ensure the functionality, reliability, and performance of the implemented feature. These test cases cover various scenarios and edge cases to validate the behavior of the system.

- **Test Case 1:** Verify that clicking the "Login" button with valid credentials successfully logs the user in and displays the workout planner interface.
  - **Steps:**
    1. Enter valid username and password.
    2. Click the "Login" button.
  - **Expected Result:** The user should be logged in, and the workout planner interface should be displayed.

- **Test Case 2:** Verify that clicking the "Login" button with invalid credentials displays an error message.
  - **Steps:**
    1. Enter invalid username or password.
    2. Click the "Login" button.
  - **Expected Result:** An error message should be displayed indicating invalid credentials.

- **Test Case 3:** Verify that clicking the "Logout" button successfully logs the user out and displays the login form.
  - **Steps:**
    1. Ensure the user is logged in.
    2. Click the "Logout" button.
  - **Expected Result:** The user should be logged out, and the login form should be displayed.

- **Test Case 4:** Verify that clicking on the "Strength Training" button redirects the user to the strength training plan website.
  - **Steps:**
    1. Ensure the user is logged in.
    2. Click the "Strength Training" button.
  - **Expected Result:** The user should be redirected to the strength training plan website in a new tab.

- **Test Case 5:** Verify that clicking on the "Cardio" button redirects the user to the cardio plan website.
  - **Steps:**
    1. Ensure the user is logged in.
    2. Click the "Cardio" button.
  - **Expected Result:** The user should be redirected to the cardio plan website in a new tab.

- **Test Case 6:** Verify that clicking on the "Yoga" button redirects the user to the yoga plan website.
  - **Steps:**
    1. Ensure the user is logged in.
    2. Click the "Yoga" button.
  - **Expected Result:** The user should be redirected to the yoga plan website in a new tab.

## Used Tools, Languages, Frameworks, Platforms, etc.

- Programming Language: [Specify language(s) used]
- Frameworks: [Specify frameworks used]
- Version Control: Git
- IDE: [Specify IDE used]
- Testing Framework: [Specify testing framework used]
- Deployment Platform: [Specify deployment platform]

## Markdown Usage

The documentation is written using markdown, adhering to the syntax compatible with Git repository. The following markdown elements have been utilized:

- Headings
- Styling
- Text quotes
- Code quotes
- Colors
- Links
- Images
- Lists
- Footnotes
- Alerts

## Conclusion

This documentation provides a comprehensive overview of the implemented feature, including its scope, architecture, design, test cases, and the technologies used in its development. It serves as a reference for understanding the functionality and structure of the software.

## Screenshots

- **Screenshot 1:** ![Screenshot](link_to_image)
- **Screenshot 2:** ![Screenshot](link_to_image)
- **Screenshot 3:** ![Screenshot](link_to_image)

Ensure to review the rendered documentation in the repository to confirm proper rendering of markdown files.

[Commit Link to Repository](link_to_repository)
