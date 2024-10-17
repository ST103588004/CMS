# CMS
Overview
The Contract Monthly Claim System (CMCS) is a comprehensive web-based application developed using ASP.NET MVC. The primary objective of the system is to streamline the submission, verification, and approval of monthly claims submitted by Independent Contractor (IC) lecturers. The system facilitates lecturers in submitting their claims, uploading supporting documents, and tracking the progress of their claims. It also provides Programme Coordinators and Academic Managers with an interface to review, verify, and approve claims efficiently.

Key Features
Claim Submission: Lecturers can easily submit monthly claims, providing details like hours worked and hourly rate.
Document Upload: The system supports uploading necessary supporting documents along with the claims.
Verification and Approval: Programme Coordinators and Academic Managers can verify and approve claims.
Claim Status Tracking: Lecturers can monitor the status of their claims, ensuring full transparency from submission to settlement.
User Role Management: The system includes distinct roles for Lecturers, Programme Coordinators, and Academic Managers, each with specific functionalities.
Technologies Used
ASP.NET Core MVC
C#
Entity Framework Core
SQL Server for the database
HTML, CSS, and Bootstrap for the front-end interface
Azure services for cloud-based file storage
Installation and Setup
To get started with the project, follow these steps:

Clone the repository:
bash
Copy code
git clone <repository-url>
Open the project in Visual Studio.
Restore the NuGet packages:
bash
Copy code
dotnet restore
Update the connection string in appsettings.json to point to your SQL Server instance.
Apply the necessary database migrations:
bash
Copy code
dotnet ef database update
Run the application:
bash
Copy code
dotnet run
Usage
Lecturers can log in to submit new claims and upload supporting documents.
Programme Coordinators and Academic Managers can log in to verify and approve the claims submitted by lecturers.
Contribution
Contributions are welcomed! Please feel free to fork the repository and submit pull requests.

License
This project is licensed under the MIT License.
