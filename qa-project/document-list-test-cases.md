# Document List Test Cases

| TC ID | Module | Test Description | Pre-conditions | Test Steps | Expected Result | Status |
|------|---------|------------------|----------------|-------------|-----------------|--------|
| TC-032 | Document List | Verify uploaded file appears in document list | User is on upload page | 1. Upload a valid PDF file 2. Open document list | Uploaded file appears with correct name, size, and upload date | Pass |
| TC-033 | Document List | Verify document download functionality | Uploaded document exists in list | 1. Click “Download” for a document | Selected document downloads successfully | Pass |
| TC-034 | Document List | Verify document delete functionality | Uploaded document exists in list | 1. Click “Delete” for a document | Document is removed from document list | Pass |
| TC-035 | Document List | Verify empty document list behavior | No documents uploaded | 1. Open document list page | Empty state message or blank list is displayed | Pass |
| TC-036 | Document List | Verify document list UI with 10 uploaded files | User uploads multiple documents | 1. Upload 10 PDF files 2. Open document list | All files appear correctly without UI overlap or cutoff | Pass |