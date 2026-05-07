# Document List Test Cases

| TC ID | Module | Test Description | Pre-conditions | Test Steps | Expected Result | Status |
|------|---------|------------------|----------------|-------------|-----------------|--------|
| TC-032 | Document List | Verify uploaded file appears in document list | User is on upload page | 1. Upload a valid PDF file 2. Open document list | Uploaded file appears with correct file name, file size, and upload date | Pass |
| TC-033 | Document List | Verify document download functionality | Uploaded document exists in document list | 1. Click “Download” option for a document | Selected document downloads successfully without corruption | Pass |
| TC-034 | Document List | Verify document delete functionality | Uploaded document exists in document list | 1. Click “Delete” option for a document | Document is removed successfully from document list | Pass |
| TC-035 | Document List | Verify empty document list behavior | No documents uploaded | 1. Open document list page | Empty list message or no records message is displayed | Pass |
| TC-036 | Document List | Verify UI behavior with 10 uploaded documents | User is on upload page | 1. Upload 10 valid PDF files 2. Open document list | All uploaded documents appear correctly without UI overlap or cutoff | Pass |