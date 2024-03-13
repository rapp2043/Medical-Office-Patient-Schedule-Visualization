# Medical Office Patient Schedule Visualization

## Description
This project provides a Tableau visualization of a notional patient schedule used by a medical office to manage appointments and notify patients about insurance network changes. The challenge was to visualize patients' next visits aligned with the head of household due to simple sorting and filtering methods not enabling the client to visualize what they needed.

## Data Source
The visualization is based on a notional dataset structured to reflect the original patient scheduling information. All data has been changed and is completely synthetic. 

This dataset includes three variables that were in the original dataset: head of household (HOH, individual patient names (PAT_NAMES), and dates of next visits (NV).

![image](https://github.com/rapp2043/Medical-Office-Patient-Schedule-Visualization/assets/20693928/9d731955-ee51-473d-a2ef-98fb9ae382ae)

## Data Included in This Repository
This repository contains several key components that make up the patient schedule visualization project:

- Tableau Workbook (patient_schedule.twbx): This is the main Tableau workbook file that includes the visualization dashboard. It is interactive and allows for detailed examination of the patient scheduling data in relation to the head of household.

- CSV File (patient_data.csv): This CSV file is the notional dataset from which the Tableau visualization is derived. It includes columns for the head of household, patient name, and dates of the next visits. The dataset has been anonymized and contains no real patient data.

- PowerPoint of the Result (patient_schedule.pptx): A static PowerPoint export of the Tableau visualization result. It provides a quick reference for the visualized data without the need to interact with the Tableau workbook.

The files are intended to provide a comprehensive understanding of the visualization process used to inform patients of their upcoming appointments effectively. They are designed for use within Tableau but can be adapted for similar visualization tools if needed.

Please note that the data included in the CSV file is notional and for illustrative purposes only. It does not contain any real personal or sensitive information.

## Visualizations
I utilized Tableau to create a chart with the dates of the next visit as columns and the head of household and patient names as rows. Patient names are also used in the marks column for color and text, allowing for a clear visual grouping under each head of household and showing their scheduled visits at a glance.

![image](https://github.com/rapp2043/Medical-Office-Patient-Schedule-Visualization/assets/20693928/b1912886-5639-4766-98dd-accc1c261a84)

# Results
## Usage
The visualization was designed to easily identify when patients were due for their next visit. This enabled the medical office staff to proactively send notification letters, informing patients of upcoming appointments and any changes in their insurance network status.

## Notifications
With the help of this chart, the office was able to notify the head of household and reference the dates of other associated patients’ appointments, which helped in drafting more thorough notifications and in planning and making any necessary arrangements.

## Contribution
If you would like to contribute to this project or suggest improvements, please feel free to fork the repository, make your changes, and submit a pull request.

## License
This project is available under for anyone to use. The data used is notional and does not correspond to real patient information.
