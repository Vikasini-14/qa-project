# Upload Progress Test Cases

| TC ID | Module | Test Description | Pre-conditions | Test Steps | Expected Result | Status |
|------|---------|------------------|----------------|-------------|-----------------|--------|
| TC-016 | Upload Progress | Verify progress bar is visible during upload | User is on upload page | 1. Click “Select File” 2. Choose a valid PDF file 3. Click “Upload” | Progress bar is displayed while the file uploads | Pass |
| TC-017 | Upload Progress | Verify progress percentage updates in real time | User is on upload page | 1. Select a large PDF file 2. Click “Upload” 3. Observe upload percentage | Upload percentage updates continuously until upload completes | Pass |
| TC-018 | Upload Progress | Verify status changes from “uploading” to “complete” | User is on upload page | 1. Upload a valid PDF file 2. Wait for upload completion | Status label changes from “uploading” to “complete” after upload finishes | Pass |
| TC-019 | Upload Progress | Verify progress bar updates during slow network | User is on upload page | 1. Simulate slow internet connection 2. Upload a PDF file 3. Observe progress bar | Progress bar continues updating and does not freeze during upload | Pass |
| TC-020 | Upload Progress | Verify failed upload shows error message | User is on upload page | 1. Disconnect internet connection 2. Attempt file upload | Upload status changes to “failed” and error message is displayed | Pass |