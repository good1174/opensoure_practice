Project Documentation: Opensource_week5_Assignment
1. Introduction and Purpose
The Opensource_week5_Assignment project is a specialized management toolkit designed for open-source project maintainers. It provides a structured environment to track contributor demographics, manage issue lifecycles, and export project data into portable formats. The system is designed to streamline administrative tasks, allowing maintainers to focus on code quality and community growth.

2. System Requirements
To ensure the software operates correctly and handles data structures as intended, the following environment must be prepared:

Python Version: 3.10.0 (Mandatory)

Environment: Jupyter Notebook or any IDE supporting .ipynb files.

3. Functional Components
The system is divided into five distinct functional modules that work sequentially:

Module 1: User Information Management – Collects and stores data for new project members, including their roles and primary programming languages.

Module 2: Issue Reporting & Tracking – Facilitates the logging of bugs and feature requests with assigned priority levels and statuses.

Module 3: Database Conversion – Automatically transforms internal project data into universally accessible .csv and .txt formats.

Module 4: Urgent Issue Analytics – Filters and displays critical issues that require immediate attention from the maintainers.

Module 5: External File Synchronization – Applies the urgency filtering logic directly to the exported CSV and TXT files for consistent reporting.

4. Operating Instructions
Phase 1: User Registration
During the first execution phase, the system will prompt for information for four separate users. For each user, you must provide the following details:

Name (e.g., Minho)

Role (e.g., Backend Dev)

Programming Language (e.g., Python)

Commits (e.g., yes)

Country (e.g., Korea)

Phase 2: Issue Logging
Upon completing the user registration, the system moves to the issue management phase. You are required to log five issues using the following parameters:

ID: Unique identifier (e.g., ISS-001)

Title: Brief description (e.g., Login crash)

Type: Classification as either 'Bug' or 'Feature'

Priority: Critical, High, Medium, or Low

Reporter: The name of the user reporting the issue

Status: Open, In Progress, or Resolved

Phase 3: Automated Execution
The third, fourth, and fifth modules execute automatically once the initial data entry is complete. No further manual input is required to generate the reports or filter urgent tasks.

5. Quick Start (Local Demo)
To begin using the toolkit, follow these steps:

Ensure your local environment is running Python 3.10.0.

Navigate to the project directory and locate the Opensource5.ipynb file.

Open the file in your preferred notebook environment.

Select "Run All Cells" to initiate the sequential workflow.

6. License and Usage Notices
This project is released under the MIT License. This granting of rights allows users to freely use, copy, modify, merge, and distribute the software, provided that the copyright notice and this permission notice are included in all copies or substantial portions of the software.

The software is provided "as is," without warranty of any kind. The authors or copyright holders are not liable for any claim, damages, or other liability arising from the use of this software.
