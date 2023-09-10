
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
   - [Adjusting the Database Connection](#adjusting-the-database-connection)
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

![Dashboard Screenshot](https://imgur.com/mHEidJA.png)

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

![Create Account Page](https://imgur.com/vJuwITE.png)


For the initial login, you can use the following admin credentials:
- **Username:** `Admin`
- **Password:** `admin1234` (case sensitive)

![Login Page](https://imgur.com/7fyBQWN.png)

### Adding a New HMO with Custom Claims Form and Tariff

If you need to add a new HMO to the system, complete with a custom claims form and tariff, follow these steps:

1. **Provide the Custom Claims Form**: Contact the HMO and request their custom claims form. Ensure that they provide the necessary details for the form's layout, including fields, labels, and any special requirements. Typically, this form will be in Excel format.

2. **Design the Custom Claims Form**: Once you have the HMO's claims form, our development team will design it to seamlessly integrate with the NHIS Claims Management System. We'll use native VBA controls (toolbox) to create a user-friendly interface. This process includes coding each button, combobox, textbox, and other elements to enable NHIS officers to process claims efficiently.

3. **Provide Tariff Information**: In addition to the custom claims form, the HMO must provide their tariff rates. Tariffs are crucial for calculating claim amounts based on the services provided. Ensure that you have a clear understanding of how the tariff should be applied to different services.

4. **Integration with the System**: Our team will integrate the custom claims form and tariff information into the NHIS Claims Management System. This integration ensures that NHIS officers can easily select the new HMO, access the custom claims form, and utilize the specified tariff rates for accurate claim processing.

By following these steps, you can seamlessly onboard new HMOs into the system, allowing NHIS officers to process claims efficiently and accurately.

If an HMO doesn't have a custom claims form or tariff, they will adopt the provider's (Almadina Clinic) standard claims form and tariff. This flexibility ensures that claims can still be processed without delays.

For more detailed instructions and support, please refer to the [User Manual](https://github.com/IsraelVow/NHIS-Claims-Managements-System-With-Access-Database/blob/main/Documentation/User%20Manual.md) or [contact our support team](mailto:Israeljvow@gmail.com).

**Note**: The process may vary slightly based on the specific requirements of the HMO and the compatibility of their claims form with the system. It's essential to maintain clear communication with the HMO throughout the onboarding process to ensure a smooth integration.

### Making Adjustments

Contributors may need to adjust various aspects of the project to align with their specific environments or requirements. This section provides guidance on how to modify the database connection string and other settings.

#### Adjusting the Database Connection

The NHIS Claims Management System is designed to connect seamlessly with an Access database. To ensure the project works correctly on your system, you may need to adjust the database connection string. Follow these steps:

1. **Open the "NCMS - No password" XLSM File**:
   - Start by opening the "NCMS - No password" XLSM file provided in this repository. This file does not require login authentication.

2. **Uncomment the Login Code**:
   - Navigate to the Visual Basic for Applications (VBA) editor by pressing `Alt` + `F11`.
   - In the editor, find the "ThisWorkbook" object in the Object Explorer.
   - Locate the `Workbook_Open()` event.
   - Uncomment all the code within this event. This step enables the system to request user credentials when the workbook is opened.

3. **Replace the Existing Connection String**:
   - Still in the VBA editor, use the "Find and Replace" functionality by pressing `Ctrl` + `H`.
   - In the "Find what" field, enter the existing connection string, which is set to connect to the database on the login page initialization.
   - In the "Replace with" field, provide your customized connection string that points to your Access database directory.
   - Ensure you select "Current project" and click "Replace All" to update all instances of the existing connection string in the code.

4. **Save Your Changes**:
   - Save the changes made in the VBA editor and close it.

5. **Open the "NCMS" XLSM File**:
   - Now, open the "NCMS" XLSM file. With the modified connection string, the application will connect to your Access database correctly.

By following these steps, you can customize the NHIS Claims Management System to work seamlessly with your database setup. This flexibility allows you to adapt the system to your specific environment while maintaining data security and accuracy.

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
