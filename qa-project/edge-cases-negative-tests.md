# Edge Cases & Negative Test Cases

| TC ID | Module | Test Description | Pre-conditions | Test Steps | Expected Result | Status |
|------|---------|------------------|----------------|-------------|-----------------|--------|
| TC-037 | Edge Cases | Verify upload behavior with no internet connection | User is on upload page | 1. Disconnect internet connection 2. Attempt file upload | Network error message is displayed | Pass |
| TC-038 | Edge Cases | Verify validation when uploading without selecting file | User is on upload page | 1. Click “Upload” without selecting file | Validation message is displayed asking user to select file | Pass |
| TC-039 | Edge Cases | Verify rapid multiple upload button clicks | User is on upload page | 1. Select valid PDF file 2. Rapidly click “Upload” button multiple times | Duplicate uploads are prevented | Pass |
| TC-040 | Edge Cases | Verify upload with special characters in filename | User is on upload page | 1. Rename file with special characters 2. Upload file | File uploads successfully without errors | Pass |
| TC-041 | Edge Cases | Verify application responsiveness on multiple screen sizes | User opens application | 1. Open application in 375px mobile view 2. Open in 768px tablet view 3. Open in 1280px desktop view | Application layout adjusts properly without UI issues | Pass |