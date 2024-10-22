
# Overview

MapmyIndia [Workmate](https://workmate.mapmyindia.com/wmnextgen/#/home/people/activity) is a ***field/workforce management app*** that geo-enables the field force, enhances productivity & offers a multitude of features that augment field/workforce management with location Intelligence and automation. It provides visual insights into field force operations by tracking field users' movements through a unique layer of spatial intelligence. 

---

**Workmate** offers a unique set of features that are highly **customizable**, **scalable**, & **flexible**. Some pain points that Workmate resolves are **automating distance-based reimbursements** & **attendances to save costs**, **optimize beat** & **route planning by allocating Nearby Tasks based on Location**, providing safe & hyperlocal navigation to client locations, verification of tasks by monitoring location & geo-tagging client locations for a standardized database. These functions enable increased revenue, cost savings & a healthier client-business relationship due to greater visibility across the board.  
 
## Workmate Web 

> ## **A.1. Bulk Actions (User)**

### ***Introduction***
The new Bulk Actions functionality enables admins to perform multiple actions on users directly from the user list UI. This feature streamlines the management of large user groups, improving operational efficiency.

### ***Key Features & Benefits***

**Activate/Deactivate Users:** Admins can quickly activate or deactivate multiple users in a single action, ensuring swift role management.

**Delete Users:** Easily delete multiple users from the system, simplifying the cleanup process and saving time.
Send Emails: Allows the admin to send emails to multiple users at once, streamlining communication with large groups.

**Field Update:** Provides the ability to select a specific field from user records and update its value for all selected users, reducing manual data entry.

### ***Conclusion***
The Bulk Actions feature provides admins with powerful tools to manage user records quickly and efficiently, improving operational workflows and saving time.

------

> ## **A.2. User Bulk Update through Kafka**

### ***Introduction***
The user bulk update process has been improved by integrating Kafka-based real-time updates. Previously, the bulk update process ran on a 40-minute scheduler, causing delays. Now, updates reflect immediately, improving the user experience and reducing operational lag.

### ***Key Features & Benefits***
**Real-Time Processing:** Kafka integration allows for real-time bulk updates, ensuring changes are reflected instantly.

**No More Delays:** Eliminates the lag caused by the previous scheduler-based updates, leading to faster operations and more up-to-date information.

**Improved Scalability:** Kafka's capability to handle high data volumes ensures efficient processing of large user updates without performance degradation.

----

### ***Conclusion***
Switching to Kafka for user bulk updates has significantly improved the system's performance and responsiveness, ensuring that admins can make updates without waiting for scheduled processes.

## **A.3. Service Area for Office Location**

### ***Introduction***

We’ve introduced a feature that allows admins to define a service area for office locations based on a radius. This feature enhances the ability to manage and monitor field agents by visually representing geofences around office locations.

### ***Key Features & Benefits***

***Service Area Association:*** Users can associate service areas for each office location based on a defined radius (in kilometers or meters), ensuring that branches serve specific geographic areas.

***Geofence Visualization:*** A color-coded geofence is created around the office location on the map, allowing managers to see the area within which field agents are expected to operate.

***Field Agent Tracking:*** Managers can easily track if field agents move outside the defined service area, ensuring compliance with operational boundaries.


### ***Conclusion***

The service area feature enhances location-based management by providing visibility into office coverage areas and ensuring that field agents operate within their designated boundaries.

> ## **A.4. Dynamic Task Sorting**

### ***Introduction***

The Dynamic Task Sorting feature allows users to sort tasks by **creation date**, **updation date**, or **due date in both ascending and descending order**. This functionality is designed to offer flexibility and improve **task management**, **enabling users to prioritize tasks based on their needs**.

### ***Key Features & Benefits***

**Sort by Creation Date:** Users can sort tasks by the date they were created, allowing for easy management of new and old tasks.
Sort by Update Date: Sorting tasks by the last update ensures users can focus on the most recently modified tasks.

**Sort by Due Date:** Users can prioritize tasks based on their deadlines, ensuring timely completion of important tasks.

**Ascending & Descending Order:** Sorting can be done in both ascending and descending order, giving users complete control over task organization.

### ***Conclusion***
The Dynamic Task Sorting feature provides users with the flexibility to organize tasks according to their specific needs, improving task visibility and management.

---

> ## **A.5. Support Ticket to Raise Issues**

### ***Introduction***

The Support Ticket feature allows users to raise issues directly from the Workmate web console or mobile application. By enabling users to report issues with detailed information, this feature enhances support and troubleshooting processes.

### ***Key Features & Benefits***

**Issue Reporting:** Users can report issues they encounter on the platform, ensuring faster resolution and enhanced support.

**Attach Screenshots:** Users can attach relevant screenshots to help illustrate the issue, making it easier for the support team to understand the problem.

**Category & Sub-Category:** The feature allows users to categorize the issue by selecting appropriate categories and sub-categories, ensuring that the issue is routed to the correct team.



### ***Conclusion***

The Support Ticket feature empowers users to report issues in a structured manner, ensuring faster and more accurate resolutions through better communication and detailed issue reporting.

---

> ## **A.6. RBAC Configuration through UI**

### ***Introduction***

**Role-Based Access Control (RBAC)** configuration through the UI allows the product and support teams to define and manage access for Workmate accounts directly from the super admin console. This empowers teams to customize access based on roles, designations, and role hierarchies.

### ***Key Features & Benefits***

**RBAC Configuration:** Allows admins to configure role-based access for any account, ensuring that the right users have the appropriate access permissions.

**Customizable Access & Scope:** Users can define the scope of access for different designations, improving security and ensuring role-appropriate access.

**Role Hierarchy:** Supports defining role hierarchies to control access to features and data, enhancing operational security and clarity.


### ***Conclusion***

RBAC Configuration through the UI enhances control and flexibility in managing access permissions for Workmate accounts, ensuring that users have the appropriate access based on their role and designation.

---


> ## **A.7. Task Trail to Show Workflow Form Data**

### ***Introduction***
The Task Trail feature allows admins and managers to view workflow form data filled by on-field executives at each step of a workflow. This information is accessible directly on the task page, improving visibility into task progress and field activities.


### ***Key Features & Benefits***

**Workflow Data Access:** Admins and managers can view detailed workflow form data, offering insights into the data collected by field executives during task completion.

**Task Page Integration:** All workflow data is available on the task page, making it easy to access without navigating away from the task itself.

**Enhanced Task Visibility:** Improves task monitoring and oversight by providing full visibility into each step of the task's workflow and the data collected.

### ***Conclusion***

The Task Trail feature enhances transparency and control by providing easy access to workflow form data associated with each task, ensuring managers and admins have full visibility into on-field operations.

---


> ## **A.8. Add Extended Fields for User & Client Creation from UI**

### ***Introduction***

The Add Extended Fields for User & Client Creation feature is a significant enhancement to the user and client creation process. This feature allows admins to input extended fields directly from the UI when creating new users or clients, simplifying the onboarding process and eliminating the need for manual Excel uploads.


### ***Key Features & Benefits***

**Direct Extended Field Input:** Users can now add extended fields for new users and clients directly from the UI, improving the speed and efficiency of data entry.

**Role-Based Access Integration:** Extended fields related to role-based access can be filled during the user or client creation process, ensuring accurate access control from the start.

**No Need for Excel Uploads:** This feature removes the dependency on Excel sheets for updating user or client details, even for minor changes like adding one or two users.

**Streamlined Onboarding:** Reduces the steps required to create users and clients, resulting in a faster and more streamlined onboarding process.


### ***Conclusion***

The Add Extended Fields for User & Client Creation from UI feature simplifies and accelerates the creation process for users and clients. By enabling the entry of extended fields directly from the UI, it reduces manual effort and improves the overall user experience, particularly for admins managing multiple accounts.

> ## **A.9.Client Data Segregation at Account Level (Major Change)**

### ***Introduction***

We have implemented a significant change in Workmate’s database by segregating the Client Master Table at the account level. Previously, all client data was stored in a single master table, which contained clients from all accounts. With this update, each account now has its own dedicated client table, improving the overall performance and efficiency of the platform.

### ***Key Features & Benefits***

**Faster Client Searches:** By segregating client data at the account level, the search process becomes significantly faster, as the system no longer needs to query a large, centralized table containing data for all accounts.

**Improved Database Performance:** Segregating client data reduces the load on the database, leading to better performance for other operations that rely on client data, such as reporting, filtering, and task assignments.

**Enhanced Data Security:** Each account’s client data is now more securely isolated, reducing the risk of cross-account data exposure and improving overall data governance.

**Simplified Data Management:** This change simplifies data management tasks such as updates, backups, and data restoration, as each account’s client data can be handled independently.

**Scalability:** With client data separated per account, the system can now scale more effectively. As the number of accounts and clients grows, this structure allows for smoother operations without performance bottlenecks.

**More Efficient Resource Usage:** Segregated tables allow more efficient use of database resources, improving query processing times and optimizing performance for high-volume operations.

### ***Conclusion***

The Client Data Segregation at Account Level is a major architectural improvement that boosts performance, security, and scalability. With faster searches and improved database management, this change enhances the overall user experience, particularly for organizations handling large volumes of client data.


# B. Workmate Android

> ## **B.1. Support Ticket to Raise Issues**

### ***Introduction***

The Support Ticket feature allows users to raise issues directly from the Workmate web console or mobile application. By enabling users to report issues with detailed information, this feature enhances support and troubleshooting processes.

### ***Key Features & Benefits***

**Issue Reporting:** Users can report issues they encounter on the platform, ensuring faster resolution and enhanced support.

**Attach Screenshots:** Users can attach relevant screenshots to help illustrate the issue, making it easier for the support team to understand the problem.

**Category & Sub-Category:** The feature allows users to categorize the issue by selecting appropriate categories and sub-categories, ensuring that the issue is routed to the correct team.


### ***Conclusion***

The Support Ticket feature empowers users to report issues in a structured manner, ensuring faster and more accurate resolutions through better communication and detailed issue reporting.

> ## **B.2. Refresh Token Implementation**


### ***Introduction***

The Refresh Token Implementation ensures users maintain uninterrupted access to Workmate Studio. When a session token expires, the system will now automatically generate a new one, preventing users from being logged out unexpectedly.

### ***Key Features & Benefits***

**Seamless User Experience:** No more sudden logouts due to token expiration, ensuring users can work uninterrupted.

**Automatic Token Renewal:** The system automatically generates a new session token as soon as the current one expires, ensuring users don’t have to log back in manually.

**Enhanced Security:** This feature maintains the necessary security checks while improving user convenience by keeping sessions active without compromising security.


### ***Conclusion***

With Refresh **Token Implementation,** users can enjoy a seamless experience on Workmate Studio, avoiding frustrating session timeouts and interruptions, all while ensuring robust security protocols

> ## **B.4 Bug Fixes and Optimizations**

### ***Introduction***

To ensure the best possible performance and reliability, we have implemented various bug fixes and optimizations. These improvements address known issues and enhance the overall user experience.

### ***Key Features & Benefits***

**Bug Fixes:** Various bugs have been identified and resolved, ensuring smoother operation and increased stability.

**Performance Enhancements:** Optimizations have been made to improve the speed and responsiveness of the app.

**Enhanced User Experience:** Users will enjoy a more reliable and efficient app, with fewer disruptions and improved functionality.

## **Ongoing POCs:** Small Finance & Microfinance 

Several prominent players from the small finance and microfinance space are currently running ***Proof of Concepts (POCs)*** to explore Workmate's functionalities. These POCs aim to boost the efficiency and productivity of collection and sales agents while automating their processes. The organizations involved include:

**IDFC**

**Annapurna Finance**

**Ujjivan**

**Groww**

**Muthoot Finance**

**HDBFS**

These organizations are looking to leverage Workmate’s capabilities to streamline operations and enhance the performance of their agents in the field.
