# IoT Anomaly Detection with Bolt and Python

This project demonstrates how to implement anomaly detection for Internet of Things (IoT) sensor data using the Bolt IoT platform and Python. Anomaly detection is a crucial aspect of IoT applications, helping to identify unusual patterns or events in sensor readings.

## Overview

The project utilizes the Bolt IoT platform, which provides hardware modules for collecting sensor data and cloud services for data analysis and communication. Python is used to develop the anomaly detection algorithm and interface with Bolt's APIs.

## Features

- **Anomaly Detection Algorithm**: Implements a Z-score based anomaly detection algorithm to identify significant deviations in sensor readings.

- **Integration with Bolt IoT**: Utilizes the Bolt Cloud API to interact with Bolt hardware modules, collect sensor data, and trigger alerts.

- **Twilio Integration**: Sends SMS alerts using Twilio API when anomalies are detected, providing real-time notifications to stakeholders.

## Setup

To run this project, follow these steps:

1. Clone the repository to your local machine.
2. Install the required Python dependencies listed in `requirements.txt`.
3. Update the `conf.py` file with your Bolt API key, device ID, Twilio credentials, and other configuration settings.
4. Connect your Bolt device with the appropriate sensors (e.g., light sensor, temperature sensor).
5. Run the Python script `anomaly_detection.py` to start monitoring sensor readings and detect anomalies.

## Usage

- **Monitor Sensor Readings**: The `anomaly_detection.py` script continuously collects sensor readings and analyzes them for anomalies.
  
- **Receive Alerts**: If significant deviations from normal patterns are detected, the script triggers alerts via SMS using the Twilio API.

## Contributions

Contributions to this project are welcome! If you have any suggestions, bug reports, or feature requests, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

---

Feel free to customize and extend this project according to your requirements. Happy coding!
