[![build and deploy Speckle functions](https://github.com/specklesystems/speckle_automate-data_sanitizer_demo/actions/workflows/main.yml/badge.svg)](https://github.com/specklesystems/speckle_automate-data_sanitizer_demo/actions/workflows/main.yml)

# Speckle Automate Function: Data Sanitizer

## Overview
The Speckle Automate Data Sanitizer function is a conceptual demonstration designed for the AEC industry. It showcases the potential of leveraging Speckle's capabilities for automated detection and sanitization of sensitive data within project version commits.

## ⚠️ Disclaimer: Conceptual Demonstration Only
**IMPORTANT: This function is a theoretical model and not a functional implementation. It is intended to exhibit the possibilities of data sanitization within Speckle Automate, emphasizing the importance of privacy and data integrity in collaborative environments.**

<img width="850" alt="image" src="https://github.com/specklesystems/speckle_automate-data_sanitizer_demo/assets/760691/e1bb3aea-66f6-45f2-b938-8eb7c7a9765e">

## Value of the Data Sanitizer
In the realm of AEC project management, handling sensitive data such as private client details, confidential design elements, or proprietary information is a significant challenge. The Data Sanitizer function aims to address these challenges by:
- **Enhancing Data Privacy:** Automatically filtering out sensitive information from shared project data.
- **Maintaining Data Integrity:** Ensuring that the cleansing process preserves the usefulness and accuracy of the data.
- **Streamlining Compliance:** Assisting in adhering to privacy laws and regulations within the AEC industry.
- **Boosting Collaborative Confidence:** Enhancing trust among project stakeholders through responsible data handling.

### How It Works
The function employs Speckle's data traversal capabilities to scrutinize data within a version commit. It uses predefined rules to identify sensitive information and filters it out, sharing only pertinent, non-sensitive data.

<img width="580" alt="image" src="https://github.com/specklesystems/speckle_automate-data_sanitizer_demo/assets/760691/42b3ce4f-4fd7-4f34-97ed-81c17273ddd0">

### Key Components
- **Automated Data Scrubbing:** Detects and sanitizes private data in near real-time.
- **Customizable Ruleset:** Adaptable to various definitions of sensitive information.
- **In-Depth Data Processing:** Meticulously processes data to balance privacy with data utility.

### Function Logic
The main function body includes stages like initial checks, data reception and traversal, rule application, data sanitization, and post-processing to generate sanitized data versions and detailed reports.



## Using this Speckle Function

1. **Create a New Speckle Automation**: Navigate to the Speckle dashboard.

2. **Select the Speckle Project & Model**: Choose the relevant project and model.

3. **Select the Function**: Opt for the function named "Data Validation in AEC."

4. **Configure & Create**: Adjust settings as needed and click "Create Automation."

## Develop Your Own Speckle Function

1. **Fork & Clone**: Fork this repository and clone it or use GitHub CodeSpaces.

2. **Function Registration**: After registration, save the Function Publish Token and ID as GitHub Action Secrets.

3. **Edit**: Make modifications in `main.py`.

4. **Automatic Versioning**: Every commit to the main branch auto-creates a new version.

## Developer Setup

- **Requirements**: Install Python 3 and Poetry. Run `poetry shell && poetry install` for required packages.

- **Building & Testing**: Test locally using `poetry run pytest`. Also, package the code as a Docker Container Image for
  Speckle Automate.

## Resources

- **SpecklePy**: Dive deeper into `SpecklePy` and harness the power of Speckle from Python.
