# EL_Task_1

I have chosen Medical Appointment No Shows data from kaggle.
📥 Dataset Loading
The dataset was successfully loaded into a pandas DataFrame for further processing and analysis.
🔍 Missing Values and Shape Inspection
The dataset was checked for null values across all columns. The overall shape of the dataset, including the number of rows and columns, was verified. A column-wise count of missing values was performed to ensure data completeness.
No missing data found
🧹 Duplicate Removal
Duplicate rows were identified and removed from the dataset to prevent redundancy and maintain data integrity.
No duplicates found.

🕒 Date Format Conversion
The ScheduledDay and AppointmentDay columns were originally in ISO 8601 format (YYYY-MM-DDTHH:MM:SSZ). These were reformatted to a more human-readable format: DD-MM-YYTHH:MM:SSZ. Only the date portion was modified while keeping the time and other components intact.
Finally saved the data.
