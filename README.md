# RMS-Automation-Suite
**Description:** A suite of Tampermonkey scripts designed to streamline and automate data entry and navigation processes on RMS web pages.

## Table of Contents

- [Overview](#overview)
- [Installation](#installation)
- [Scripts and Usage](#scripts-and-usage)
  - [COMM115](#comm115)
  - [RMS Shortcuts](#rms-shortcuts)
  - [Open Tabs and Fill Barcodes](#open-tabs-and-fill-barcodes)
- [Contributing](#contributing)
- [License](#license)

## Overview

This project consists of three Tampermonkey scripts that together automate various tasks on the RMS web platform. These scripts facilitate data extraction, automate form completion, and provide keyboard shortcuts for navigation.

## Installation

1. **Install Tampermonkey:**
   - Visit the [Tampermonkey website](https://www.tampermonkey.net/) and install the extension for your browser.

2. **Add Scripts:**
   - Open Tampermonkey in your browser.
   - For each script below, click on "Add a new script" and copy-paste the script code into the editor.
   - Save each script.

## Scripts and Usage

### COMM115

**Description:** Automates form actions, data extraction, and validation on a specific RMS page.

- **Target Page:** `https://rms.pason.com/pages/Components/ComponentAdd.aspx?componentTemplate=*`
- **Functions:**
  - Autofocuses on the input box.
  - Validates input as an 8-digit number starting with zero.
  - Fetches data via an API and fills form fields if valid data is found.
  - Selects "Canada" in dropdowns and focuses on the submit button.

### RMS Shortcuts

**Description:** Provides keyboard shortcuts for the RMS Asset Detail page to enhance user navigation.

- **Target Page:** `https://rms.pason.com/Pages/Components/ComponentDetails.aspx?id=*`
- **Shortcuts:**
  - Press "E" to click the "Update" button.
  - Press "C" to click the "Create Similar" button.
  - Press "D" to focus on the barcode input box.
- **Usage:** Shortcuts work when focus is not on any input element.

### Open Tabs and Fill Barcodes

**Description:** Allows opening multiple tabs with barcodes filled automatically.

- **Target Page:** `https://rms.pason.com/*`
- **Functionality:**
  - Adds a button next to the "Choose Barcodes" button for batch processing.
  - On click, opens new tabs with barcodes entered in a text box.
  - Automatically fills the barcode input on child pages.
- **Usage:** Enter barcodes in the provided text area, then click the "Add Multiple in Tab" button to open new tabs.

## Contributing

Contributions are welcome! If you have suggestions or improvements, feel free to fork the repository and submit a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
