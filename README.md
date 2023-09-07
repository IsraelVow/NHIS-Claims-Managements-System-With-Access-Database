
# NHIS Claims Management System with Excel and Access Database

## Table of Contents
1. [About](#about)
2. [Features](#features)
3. [System Design](#system-design)
4. [Getting Started](#getting-started)
   - [Prerequisites](#prerequisites)
   - [Installation](#installation)
   - [Database Connection](#database-connection)
   - [User Credentials](#user-credentials)
   - [Making Adjustments](#making-adjustments)
5. [Contributing](#contributing)
6. [License](#license)

## About
The NHIS Claims Management System is a comprehensive solution designed to streamline claims processing and management for healthcare providers, specifically tailored for Almadina Clinic. This project was initiated to address the challenges faced by Almadina Clinic in tracking claims, ensuring data accuracy, and meeting submission deadlines. It serves as an efficient tool for NHIS officers to manage and process claims seamlessly.

## Features
- **Dynamic Claim Forms**: The system generates HMO-specific claim forms, automating data entry and ensuring accuracy.
- **Database Integration**: Claims data is stored in an Access database, allowing for easy retrieval, analysis, and management.
- **User Permissions**: Admins can control user access to various features, enhancing data security.
- **Real-time Analytics**: Interactive charts provide insights into claim statistics, helping users make informed decisions.
- **Document Management**: Users can access and manage essential documents directly within the application.
- **Data Export**: Generate reports and export data to Excel or PDF formats.
- **Web Portal Integration**: Seamless integration with HMO web portals streamlines claim submission.

## System Design
The system features a user-friendly interface with multiple tabs, including Dashboard, Claims, Tariff, Documents, Analysis & Report, and Settings. Users can switch between public and private HMOs, create pending claims, search HMOs, and adjust tariff rates. The Dashboard displays key analytics and allows users to send claims via email.

![Dashboard Screenshot](/images/dashboard.png)

## Getting Started
### Prerequisites
- Microsoft Excel
- Access Database Engine (if not already installed)

### Installation
1. Clone this repository to your local directory:
   ```bash
   git clone https://github.com/IsraelVow/NHIS-Claims-Managements-System-With-Access-Database.git
   ```

### Database Connection
To ensure the project works correctly, you need to adjust the database connection string. Here's how:

1. Open the workbook in the VBE editor.
2. Navigate to the "ThisWorkbook" object on the left in the Object Explorer.
3. Locate the `Workbook_Open()` event.
4. Uncomment all the code in this event to allow the system to request user credentials when the workbook is opened.


### User Credentials
The login page provides access to the system for existing users and also allows you to register a new user. It consists of two pages within a multipage control:
1. **Login Page**: Use this page to log in to the system with your existing credentials.
2. **Create Account Page**: If you're a new user, you can create a new account from this page.

To create a new account, follow these steps:
1. Click the "Create Account" button located at the bottom left of the login page.
2. A textbox will pop up, requesting the admin password. Enter "admin1234" (case sensitive).
3. Once the admin password is accepted, it will open a registration form for creating a new account.

![Create Account Page](https://i.imgur.com/tX2dCvB.png)
![Create Account Page](https://imgur.com/vJuwITE.png)


For the initial login, you can use the following admin credentials:
- **Username:** `Admin`
- **Password:** `admin1234` (case sensitive)

![Login Page](https://imgur.com/7fyBQWN.png)


### Making Adjustments
Contributors may need to adjust various aspects of the project to suit their environment or requirements. To do so:

1. Modify the database connection string in the code to match your system's directory path.

## Contributing
Contributions to this project are welcome! If you'd like to contribute, please follow these steps:
1. Fork the project.
2. Create a new branch for your feature: `git checkout -b feature-name`
3. Make your changes and commit them: `git commit -m 'Add some feature'`
4. Push to your branch: `git push origin feature-name`
5. Create a pull request.

Please adhere to the project's coding guidelines and maintain a clean commit history.

## License
This project is licensed under the [MIT License](LICENSE).
```
