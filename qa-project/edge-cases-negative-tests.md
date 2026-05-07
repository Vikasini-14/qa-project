# Edge Cases & Negative Test Cases

| TC ID | Module | Test Description | Pre-conditions | Test Steps | Expected Result | Status |
|------|---------|------------------|----------------|-------------|-----------------|--------|
| TC-037 | Edge Cases | Verify upload with no internet connection | User is on upload page | 1. Disconnect internet connection 2. Select a valid PDF file 3. Click “Upload” | Network error message is displayed | Pass |
| TC-038 | Edge Cases | Verify validation when no file is selected | User is on upload page | 1. Click “Upload” without selecting any file | Validation message appears asking user to select a file | Pass |
| TC-039 | Edge Cases | Verify rapid multiple upload clicks do not create duplicates | User is on upload page | 1. Select a valid PDF file 2. Rapidly click “Upload” button multiple times | Duplicate uploads do not occur | Pass |
| TC-040 | Edge Cases | Verify upload with special characters in filename | User is on upload page | 1. Rename file with special characters 2. Upload the file | File uploads successfully and filename is handled correctly | Pass |
| TC-041 | Edge Cases | Verify application responsiveness on multiple screen sizes | User opens application | 1. Open application at 375px width 2. Open at 768px width 3. Open at 1280px width | Application layout displays correctly without UI issues on all screen sizes | Pass |