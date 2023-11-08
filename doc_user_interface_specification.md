# User Management UI Specification

## Introduction
This document is to outline the design, functionality and usage of the user management screen of our application. This screen is critical for the management to see active users, and adding new ones.

## User Interface Components
User interface for this page should be divided into two main grids.

### 1. Top Grid
This part would occupy a small portion of the interface, since it will contain three components side by side. This part carries the functionality of the page.

#### 1. New User Button
- This button is to add new users and is replaced on the top left corner of the interface to naturally catch the eye of the user.
- It is named as "+ New User", the "+" symbol highlights the adding attribute of the button.

#### 2. Hide Disabled User
- It is placed next to the new user button.
- A "Hide Disabled User" checkbox allows the user to filter the users in the system.
- When it is not checked, all the users are presented below.
- When it is selected, only the enabled users are shown in the list. It is checked/selected by default.

#### 3. Save User Button
- This button saves the information given for the user to be added to the system.
- It is placed on the top right corner of the page. It is right aligned as opposed to the first two components.
- It is disabled when the input boxes are empty and enabled when the blanks are filled.

### 2. Bottom Grid
This part is also divided into two, one for the list of users and the second for registering new users.

#### 1. User Table
- This table is placed on the left side of the second grid.

##### Table Layout
- The table includes column names, "ID", "User Name", "Email", and "Enabled", respectively.
- Each column has the property of filtering with the filter icon placed next to the column labels.
- The columns are in a darker color and written with a bold font.
- The users are, by default, listed by the dates that they are saved to the system, however this listing can be changed by different sorting options in terms of increasing order of ID, or alphabetical order of names or emails.

#### 2. New User Registry
- This segment of the page is right next to the User Table, which enables the user to see if the newly registered user is added to the table on the left or not.
- This segment is also divided into two. It has two sub-parts on top of each other.
- The top part consists of a label which has a larger font than the rest of the page because it indicates the name of the part, which is "New User" for clarity.
- The bottom part is where the labels and the components for input are placed.

##### 1. Labels
- This container has 6 labels that are listed one under the other.
- These labels are "Username:", "Display Name:", "Phone:", "Email:", "User Roles:", and "Enabled:", respectively.

##### 2. Input Fields
- There are four input/text fields next to the first four labels.
- The text fields are empty by default.

##### 3. Dropdown Menu
- There is a drop-down menu for the user roles.
- The dropdown menu has a placeholder text of "Select user roles...", written in gray.
- The values for the dropdown are, "Guest", "Admin", and "SuperAdmin".

##### 4. Checkbox
- There is a checkbox for the "Enabled:" label, which is placed right next to it.
- It is not checked by default.
- If it is checked, the user is enabled, else it is disabled.

## Layout and Styling
- The page should have a clean, understandable and user-friendly design.
- The color blue can be used to both be consistent with the brand, and convey a sense of trustworthiness, competence, and reliability.
- The layout should be responsive to and compatible with varying screen sizes and devices.

## Validation and Error Handling
- Display error messages for incorrect credentials or input validation errors.

## Testing
- Thoroughly test the user management page to ensure that it functions correctly and is free of bugs.

## Localization
- Ensure that the page supports multiple languages, if applicable.

## Security
- Implement security measures to protect against common threats such as data leakage of the email and phone number of the added users.

## Version Control
- Use version control to track changes and updates to the user management page.

## Documentation
- Document any third-party libraries or APIs used in the development of this page.

## Approval
- [ ] This UI specification has been reviewed and approved.

## Revision History
| Version | Description | Author | Date     |
| ------- | ----------- | ------ | -------- |
| 1.0     | Initial draft | [Your Name] | [Date] |

## Feedback and Comments
Please provide feedback and comments for improvement. Your input is valuable in ensuring the quality and usability of the user management page.