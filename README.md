# AI-Powered-Contract-Auditing-System
This is an ongoing project and the requirements are listed below. Updates will be made to this document as the project progresses.

[🟧: Development Pending]

[☑️: Development In Progress]

[✅: Development Completed]

## Key Requirements:
✅ Data Gathering and/or generation

✅ Optical Character Recognition (OCR) to extract text from scanned contracts (Using Tesseract)

☑️ Text Localisation and Detection

☑️ Signature Field Detection – Identify words like "Signed by," "Signature," "Authorized Representative," and determine if a signature is present

🟧 Handwritten Signature Detection – Use AI or pattern recognition to identify if a contract has a handwritten signature

🟧 Digital Signature Validation – If a contract is e-signed (DocuSign, Adobe Sign), verify if all required signers have signed

🟧 Compare Against Expected Signers – Cross-check signers with a predefined list and flag missing signatures

🟧 Automated Notifications – Send email or Slack alerts if a contract is missing signatures

🟧 Integration – Connect with Google Drive, OneDrive, Dropbox, DocuSign, or SharePoint to fetch and audit contracts

🟧 User-Friendly Dashboard – A web-based or Excel-based reporting tool to track audits and flagged contracts



## Datasets
The following datasets have been used for training and testing this system.
### 1. SignverOD: https://www.kaggle.com/datasets/victordibia/signverod?resource=download-directory
#### Citations

@article{
DibiaReed2022signverod, author = {Victor, Dibia},
title = {A Dataset for Handwritten Signature ObjectDetection in Scanned Documents.},
year = {2022},
publisher = {victordibia.com},
journal = {victordibia.com},
url = {https://victordibia.com/signverod.pdf}
}

@article{
Dibia2022signver,
author = {Victor, Dibia and Andrew Reed},
title = {SignVer: A Deep Learning Library for Automatic Offline Signature Verification Tasks},
year = {2022},
publisher = {victordibia.com},
journal = {victordibia.com},
url = {https://victordibia.com/signver.pdf}
}
