# Send Bulk Guest User to Join a Teams Meeting

## Overview
* This python script will allow you to open multiple chrome window and join the meeting with multiple guest usernames at same time. This also makes camera off and mic muted by default.

## Installation Guide
* Pull the script to your local environment ```git clone https://github.com/CraftyPythonDeveloper/bulk-teams-meeting-join.git```
* Install requirements ```pip install -r requirements.txt```

## Script Running Guide
* Add the list of usernames in usernames.txt file
* Add the meeting url in meeting_url.txt file
* Add the meeting exit time in minutes, so that users can exit the meeting, in meeting_exit_time_in_minutes.txt file.
* Once Done Run the script by running ```python main.py```