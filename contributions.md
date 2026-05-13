## 1. Prerequisites for Contributors

Before making any changes or testing the system, ensure your environment meets the following mandatory specifications:

* **Python Version**: You must have Python 3.10.0 installed.


* **Execution Environment**: The project is designed to be run within the `Opensource5.ipynb` file. Ensure you have a working Jupyter Notebook environment or a compatible IDE.



## 2. Contribution Workflow

The project is structured into five sequential modules that handle user data, issue tracking, and data export. When contributing or testing, please follow the operational flow below:

### Phase 1: User Data Management

If you are adding new test cases or modifying the user handling logic, remember that the system expects information for four users. Each entry must include:

* **Name**: The contributor's name.


* **Role**: Their function (e.g., Backend Dev, Web).


* **Language**: Primary programming language (e.g., Python, JavaScript).


* **Commits**: Confirmation of activity (e.g., yes).


* **Country**: Location of the contributor.



### Phase 2: Issue Tracking & Reporting

The second module manages newly reported issues. Contributors must ensure that five issues are logged with the following data points to maintain database consistency:

* **ID**: Unique identifier (e.g., ISS-001).


* **Title**: Summary of the issue.


* **Type**: Classified as either a 'Bug' or a 'Feature'.


* **Priority**: Ranked as Critical, High, Medium, or Low.


* **Reporter**: The name of the person reporting (must match a registered user).


* **Status**: Current state (Open, In Progress, or Resolved).



### Phase 3: Automated Processing

Modules three through five automate the conversion of the database into CSV and TXT formats and identify urgent issues. Ensure any code modifications do not break the automatic execution of these steps after Phase 2 is complete.

## 3. Code Standards & Testing

* **Data Persistence**: When adding features, ensure that the fourth and fifth codes still correctly filter urgent issues and apply those changes to both CSV and TXT files.


* **Demo Verification**: Before submitting a contribution, open the `Opensource5.ipynb` file and execute all cells to verify that the local demo runs without errors.



## 4. License Agreement

By contributing to this project, you agree that your contributions will be licensed under the **MIT License**.

* You are free to use, modify, and distribute this software.


* The software is provided "as is," without warranty of any kind.


* All copies or substantial portions of the software must include the original copyright and permission notice.
