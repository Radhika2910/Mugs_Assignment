# Mugs_Assignment
Dealing with the MIMIC-IV FHIR dataset for the purpose of this assignment.
As part of my work, I had the opportunity to engage with the MIMIC-IV FHIR dataset, a comprehensive collection of healthcare data in FHIR (Fast Healthcare Interoperability Resources) format. This dataset encompasses various FHIR resources representing critical aspects of a hospital system, including patients, conditions, and encounters. Among the key files provided were Patient.ndjson, Condition.ndjson, Encounter.ndjson, and EncounterICU.ndjson.

The primary objective of my assignment was to process these files to achieve the following tasks:

a) Gain familiarity with the JSON object format within each of the four files.
b) Develop a script to organize conditions associated with each patient into arrays.
c) Assign estimated timestamps for each condition by correlating them with the corresponding encounters.
d) Generate a CSV file featuring columns for patient ID, timestamp, condition code, and condition description.
e) As part of the assignment requirements, I was tasked with submitting both the CSV file and the Jupyter notebook utilized for processing the dataset.

Readme:
MIMIC-IV FHIR Dataset Assignment
During my tenure, I undertook the MIMIC-IV FHIR dataset assignment, collaborating closely with the provided data files to fulfill the project objectives. The assignment involved:

Processing patient, condition, and encounter data stored in FHIR format.
Implementing a Python script to organize conditions associated with each patient.
Establishing a mechanism to assign estimated timestamps to each condition based on related encounters.
Producing a CSV file containing pertinent patient information and condition details.

Files Included:
patient.ndjson: Dataset file containing patient data in FHIR format.
condition.ndjson: Dataset file containing condition data in FHIR format.
encounter.ndjson: Dataset file containing encounter data in FHIR format.
encounterICU.ndjson: Dataset file containing ICU encounter data in FHIR format.
assignment.ipynb: Jupyter notebook containing the code used for processing the dataset and generating the CSV file.
patient_conditions.csv: The output CSV file featuring patient information, condition timestamps, and associated details.

Upon execution, the output CSV file (patient_conditions.csv) will be created in the same directory.
The CSV file and the Jupyter notebook (assignment.ipynb) is the final deliverables.
