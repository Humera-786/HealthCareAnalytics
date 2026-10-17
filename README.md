# CarePulse Analytics — Healthcare Operations & Patient Insights

## Project Overview

CarePulse Analytics is an interactive healthcare data analytics dashboard designed to analyse medical appointment records and identify patterns in patient attendance. It transforms raw healthcare appointment data into meaningful insights using key performance indicators (KPIs), interactive charts, filters, and automated summaries.

The project uses the Medical Appointment No Shows dataset to explore appointment attendance, missed appointments, patient demographics, SMS reminders, appointment lead times, and neighbourhood-level trends.

## Objectives

* Analyse appointment attendance and no-show rates.
* Identify patterns associated with missed appointments.
* Understand attendance trends across age groups and weekdays.
* Explore the relationship between SMS reminders and appointment attendance.
* Evaluate data quality and identify inconsistencies.
* Support data-driven healthcare operations and appointment management decisions.

## Key Features

* **Interactive Dashboard:** Displays appointment counts, attendance rate, no-show rate, unique patients, and SMS coverage.
* **CSV Dataset Upload:** Loads healthcare appointment data from a CSV file.
* **Interactive Visualisations:** Explores attendance trends, age groups, weekdays, SMS reminders, and neighbourhoods.
* **Advanced Filters:** Filters records by date, gender, age, neighbourhood, SMS status, and appointment outcome.
* **No-Show Pattern Analysis:** Compares no-show rates across different patient and appointment groups.
* **What-If Scenario Simulator:** Estimates hypothetical changes in missed appointments using adjustable assumptions.
* **Data Quality Centre:** Checks for missing information, duplicate appointment IDs, invalid ages, date errors, and unexpected values.
* **Appointment Registry:** Provides searchable and filterable appointment records.
* **Automated Insights:** Highlights notable trends in the uploaded dataset.
* **CSV Export:** Downloads filtered records and analysis summaries.
* **Printable Executive Report:** Allows users to print the dashboard or save it as a PDF.
* **Dark and Light Modes:** Offers a choice of dashboard appearance.
* **Responsive Design:** Supports modern desktop and mobile browsers.

## Dataset

**Dataset name:** Medical Appointment No Shows

**Source:** Kaggle
https://www.kaggle.com/datasets/joniarroba/noshowappointments

**Dataset file:** `KaggleV2-May-2016.csv`

The dataset contains approximately 110,000 medical appointment records and 14 columns. It includes information such as:

* Patient ID and appointment ID
* Gender and age
* Scheduled date and appointment date
* Neighbourhood
* Scholarship information
* Hypertension and diabetes indicators
* Alcoholism and handicap indicators
* SMS reminder status
* Appointment attendance outcome

The `No-show` column indicates whether the patient missed the appointment. A value of `Yes` means the patient did not attend, while `No` means the patient attended.

The dataset contains historical appointment records and does not represent real-time hospital operations.

## Technologies Used

* HTML5
* CSS3
* JavaScript
* Chart.js for interactive charts
* PapaParse for CSV processing
* Browser-based data analysis

## Project Structure

```text
CarePulse-Analytics/
├── index.html
├── KaggleV2-May-2016.csv
└── README.md
```

## How to Run the Project

1. Download the Medical Appointment No Shows dataset from Kaggle.
2. Extract the downloaded ZIP file.
3. Ensure the dataset file is named `KaggleV2-May-2016.csv`.
4. Download or save the CarePulse Analytics website as `index.html`.
5. Place `index.html` and the CSV dataset in the same project folder.
6. Open `index.html` in a modern web browser, such as Google Chrome.
7. Click the dataset upload option and select `KaggleV2-May-2016.csv`.
8. Explore the dashboard, apply filters, review insights, and export reports.

An internet connection is required to load the external charting and CSV-processing libraries.

## Business Value

CarePulse Analytics demonstrates how healthcare appointment data can be converted into useful operational insights. The dashboard can help analysts explore missed-appointment patterns, review reminder coverage, identify groups with higher no-show rates, and support discussions about appointment management strategies.

The analysis identifies associations and trends; it does not establish that a particular factor causes missed appointments.

## Limitations

* The project analyses historical data rather than live hospital records.
* The dataset does not contain hospital departments, waiting times, treatment outcomes, or actual healthcare costs.
* The what-if simulator provides hypothetical estimates and is not a validated predictive model.
* The dashboard is a browser-based analytics prototype, not a production hospital management system.
* The dataset contains sensitive-looking patient-related identifiers. These should not be unnecessarily displayed or shared.

## Privacy and Dataset Licence

The dataset is provided by its original publisher on Kaggle. Review and comply with the dataset's licence and attribution requirements before redistributing it or using it commercially. Avoid publishing patient identifiers or other unnecessary record-level information.

## Conclusion

CarePulse Analytics is a healthcare data analytics portfolio project that combines data exploration, interactive visualisation, data-quality checks, and business-oriented insights in a single dashboard. It demonstrates practical skills in data analysis, JavaScript, CSV processing, dashboard development, and communicating findings to support data-informed decisions.
