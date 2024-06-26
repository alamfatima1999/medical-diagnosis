## Application of Deep learning based NLP Techniques for design of medical diagnosis systems from complaint text using FastText encoding.

Added python script & trained model.
For dataset please reach me out on alamfatima1999@gmail.com

# Problem Statement
In a large hospital there are numerous departments and doctors specialising on their own. In such a situation there has to be a more generalised way to predict diseases based on the patient’s plea. In this prediction method, the goal is to link the patient’s complaint to possible diagnosis that a doctor would suggest regardless of depending to which field it belongs to. Sometimes it is unable to find out what exactly is the root cause of the problem and the patient might spend ranging from a week to a month or two to find out the exact cause. This is where this prediction model comes into picture whose ultimate aim is to give top predictions so that a patient’s time and effort is saved and quality healthcare is provided within a short time frame.

# Objective
• To achieve sufficient accuracy to predict top -K diseases.
• The proposed solution should be robust and immune to the outliers and the noise data.
• It should work for the large no. of output classes (presently - 11532) present in the data.
• It should be extendable to any new output classes(here disease) that might add on in future.
• In near future, the data is expected to increase 4-fold and so the proposed solution should be scalable to the future data

# A Brief Overview
The data available in raw form consists of 7 columns: 

RCH_PIN: This column represents the unique Personal Identification Number (PIN) associated with each patient. It serves as an identifier for individuals in the dataset.

RCH_CVRNO: The RCH_CVRNO column contains the Centralized Virtual Registry (CVR) number assigned to each patient by the hospital. It is a unique identifier specific to the hospital’s records.

CREATEDON: The CREATEDON column denotes the date when the record was created or entered into the system. It provides information about the timing of thepatient’s visit or interaction with the hospital.

SPED_COMLTEXT: This column contains text data describing the patient’s medical complaint or symptom. It may include information about the location, duration, or nature of the symptoms.

SPDD_ICDCODE: The SPDD_ICDCODE column represents the ICD (International Classification of Diseases) code associated with the patient’s condition. The ICD code is a standardized system used for classifying and coding diagnoses andmedical conditions.

DESCRIPTION: The DESCRIPTION column provides a textual description or name corresponding to the ICD code. It describes the medical condition or diagnosisassociated with the patient’s record.

SPDD_TYPE: The SPDD_TYPE column indicates the type or category of the medical condition. It may provide additional information about the classification or nature of the condition. Each row in the dataset represents a single patient’s record, capturing information about their PIN, CVR number, creation date, medical complaint, ICD code, de-scription, and condition type. The data is structured in a tabular format, with eachcolumn holding specific information related to the patient’s medical history and visit
to the hospital.


# Data Structure of Sample Data
![data](https://github.com/alamfatima1999/medical-diagnosis/assets/71816449/a8c4b989-ea96-4f35-ad0a-b90d6bd87d43)

# Data Treatement Flow
![Data treatment flow](https://github.com/alamfatima1999/medical-diagnosis/assets/71816449/127f044e-d4c7-4f2b-a5df-6f411feb1fb6)


# Fastext Model
![Model-architecture-of-fastText-where-L-in-L1-represents-layer-and-O-in-O1-operation](https://github.com/alamfatima1999/medical-diagnosis/assets/71816449/74febd24-1923-4304-ae83-c3a09b6629c2)


# CDSSM Model Architecture
![CDSSM Architecture](https://github.com/alamfatima1999/medical-diagnosis/assets/71816449/01ce2472-fce8-47b3-a2c9-91d0a7a63435)


# Flow of NLP Project
![Flow of NLP Project drawio](https://github.com/alamfatima1999/medical-diagnosis/assets/71816449/22de6f91-4cae-4fe9-960e-02d71f86a4f0)







