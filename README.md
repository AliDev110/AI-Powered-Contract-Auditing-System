# AI-Powered-Contract-Auditing-System
This is an ongoing project and the requirements are listed below. Updates will be made to this document as the project progresses.

[✅: Development to be started]
[☑️: Development in progress]

## Key Requirements:
☑️ Optical Character Recognition (OCR) to extract text from scanned contracts (Tesseract, Google Vision AI, Amazon Textract)

✅ Signature Field Detection – Identify words like "Signed by," "Signature," "Authorized Representative," and determine if a signature is present

✅ Handwritten Signature Detection – Use AI or pattern recognition to identify if a contract has a handwritten signature

✅ Digital Signature Validation – If a contract is e-signed (DocuSign, Adobe Sign), verify if all required signers have signed

✅ Compare Against Expected Signers – Cross-check signers with a predefined list and flag missing signatures

✅ Automated Notifications – Send email or Slack alerts if a contract is missing signatures

✅ Integration – Connect with Google Drive, OneDrive, Dropbox, DocuSign, or SharePoint to fetch and audit contracts

✅ User-Friendly Dashboard – A web-based or Excel-based reporting tool to track audits and flagged contracts
