# File Upload — Bulk Upload Test Cases

| TC ID | Module | Test Description | Expected Result | Status |
|------|---------|------------------|-----------------|--------|
| TC-011 | Bulk Upload | Upload exactly 3 files simultaneously | Individual progress bars are displayed for all files | Pass |
| TC-012 | Bulk Upload | Upload 4 or more files simultaneously | “Upload in progress” banner appears | Pass |
| TC-013 | Bulk Upload | Upload 10 files simultaneously | All files upload successfully and appear in document list | Pass |
| TC-014 | Bulk Upload | Upload mix of valid and invalid files | Only valid files upload successfully | Pass |
| TC-015 | Bulk Upload | Upload duplicate filenames | System handles duplicates correctly | Pass |