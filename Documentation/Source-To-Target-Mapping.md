# Source to Target Mapping (STM)

| Source Column | Description       | FHIR Resource | FHIR Element |
|---------------|------------------|---------------|--------------|
| patient_id    | Legacy ID         | Patient       | Patient.id   |
| name          | Full name         | Patient       | Patient.name.text |
| birthDate     | Date of birth     | Patient       | Patient.birthDate |
| gender        | Gender of patient | Patient       | Patient.gender |
