# Power BI Integration with Jupyter Notebook

This project demonstrates how to connect Jupyter Notebook to Power BI using Python. It includes functionality to create a Pandas dataframe from data retrieved from a visual on a Power BI report page. The following steps outline the process:

## Table of Contents
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Packages](#packages)
- [PBI Login Authentication](#pbi-login-authentication)
- [Choosing the Report](#choosing-the-report)
- [Getting all Report Pages](#getting-all-report-pages)
- [Creating a DataFrame from a Visual](#creating-a-dataframe-from-a-visual)

## Prerequisites

- Python 3.x
- Jupyter Notebook
- Power BI account

## Installation

1. Clone or download this repository to your local machine.

   ```bash
   git clone https://github.com/A-Kilany/Python_for_BI.git

## Packages

The required Python packages need to be installed beofre they are imported to enable the integration between Jupyter Notebook and Power BI.

powerbiclient
io
pandas

## PBI Login Authentication
The authentication process is initiated to establish a connection between Jupyter Notebook and Power BI. This is essential so that Power BI allows access for the following steps.
I added an alternative authentication method that is slightly longer (it requires a PIN). Either method should work just fine. If one does not work, feel free to try out the other. If you would like to expand on this project and build an embedding environment, you might need the access token from Power BI's REST API, in which case I would recommend using the second authentication method for trying things out, since it includes a function to fetch the current access token.

## Choosing the Report
Specify the group ID and report ID for the Power BI report you want to connect to. These IDs can be obtained from the URL of the report.

## Getting all Report Pages
Retrieve information about the report's pages, including both visible and hidden pages.
To retrieve visuals from a specific page, replace <page name> in the code below with the actual page name.

## Creating a DataFrame from a Visual
Export the data from a visual of your choice and create a Pandas DataFrame using the exported data.
Make sure to replace <page name> and <visual name> with the respective names obtained from the previous steps.


## Feel free to explore and modify the code to suit your specific requirements and Power BI integration needs.


# SUMMARY:

This README.md file provides an overview of the project, outlines the necessary steps, and provides code snippets to demonstrate the integration between Jupyter Notebook and Power BI. It serves as a guide for users to understand and utilize the capabilities of the project effectively.
Please make sure to replace `<Your report's workspace ID>`, `<Your report's ID>`, `<page name>`, and `<visual name>` with the relevant values specific to your Power BI report.
Remember to also update the appropriate sections of the README with any additional information, usage instructions, or project-specific details that may be helpful for users.
If you have any questions or need further assistance, please don't hesitate to reach out to me via contact details below. Enjoy integrating Jupyter Notebook with Power BI!

Author: Ahmed Kilany
GitHub: A-Kilany
LinkedIn: ahmed--kilany
