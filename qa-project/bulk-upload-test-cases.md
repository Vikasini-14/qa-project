# File Upload — Bulk Upload Test Cases

| TC ID | Module | Test Description | Pre-conditions | Test Steps | Expected Result | Status |
|------|---------|------------------|----------------|-------------|-----------------|--------|
| TC-011 | Bulk Upload | Upload exactly 3 files simultaneously | User is on upload page | 1. Click “Select Files” 2. Select 3 valid PDF files 3. Click “Upload” | Individual progress bars are shown for each file and upload completes successfully | Pass |
| TC-012 | Bulk Upload | Upload 4 or more files simultaneously | User is on upload page | 1. Click “Select Files” 2. Select 4 valid PDF files 3. Click “Upload” | “Upload in progress” banner appears and files upload successfully | Pass |
| TC-013 | Bulk Upload | Upload 10 files | User is on upload page | 1. Click “Select Files” 2. Select 10 valid PDF files 3. Click “Upload” | All files complete upload and appear in document list | Pass |
| TC-014 | Bulk Upload | Upload mix of valid and invalid files in bulk | User is on upload page | 1. Click “Select Files” 2. Select PDF and PNG/DOCX files together 3. Click “Upload” | Valid PDF files upload successfully and invalid files display error message | Pass |
| TC-015 | Bulk Upload | Upload duplicate filenames | User is on upload page | 1. Select two files with same filename 2. Click “Upload” | System handles duplicate files correctly by rejecting or renaming duplicates | Pass |