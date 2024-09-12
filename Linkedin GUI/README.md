# LinkedIn Outreach Helper GUI

This project is a GUI application designed to help automate LinkedIn outreach efforts. It provides features to load CSV files, process user information, and manage LinkedIn contact outreach.

## Requirements

- Python 3.12.4 or higher
- The following Python libraries:
  - `attrs==24.2.0`
  - `certifi==2024.7.4`
  - `h11==0.14.0`
  - `idna==3.7`
  - `numpy==2.0.1`
  - `outcome==1.3.0.post0`
  - `pandas==2.2.2`
  - `pyperclip==1.9.0`
  - `PySocks==1.7.1`
  - `python-dateutil==2.9.0.post0`
  - `pytz==2024.1`
  - `selenium==4.23.1`
  - `setuptools==72.1.0`
  - `six==1.16.0`
  - `sniffio==1.3.1`
  - `sortedcontainers==2.4.0`
  - `trio==0.26.2`
  - `trio-websocket==0.11.1`
  - `typing_extensions==4.12.2`
  - `tzdata==2024.1`
  - `urllib3==2.2.2`
  - `websocket-client==1.8.0`
  - `wheel==0.43.0`
  - `wsproto==1.2.0`

Make sure you have `python-3.12.4-macos11.pkg` installed if you're running this on macOS.

## Setup Instructions

### 1. Download the Project Files

1. Download the `linkedin-bot.zip` file from the source.
2. Unzip the `linkedin-bot.zip` file.
3. Navigate to the project folder, which should now be located in `~/Downloads/linkedin-bot` by default.

### 2. Install Python (if necessary)

Before proceeding, ensure that Python 3.12.4 is installed. The `run.sh` script will automatically check for Python and install it if necessary.

### 3. Running the Application

Open the terminal, then navigate to the `linkedin-bot` directory:

```bash
cd ~/Downloads/linkedin-bot

Alternatively, use the correct path if the directory is saved elsewhere on your system.

### 4. Executing the run.sh Script

Once inside the project directory, run the run.sh script:

```bash
sh run.sh
```

The script will do the following:

	•	Check if Python 3.12 is installed. If not, it will install Python 3.12.
	
	•	Create a virtual environment in the venv folder.
	
	•	Install all required dependencies from the requirements.txt file.
	
	•	Launch the LinkedIn Outreach Helper GUI.

5. Using the Application

After running run.sh, the LinkedIn Outreach Helper GUI will open. Follow these steps to use it:
	•	Load CSV: Click the Load CSV button to load a CSV file containing LinkedIn user data.
	
	•	Settings: Click the Settings button to customize outreach templates and set your LinkedIn credentials.
	
	•	Open Profile: Open a LinkedIn profile and copy a message to the clipboard.
	
	•	Mark as Sent: Mark profiles as contacted.
	
	•	Hide Messaged Connections: Run a filter to hide LinkedIn contacts who have already been messaged.
	
	•	Refresh Recently Contacted: Refresh the list of recently messaged contacts.
	
	
	
	
	