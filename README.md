# Send Bulk Guest User to Join a Teams Meeting

## Overview
* This python script will allow you to open multiple chrome window and join the meeting with multiple guest usernames at same time. This also makes camera off and mic muted by default.


## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Support](#support)
- [Contributing](#contributing)

## Installation

* Make sure python is installed and accessible through terminal/cmd by typing ```python --version``` or ```python3 --version```
* (Optional step) Create virtual environment by following tutorial on [How to install virtual environment](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/)
* Clone the repo locally using ```git clone https://github.com/CraftyPythonDeveloper/bulk-teams-meeting-join.git```
* Install requirements ```pip install -r requirements.txt```

## Usage

To run the script follow the below mentioned steps:

* Add the list of usernames in usernames.txt file
* Add the meeting url in meeting_url.txt file
* Add the meeting exit time in minutes, so that users can exit the meeting, in meeting_exit_time_in_minutes.txt file.
* Once Done Run the script by running ```python main.py```

## Support

- If you face any issue or bug, you can create an issue describing the error message and steps to reproduce the same error, with log file attached.

Please [open an issue](https://github.com/CraftyPythonDeveloper/bulk-teams-meeting-join/issues/new) for support.

## Contributing

Please contribute by create a branch, add commits, and [open a pull request](https://github.com/CraftyPythonDeveloper/bulk-teams-meeting-join/pulls).
