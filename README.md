# Job Application Automation

This project automates job applications using **Selenium** and YAML-based resume templates.

## Prerequisites

Before running the script, ensure you have the following installed:

- **Python** (>= 3.x)
- **pip** (Python package manager)

## Setup Instructions

### 1. Clone the Repository

```sh
git clone https://github.com/WhiteboxHub/JobVite-Automaton.git
```

### 2. Create and Activate a Virtual Environment

It is recommended to use a virtual environment to manage dependencies.

#### On Windows:
```sh
python -m venv myvenv
myvenv\Scripts\activate
```

#### On macOS/Linux:
```sh
python3 -m venv myvenv
source myvenv/bin/activate
```

### 3. Install Dependencies

```sh
pip install pyyaml selenium webdriver-manager
```

### 4. Run the Script

```sh
python main.py
```

## Notes

- **WebDriver Setup**: The script uses `webdriver-manager`, so you don't need to manually download WebDriver.
- **Resumes**: Ensure your resumes are formatted using the YAML structure defined in the project.
- **Logging**: Logs are generated for debugging and tracking application status.

## Troubleshooting

- If Selenium fails to launch the browser, ensure your browser (Chrome/Firefox) is updated.
- If using Workday or Jobvite automation, update the script as per the latest website changes.

---


