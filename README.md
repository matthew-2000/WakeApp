# WakeApp - Depression Monitoring System

![WakeApp Logo](https://github.com/matthew-2000/WakeApp/blob/main/assets/icons/icona.png)

**Table of Contents**
- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Contact](#contact)
- [Project Status](#project-status)
- [Acknowledgments](#acknowledgments)

## Description

WakeApp is a system designed to assist individuals suffering from major depression. Its primary objectives are:

- To aid in the early diagnosis of the condition as symptoms manifest.
- To assist healthcare professionals in monitoring and managing patients.
- To leverage environmental and physical data for more precise diagnosis.

The system functions as a platform that facilitates communication among various devices to provide accurate, real-time data analysis. Communication occurs between different devices, including:

- Wearables
- IoT Devices
- AI Tools

The system's mood monitoring operates as follows:

- The system sends two daily notifications to which the patient responds by recording a 120-second video describing their mood.
  - Patient feedback on their perceived mood.
  - The video reveals the actual mood, while the feedback indicates the perceived mood.
- Additionally, twice a week, the system sends text prompts for the patient to read aloud, recording the audio in the app.
  - Patient feedback on their perceived mood.
  - The audio reveals the real mood, while the feedback indicates the perceived mood.

Furthermore, there is a multi-platform dashboard available to healthcare professionals, where all data collected from the patients' applications is displayed. The doctor will have access to data and analyses conducted by AI at any time for all their patients.

## Installation

To install WakeApp, follow these steps:

1. Clone the GitHub repository: `git clone https://github.com/your-username/WakeApp.git`
2. Navigate to the project directory: `cd WakeApp`
3. Install Flutter for the mobile application.
4. Set up the [Flask server](server_python) for handling notifications and data analysis.

## License

WakeApp is licensed under the [MIT License](link_to_license).

## Acknowledgments

We would like to thank the open-source community and the following libraries and frameworks that have contributed to the development of WakeApp:

- Flutter: [Flutter](https://flutter.dev)
- Flask: [Flask](https://flask.palletsprojects.com)
