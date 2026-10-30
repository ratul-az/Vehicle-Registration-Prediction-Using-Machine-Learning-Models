# Dataset Information

## Required file

The notebook expects a CSV file named:

`cleaned_registrations.csv`

## Dataset availability

The CSV file was not included with the notebook uploaded for documentation. The notebook itself does not provide a verifiable original dataset URL, publisher or licence. Therefore, no replacement source is claimed here.

If you have the original CSV, add it to your private Colab session or local working directory when running the notebook. Before publishing any dataset, confirm that you have permission to redistribute it and document its original source.

## Expected fields

The main XGBoost regression section uses `registrations` as the target. Its summary identifies these inputs:

- Month
- Year
- Day
- Vehicle Type
- Fuel Type

Other notebook sections refer to `fuel` as a classification target and use their own data preparation steps. Check the actual CSV column names against each section before execution.

## File paths in the notebook

Different cells load the same filename using different relative paths:

- `cleaned_registrations.csv`
- `/content/cleaned_registrations.csv`

For Google Colab, upload the CSV to `/content/` or update the relevant cell paths consistently. For local execution, place it in the notebook's working directory or adjust the paths.
