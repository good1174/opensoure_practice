# 

# MUST INSTALL
You have to installed the python 3.10.0.

# Opensoure_week5_Assignment

---

## Purpose
This code is intended for people who want to manage an open-source project.

The first code handles new user information.
The second code manages newly reported issues.
The third code converts the database into CSV and TXT formats.
The fourth code displays urgent issues.
The fifth code applies the fourth code’s functionality to the CSV and TXT files.

## Quick Usage

For the first code
You must enter the name,role,programming language,commits,country.
This would be repeated for 4 times.
For example

' python
name: Minho
role: Backend Dev
language: Python
commits: yes
country: Korea
name: Jisoo
role: Web
language: JavaScript
commits: yes
country: Korea
name: Fatima
role: web
language: TypeScript
commits: yes
country: Other
name: Sara
role: Data
'

For the second code
After finished the first code you need to enter the id,title,type,priority(Critical/High/Medium/Low),reporter,status(Open/In Progress/Resolved).
This would be repeated for 5 times.
For example

' python
id : ISS-001
title : Login crash
type : (Bug/Feature)Bug
priority: (Critical/High/Medium/Low):High
reporter : Minho
status : (Open/In Progress/Resolved): Open
id : ISS-002
title : Dark mode
type : (Bug/Feature)Feature
priority: (Critical/High/Medium/Low):High
reporter : Minho
status : (Open/In Progress/Resolved): Open
id : ISS-003
title : README typo
type : (Bug/Feature)Feature
priority: (Critical/High/Medium/Low):Low
reporter : Jisoo
status : (Open/In Progress/Resolved): Resolved
id : ISS-004
title : Nothing
type : (Bug/Feature)Feature
priority: (Critical/High/Medium/Low):Medium
reporter : Fatima
status : (Open/In Progress/Resolved): In Progress
id : ISS-005
'
For the third,fourth,fifth code
You don't need to do anything to execute. If you followed the upper step.


## Demo
You can start your local demo by:
```
Open the Opensource5.ipynb file and execute it all.
```

## LicenseUsage and License Notices:
This project is released under the MIT License. You are free to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the software, subject to the conditions of the MIT License.

The software is provided "as is", without warranty of any kind, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose, and noninfringement. See the LICENSE file for more details.
