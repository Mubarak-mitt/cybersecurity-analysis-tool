\# Cybersecurity Log Analysis Tool



\## Overview



The Cybersecurity Log Analysis Tool is a Python-based application that analyzes log files to identify potential security incidents. It scans log entries for suspicious events such as failed login attempts, unauthorized access, warnings, and errors, then displays the findings along with a summary of detected incidents.



This project demonstrates basic security log analysis while following software development best practices, including version control with GitHub and issue tracking with Freshworks.



\## Features



\* Analyzes log files for security-related events.

\* Detects \*\*ERROR\*\* log entries.

\* Detects \*\*WARNING\*\* log entries.

\* Identifies failed login attempts.

\* Detects unauthorized access events.

\* Generates a summary of detected incidents.

\* Simple, lightweight, and easy to extend.



\## Requirements



\* Python 3.8 or later

\* Git (for version control)



No external Python libraries are required because the script uses only Python's standard library.



\## Installation



1\. Clone the repository:



```bash

git clone https://github.com/yourusername/cybersecurity-analysis-tool.git

```



2\. Navigate to the project folder:



```bash

cd cybersecurity-analysis-tool

```



\## Running the Script



Move into the source directory:



```bash

cd src

```



Run the script:



```bash

python log\_analyzer.py

```



The script reads the sample log file located in the `logs` directory and displays any detected security events, followed by a summary.



\## Sample Output



```

==================================================

Security Log Analysis

==================================================



\[Medium] WARNING Failed login attempt: admin

\[High] ERROR Database connection failed

\[Medium] WARNING Failed login attempt: root

\[High] ERROR Unauthorized access detected



Summary

\------------------------------

WARNING: 2

Failed login: 2

ERROR: 2

Unauthorized: 1



Analysis Complete.

```



\## Technologies Used



\* Python 3

\* Git

\* GitHub

\* Freshworks



\## Future Improvements



\* Export reports to CSV or PDF.

\* Detect brute-force login attacks.

\* Detect suspicious IP addresses.

\* Add command-line arguments.

\* Support multiple log file formats.

\* Generate detailed incident reports.



\## Version Control



GitHub is used to manage source code through feature branches and descriptive commit messages. Development is performed in feature branches before being merged into the development and main branches.



\## Issue Tracking



Freshworks is used to record bugs, feature requests, and enhancements throughout the development process.



\## Author



\*\*Mubarak Sikiru\*\*



\## License



This project is intended for educational purposes.



