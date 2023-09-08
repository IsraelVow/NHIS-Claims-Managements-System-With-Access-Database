**NHIS Claims Management System User Manual**

*Version: 1.0.0*

**Table of Contents**
1. [Introduction](#introduction)
   - [About NHIS Claims Management System](#about-nhis-claims-management-system)
   - [System Features](#system-features)

2. [Getting Started](#getting-started)
   - [Installation](#installation)
   - [Prerequisites](#prerequisites)

3. [User Authentication](#user-authentication)
   - [Login](#login)
   - [Registration](#registration)
   - [Forgot Password](#forgot-password)

4. [Dashboard](#dashboard)
   - [Overview](#overview)
   - [Analytics Cards](#analytics-cards)
   - [Sending Claims via Email](#sending-claims-via-email)
   - [User Greetings and Last Seen](#user-greetings-and-last-seen)

5. [Claims Management](#claims-management)
   - [Overview](#overview)
   - [Tabs Overview](#tabs-overview)
   - [Processing Claims](#processing-claims)
   - [Pending Claims](#pending-claims)
   - [Web Portal Integration](#web-portal-integration)
   - [Search HMO](#search-hmo)

6. [Tariff Adjustment](#tariff-adjustment)
   - [Accessing Tariff Adjustment](#accessing-tariff-adjustment)
   - [Adjusting Tariff Rates](#adjusting-tariff-rates)
   - [Adding New Tariff Information](#adding-new-tariff-information)
   - [Deleting Tariff Information](#deleting-tariff-information)
   - [Database Synchronization](#database-synchronization)

7. [Document Management](#document-management)
   - [Accessing Document Management](#accessing-document-management)
   - [Viewing Documents](#viewing-documents)
   - [Opening Documents](#opening-documents)
   - [Adding Documents](#adding-documents)
   - [Deleting Documents](#deleting-documents)
   - [Search Functionality](#search-functionality)
   - [Document Categories](#document-categories)
   - [Document Upload Guidelines](#document-upload-guidelines)

8. [Analysis & Reporting](#analysis--reporting)
   - [Accessing Analysis & Reporting](#accessing-analysis-&-reporting)
   - [Interactive Charts](#interactive-charts)
   - [Filtering Data](#filtering-data)
   - [Generating Reports](#generating-reports)
   - [Report Contents](#report-contents)
   - [Saving and Printing Reports](#saving-and-printing-reports)
   - [Emailing Reports](#emailing-reports)
   - [Return to Main Menu](#return-to-main-menu)

9. [Settings](#settings)
   - [Accessing Settings](#accessing-settings)
   - [Admin Control and User Permissions](#admin-control-and-user-permissions)
   - [Changing Password](#changing-password)
   - [User Credentials](#user-credentials)
   - [Registering a New User](#registering-a-new-user)
   - [Editing User Credentials](#editing-user-credentials)
   - [User Password Management](#user-password-management)
   - [Additional Settings](#additional-settings)
   - [Data Export](#data-export)
   - [Contributions and Upgrades](#contributions-and-upgrades)

10. [FAQs (Frequently Asked Questions)](#faqs-frequently-asked-questions)
   - [Q1 What are the system requirements to run the NHIS Claims Management System?](#q1-what-are-the-system-requirements-to-run-the-nhis-claims-management-system?)
   - [Q2 How do I adjust the database connection string to match my system directory?](#q2-how-do-i-adjust-the-database-connection-string-to-match-my-system-directory?)
   - [Q3 How can I register a new user within the NHIS Claims Management System?](#q3-how-can-i-register-a-new-user-within-the-nhis-claims-management-system?)
   - [Q4 How do I add a new HMO to the system with a custom claims form and tariff?](#q4-how-do-i-add-a-new-hmo-to-the-system-with-a-custom-claims-form-and-tariff?)
   - [Q5 What happens if an HMO doesn't have a custom claims form or tariff?](#q5-what-happens-if-an-hmo-doesn't-have-a-custom-claims-form-or-tariff?)
   - [Q6 Can I change my user credentials (email, phone number, password) within the system?](#q6-can-i-change-my-user-credentials-(email,-phone-number,-password)-within-the-system?)
   - [Q7 What happens if I forget my password or encounter login issues?](#q7-what-happens-if-i-forget-my-password-or-encounter-login-issues?)
   - [Q8 How can I contribute to the NHIS Claims Management System project?](#q8-how-can-i-contribute-to-the-nhis-claims-management-system-project?)
   - [Q9 Can I use the NHIS Claims Management System for my healthcare facility or organization?](#q9-can-i-use-the-nhis-claims-management-system-for-my-healthcare-facility-or-organization?)
   - [Q10 Is technical support available for the NHIS Claims Management System?](#q10-is-technical-support-available-for-the-nhis-claims-management-system?)

11. [Contact Support](#contact-support)
   - [Contact Information](#contact-information)
   - [Support Channels](#support-channels)

12. [Adding a New HMO with Custom Claims Form and Tariff](#adding-a-new-hmo-with-custom-claims-form-and-tariff)
   - [Step 1 Obtain the Custom Claims Form](#step-1-obtain-the-custom-claims-form)
   - [Step 2 Design the Custom Claims Form](#step-2-design-the-custom-claims-form)
   - [Step 3 Provide Tariff Information](#step-3-provide-tariff-information)
   - [Step 4 Integration with the System](#step-4-integration-with-the-system)
   - [Step 5 Testing and Validation](#step-5-testing-and-validation)
   - [Step 6 Deployment](#step-6-deployment)
   - [Step 7 User Training](#step-7-user-training)
   - [Step 8 Ongoing Support](#step-8-ongoing-support)

**1. Introduction**

## Introduction

## About NHIS Claims Management System

The NHIS Claims Management System is a robust software solution designed to streamline and automate the claims processing and management workflow for healthcare providers, specifically tailored for Almadina Clinic. This system offers a range of features to enhance efficiency and accuracy in managing claims, including dynamic claim forms, database integration, user permissions, real-time analytics, document management, data export, web portal integration, and more.

## System Features

The NHIS Claims Management System comes with the following key features:
- Dynamic Claim Forms: Automatically generates HMO-specific claim forms.
- Database Integration: Stores claims data in an Access database for easy retrieval and analysis.
- User Permissions: Admins can control user access to various features for enhanced security.
- Real-time Analytics: Interactive charts provide insights into claim statistics.
- Document Management: Users can access and manage essential documents within the application.
- Data Export: Generate reports and export data to Excel or PDF formats.
- Web Portal Integration: Seamless integration with HMO web portals streamlines claim submission.


**2. Getting Started**

## Getting Started

## Installation

To get started with the NHIS Claims Management System, follow these steps:
1. Clone the GitHub repository to your local directory.
2. Ensure you have Microsoft Excel and the Access Database Engine installed.
3. Adjust the database connection string in the code to match your system's directory path (details in the README file).

## Prerequisites

Make sure you have the following prerequisites before using the system:
- Microsoft Excel
- Access Database Engine (if not already installed)


**3. User Authentication**

## User Authentication

## Login

To access the system, use the provided login credentials (Username: `Admin`, Password: `admin1234`). If you are a new user, you can also register for an account (details in the Registration section).

## Registration

1. On the login page, click the "Create Account" button.
2. Enter the admin password (`admin1234`) to unlock the registration form.
3. Complete the registration form with your details.
4. Click the "Register" button to create your account.

## Forgot Password

If you forget your password, please contact the system administrator or support for assistance.


**4. Dashboard**

## Dashboard

## Overview

The dashboard provides a quick overview of essential information and functionalities within the NHIS Claims Management System. It offers insights into the system's performance and allows users to perform various actions. Below, we'll explore the different elements on the dashboard.

![Dashboard Screenshot](https://imgur.com/mHEidJA.png)

**Analytics Cards**
- **Total Number of Billed Services**: This card displays the total number of services billed by the system.
- **Total Amount Claimed**: It shows the cumulative amount claimed through the system.
- **Number of Pending Claims**: This card highlights the count of pending claims yet to be processed.

## Sending Claims via Email

On the top-left corner of the dashboard, you'll find a "Send Email" button. Clicking this button opens a user form where you can send claims via email. The system will request you to select the HMO email address from a dropdown and attach the saved claim forms for the chosen HMO.

**User Greetings and Last Seen**
- At the top-right corner of the dashboard, you'll find user greetings that personalize your experience.
- The "Last Seen" information tells you when you last accessed the system. This data is derived from a helper spreadsheet.

The dashboard provides a convenient and user-friendly interface for accessing vital functions and monitoring system statistics.


**5. Claims Management**

## Claims Management

## Overview

The "Claims Management" section is the core of the NHIS Claims Management System. It allows NHIS officers to efficiently process and manage claims submitted by healthcare providers and insurance enrollees. This section is divided into several tabs, each serving a specific purpose.

## Tabs Overview

The Claims Management section features the following tabs on the left pane:

- **Public Claims**: Access Public HMO claims for processing.
- **Private Claims**: Access Private HMO claims for processing.
- **Pending Claims**: Manage and complete pending claim transactions.
- **Web Portal**: Access HMO web portals for streamlined claim submissions.
- **Search HMO**: Search for specific HMO details within the system.

## Processing Claims

To process claims, follow these steps:

1. **Select the Tab**: Click on either "Public Claims" or "Private Claims" based on the HMO you want to process claims for.
2. **Pre-Entry Form**: Fill in the required details in the Pre-Entry Form. These details include HMO Name, Enrollee Name, NHIS No, Authorization Code, Diagnosis, and more.
3. **Load to Form**: Click the "Load to Form" button to generate a specific HMO claim form with the entered details.
4. **Enter Services**: On the generated claim form, enter the services, drugs, and other medical details as needed.
5. **Calculate Totals**: The system calculates the rates and totals based on the services entered.
6. **Print or Save**: You can print the claim form or save it to your local directory for reference.
7. **Database Storage**: The system automatically saves the claim details to the database for record-keeping.

## Pending Claims

The "Pending Claims" tab allows you to manage transactions that require further processing or adjustments. You can easily retrieve and continue working on pending claims in this section.

## Web Portal Integration

The "Web Portal" tab offers a seamless way to access HMO web portals for submitting claims directly to the respective HMOs.

## Search HMO

If you need to find specific HMO details or access forms for an HMO not listed on the main dashboard, you can use the "Search HMO" tab.

The Claims Management section empowers NHIS officers to efficiently handle claims, track transactions, and ensure timely submission to HMOs.


**6. Tariff Adjustment**

## Tariff Adjustment

**Overview**
The "Tariff Adjustment" feature in the NHIS Claims Management System allows authorized users to adjust tariff rates for services provided by healthcare providers. This feature is essential to keep the system up-to-date with the latest tariff information provided by HMOs or as required.

## Accessing Tariff Adjustment

To access the Tariff Adjustment feature:

1. From the main menu, click on the "Claims Management" tab.
2. Select "Tariff" from the left pane menu.

## Adjusting Tariff Rates

Follow these steps to adjust tariff rates:

1. **Select HMO**: Choose the HMO for which you want to adjust tariff rates from the dropdown menu.
2. **Service Search**: Use the search bar to find a specific service by typing keywords or phrases. The system will filter and display matching services as you type.
3. **Editing Tariff Rates**: Double-click on the service you want to edit. This opens an editable field where you can enter the new tariff rate.
4. **Saving Changes**: After adjusting the tariff rate, press "Enter" or click outside the field to save the changes. A notification will confirm the tariff adjustment.
5. **Reset to Default**: To revert a tariff rate to its default value, double-click on the adjusted rate and press "Enter."

## Adding New Tariff Information

To add new tariff information:

1. **Select HMO**: Choose the HMO for which you want to add tariff information.
2. **Service**: Enter the name or description of the new service in the "Service" field.
3. **Tariff Rate**: Enter the tariff rate for the new service.
4. **Save**: Click the "Save" button to add the new tariff information.

## Deleting Tariff Information

To remove tariff information:

1. **Select HMO**: Choose the HMO from which you want to delete tariff information.
2. **Select Service**: Select the service from the list that you wish to delete.
3. **Delete**: Click the "Delete" button to remove the selected tariff information.

## Database Synchronization

The system automatically synchronizes tariff adjustments with the database to ensure consistency in tariff rates. Any changes made here will affect tariff rates throughout the system.

**Note:** Be cautious while adjusting tariff rates, as this may impact billing and claims calculations. Ensure that rate adjustments align with the latest agreements with healthcare providers and HMOs.

The Tariff Adjustment feature simplifies the process of managing and updating tariff rates, ensuring that the system reflects the most accurate billing information.


**7. Document Management**

## Document Management

**Overview**
The "Document Management" feature in the NHIS Claims Management System allows users to access, organize, and manage essential documents and files related to healthcare claims. This feature enhances efficiency by centralizing document storage within the application.

## Accessing Document Management

To access the Document Management feature:

1. From the main menu, click on the "Claims Management" tab.
2. Select "Documents" from the left pane menu.

## Viewing Documents

1. Upon entering the Document Management section, you will see a list of documents available for the selected HMO.
2. Documents are categorized for easy navigation and include items such as forms, contracts, and official documents.

## Opening Documents

To open and view a document:

1. Click on the document name or description in the list.
2. The document will open using the default system PDF viewer, allowing you to read and review its contents.

## Adding Documents

To add new documents to the system:

1. Click on the "Add Document" button.
2. A file dialog will appear, allowing you to browse your local directory to select the document you want to add.
3. Once selected, click "Open" to upload the document to the system.

## Deleting Documents

To remove documents from the system:

1. Select the document you wish to delete from the list.
2. Click on the "Delete" button.
3. A confirmation prompt will appear to ensure you want to delete the selected document.
4. Confirm the deletion, and the document will be permanently removed from the system.

## Search Functionality

The system includes a search bar that enables you to find specific documents by entering keywords or phrases. As you type, the system will filter and display matching documents.

## Document Categories

Documents are organized into categories to help users locate the required information more efficiently. Categories may include "Claim Forms," "Contracts," "Reports," and more, depending on your organization's requirements.

## Document Upload Guidelines

When adding documents to the system, consider the following guidelines:

- Ensure that documents are in PDF format for compatibility.
- Use clear and descriptive filenames for easy identification.
- Categorize documents appropriately to maintain an organized document library.

**Note:** The Document Management feature simplifies the process of storing and accessing essential documents, reducing the need to navigate through multiple folders and directories on your computer. It ensures that crucial documents are readily available for reference and use.


**8. Analysis & Reporting**

## Analysis & Reporting

**Overview**
The "Analysis & Reporting" feature in the NHIS Claims Management System empowers users to gain insights from claims data through interactive charts and generate detailed reports. These tools assist in making informed decisions and monitoring claim processing efficiency.

## Accessing Analysis & Reporting

To access the Analysis & Reporting feature:

1. From the main menu, click on the "Claims Management" tab.
2. Select "Analysis & Report" from the left pane menu.

## Interactive Charts

The Analysis & Reporting section provides four interactive charts, each offering unique insights:

1. **Top 10 Active HMOs (Claims Form):** This bar chart displays the top 10 HMOs based on the number of claims submitted using the claims form.

2. **Top 10 Active HMOs (Web Portal):** Another bar chart showcasing the top 10 HMOs based on the number of claims submitted via web portals, along with the total claim amount.

3. **Claims Distribution (Application vs. Web Portal):** A doughnut chart that compares the distribution of claims processed via the application and web portal, presented as a percentage.

4. **Top 5 Users by Claims:** This pie chart lists the top 5 users (claims officers) with the highest number of bills created.

## Filtering Data

Before generating charts, users have the option to filter data by specifying a date range. This feature allows you to tailor your analysis to cover specific time periods.

## Generating Reports

Once you've customized your chart view, you can generate a detailed report for your analysis:

1. Click on the "Generate Report" button.
2. The system will close the Analysis & Reporting section and open a dedicated report spreadsheet.

## Report Contents

The report spreadsheet captures the following information:

- User's name.
- Date of the report generated.
- Date range of the report (based on your filter settings).

The main table includes the following columns:

- **Description:** Lists the specific criteria or data point analyzed.
- **Quantity:** Displays the quantity or count related to the criteria.
- **Amount:** Shows the calculated amount or total associated with the criteria.

The report concludes with a summary of the total claimed amounts for both the application and web portal. The system automatically calculates these figures for your convenience.

## Saving and Printing Reports

You can save your generated report in two formats: Excel (XLSX) and PDF.

- To save the report in Excel format, click on the "Save Report as XLSX" button.
- To save the report in PDF format, click on the "Save Report as PDF" button.

Furthermore, you can print a hard copy of your report. Click on the "Print Report" button, and the system will open a print preview window for you to make any necessary printing adjustments.

## Emailing Reports

If you need to share your report with colleagues or superiors, the system provides an email feature. Click on the "Send via Email" button. The system will open your default email client, attaching the report as a PDF and providing a pre-filled email body explaining the report's content.

## Return to Main Menu

To return to the main menu after generating or viewing a report, click on the "Back to Menu" button located at the bottom of the report spreadsheet. This action will close the report and return you to the Analysis & Reporting section.


**9. Settings**

## Settings

**Overview**
The "Settings" section in the NHIS Claims Management System provides essential configuration options and user management capabilities. Administrators can tailor the system to their specific needs, set user permissions, and manage user credentials.

## Accessing Settings

To access the Settings section:

1. From the main menu, click on the "Settings" tab.

## Admin Control and User Permissions

The NHIS Claims Management System allows administrators to set user permissions for various system features. Permissions can be customized for each user to enhance data security and control access. Here are the available permissions:

- **Admin Pane Access:** Grants or restricts access to the admin control panel.
- **Search Tariff:** Determines whether users can search and view tariff rates.
- **HMO Tariff Adjustment:** Controls the ability to adjust tariff rates for HMOs.
- **Delete Processed Claims:** Manages the ability to delete processed claims from the system.
- **Make Online Claims:** Permits or restricts users from submitting claims online.
- **View Sent Claims:** Allows users to view previously sent claims.
- **View Analysis Indicators:** Controls access to the Analysis & Reporting section.
- **Delete Saved Documents:** Manages the ability to delete saved documents and records.

Administrators can enable or disable these permissions using a dynamic ON/OFF button interface within the system.

## User Credentials

The NHIS Claims Management System includes a login page with user authentication. Users are required to enter valid credentials to access the system. The default admin login credentials are as follows:

- **Username:** Admin
- **Password:** admin1234 (case sensitive)

## Registering a New User

The system also allows administrators to register new users. To register a new user:

1. Click the "Create Account" button located at the bottom left of the login page.
2. Enter the admin password (default: admin1234) when prompted.
3. A registration form will appear, allowing you to create a new user account.

## User Password Management

Users have the option to change their credentials, including email, phone number, and password, directly within the system. This feature enhances user autonomy and data security.

## Additional Settings

In addition to user permissions and credentials, administrators can manage other system settings:

- Editing HMO Web Addresses: Admins can update HMO web addresses if they change.
- Deleting or Removing User Accounts: Provides the ability to remove user accounts as needed.
- Adding Public HMO Details: Allows for the addition of new public HMO details.
- Adding Private HMO Details: Permits the addition of new private HMO details.

## Data Export

Admins can export data records within a specified date range to both PDF and XLSX formats. This feature facilitates data backup and sharing.

## Contributions and Upgrades

Contributors are welcome to enhance the system and make improvements based on their specific requirements. Refer to the "Contributing" section of this user manual for detailed guidelines on how to contribute to this open-source project.


**10. FAQs (Frequently Asked Questions)**

## FAQs (Frequently Asked Questions)

This section provides answers to some common questions about the NHIS Claims Management System. If you have a question that's not covered here, please feel free to reach out for additional support.

## Q1. What are the system requirements to run the NHIS Claims Management System?

**A:** To use the NHIS Claims Management System, you need the following:
- Microsoft Excel
- Access Database Engine (if not already installed)

## Q2. How do I adjust the database connection string to match my system directory?

**A:** To adjust the database connection string:
1. Open the workbook in Excel.
2. Go to the VBE (Visual Basic for Applications) editor.
3. Navigate to the "ThisWorkbook" object on the left in the Object Explorer.
4. Find the `Workbook_Open()` event.
5. Uncomment all the code in this event to allow the system to request user credentials when the workbook is opened. Modify the database connection string in the code to match your system's directory path.

## Q3. How can I register a new user within the NHIS Claims Management System?

**A:** To register a new user:
1. Click the "Create Account" button located at the bottom left of the login page.
2. Enter the admin password (default: admin1234) when prompted.
3. A registration form will appear, allowing you to create a new user account.

## Q4: How do I add a new HMO to the system with a custom claims form and tariff?

A1: To add a new HMO with a custom claims form and tariff, follow these steps:

1. Provide the custom claims form: If the HMO has their own claims form, you'll need to request this form. Our system can accommodate custom forms designed with native VBA controls (toolbox).

2. Design the custom claims form: Once you have the HMO's claims form, our team will design it to seamlessly integrate with the NHIS Claims Management System. We'll code each button, combobox, and other elements to ensure smooth claim processing.

3. Provide the tariff: The HMO will also need to provide their tariff rates. Tariffs are used to calculate claim amounts based on the services provided. This information is essential for accurate claim processing.

4. Integration: We'll integrate the custom claims form and tariff into the system, ensuring that NHIS officers can easily process claims for enrollees under the new HMO.

## Q5: What happens if an HMO doesn't have a custom claims form or tariff?

A2: If an HMO doesn't have a custom claims form or tariff, they will adopt the provider's (Almadina Clinic) custom claims form and use the provider's tariff. This means that claims for enrollees under such HMOs will be processed using the standard form and tariff provided by Almadina Clinic. The system is flexible enough to accommodate both custom and standard forms, ensuring claims can still be processed seamlessly.

## Q6. Can I change my user credentials (email, phone number, password) within the system?

**A:** Yes, users have the option to change their user credentials directly within the system. This feature provides greater autonomy and data security.

## Q7. What happens if I forget my password or encounter login issues?

**A:** If you forget your password or experience login issues, please contact your system administrator for assistance. They can reset your password and help you regain access to the system.

## Q8. How can I contribute to the NHIS Claims Management System project?

**A:** Contributions to this open-source project are welcome! Follow these steps to contribute:
1. Fork the project on GitHub.
2. Create a new branch for your feature or improvement.
3. Make your changes and commit them.
4. Push your branch to GitHub.
5. Create a pull request to merge your changes into the main project.

Please adhere to the project's coding guidelines and maintain a clean commit history.

## Q9. Can I use the NHIS Claims Management System for my healthcare facility or organization?

**A:** Yes, you are welcome to use and customize the NHIS Claims Management System for your healthcare facility or organization. The system is designed to be adaptable to different environments and requirements.

## Q10. Is technical support available for the NHIS Claims Management System?

**A:** Yes, technical support is available for users of the NHIS Claims Management System. If you encounter any technical issues or have questions about the system, please reach out to your system administrator or the project's contributors for assistance.


**11. Contact Support**

## Contact Support

If you encounter technical issues, have questions, or require assistance with the NHIS Claims Management System, you can reach out to our support team. We are here to help you ensure the smooth operation of the system and address any concerns you may have.

## Contact Information:

- **Email:** [Israeljvow@gmail.com](mailto:Israeljvow@gmail.com)
- **Phone:** +234 (081) 6561-1658

Our support team is available during business hours to assist you. When contacting support, please provide detailed information about the issue you're experiencing, including any error messages or unusual behavior. This will help us diagnose and resolve the problem more effectively.

We value your feedback and aim to provide timely assistance to ensure your NHIS Claims Management System experience is as seamless as possible. Don't hesitate to get in touch with us whenever you need support.


**12. Adding a New HMO with Custom Claims Form and Tariff**

## Adding a New HMO with Custom Claims Form and Tariff

In the NHIS Claims Management System, you have the flexibility to add a new HMO (Health Maintenance Organization) along with their custom claims form and tariff. This process allows NHIS officers to seamlessly process claims for enrollees under the newly added HMO. Here's a step-by-step guide:

## Step 1. Obtain the Custom Claims Form

1. Contact the new HMO to request their custom claims form. Ensure they provide you with all the necessary details about the form's layout. This includes information about fields, labels, and any specific requirements they might have.

2. The HMO typically provides this form in Excel format. Make sure you receive the form in a compatible digital format.

## Step 2. Design the Custom Claims Form

3. Once you have the HMO's custom claims form, our development team will design it to integrate seamlessly with the NHIS Claims Management System.

4. We will use native VBA controls (toolbox) to create a user-friendly interface within Excel. Each button, combobox, textbox, and other elements will be coded to enable NHIS officers to process claims efficiently.

5. This design process ensures that the custom claims form aligns with the system's functionality, allowing for smooth data entry and processing.

## Step 3. Provide Tariff Information

6. In addition to the custom claims form, the HMO must provide their tariff rates. Tariffs are essential for accurately calculating claim amounts based on the services provided.

7. Ensure that you have a clear understanding of how the tariff should be applied to different services. Tariffs should include pricing details for various medical procedures, consultations, medications, and other healthcare services.

## Step 4. Integration with the System

8. Our development team will integrate the custom claims form and tariff information into the NHIS Claims Management System.

9. This integration process ensures that NHIS officers can easily select the new HMO from the system's interface, access the custom claims form, and utilize the specified tariff rates for precise claim processing.

## Step 5. Testing and Validation

10. Before deploying the new HMO to the live system, thorough testing and validation are essential. Verify that the custom claims form accurately captures data, and that tariff calculations align with the HMO's rates.

11. Conduct test claims submissions to ensure that the integration works seamlessly and that data flows correctly between the custom form and the system's database.

## Step 6. Deployment

12. Once testing is successful, the new HMO, along with their custom claims form and tariff, can be deployed to the live NHIS Claims Management System.

## Step 7. User Training

13. Ensure that NHIS officers receive training on how to use the new custom claims form and understand the tariff structure for the specific HMO.

## Step 8. Ongoing Support

14. Maintain open communication with the new HMO to address any questions or issues that may arise during the initial rollout and ongoing usage.

15. Monitor the performance of the custom form and tariff integration to ensure efficient claim processing.

By following these steps, you can seamlessly onboard new HMOs into the NHIS Claims Management System, providing a user-friendly experience for NHIS officers and accurate claim processing for enrollees.

For additional guidance and support, please refer to the [User Manual](https://github.com/IsraelVow/NHIS-Claims-Managements-System-With-Access-Database/blob/main/Documentation/User%20Manual.md) or [contact our support team](mailto:Israeljvow@gmail.com).

**Note**: The onboarding process may vary depending on the specific requirements of the HMO and the compatibility of their claims form with the system. Clear communication and collaboration with the HMO are crucial for a successful integration.