# Automated ID Card Data Extraction with Power Apps and Power Automate

Optimize your customer registration process with this Power Platform solution, automating the extraction of data from ID cards using Microsoft's AI Builder in conjunction with Power Apps and Power Automate. The extracted customer information is saved to Dataverse as part of the registration process. This pre-built solution simplifies data entry, enhances accuracy, and accelerates processes by intelligently extracting information from various ID documents and auto-filling it into a Power App.

## Features

- **Automated Data Extraction**: Leverages AI Builder's ID Card Reader model to extract information from ID cards, including passports and US driver licenses.
- **Seamless Power Apps Integration**: Auto-fills extracted data into a Power App form, streamlining the data entry process.
- **Efficiency and Accuracy**: Reduces manual entry errors and significantly speeds up customer registration.

## Getting Started

### Prerequisites

Before importing the solution, ensure you have:

- A Microsoft Power Platform environment.
- Access to AI Builder and Power Automate for the automation part.
- A Power Apps subscription for app deployment.

### Importing the Solution

1. **Download the Solution Package**: Start by downloading the .zip file containing the Power Platform solution from this repository.

2. **Import the Solution**:
   - Navigate to the Power Platform Admin Center and select the appropriate environment.
   - Go to `Solutions` and click on `Import`.
   - Choose the downloaded solution package and follow the prompts to import it into your environment.

3. **Configure the Solution**:
   - Ensure the Power Automate flow is linked correctly to your Power App.

### Using the Solution

After importing and configuring the solution:

- Launch the Power App included in the solution to start capturing ID cards.
- Use the app to upload an ID document( a sample license document is present in this repository); the app will display fields auto-filled with the extracted data.
- Review and, if necessary, adjust the extracted information before saving or processing it further.

## Contributing

Your contributions are welcome! If you have suggestions for improvements or encounter any issues, please feel free to fork this repository, make changes, and submit a pull request.

## License

This project is licensed under the MIT License .
