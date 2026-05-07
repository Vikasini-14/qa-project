# Upload Progress Test Cases

| TC ID | Module | Test Description | Pre-conditions | Test Steps | Expected Result | Status |
|------|---------|------------------|----------------|-------------|-----------------|--------|
| TC-016 | Upload Progress | Verify progress bar visibility during upload | User is on upload page | 1. Select a valid PDF file 2. Click “Upload” | Progress bar is visible while file uploads | Pass |
| TC-017 | Upload Progress | Verify progress percentage updates in real time | User is on upload page | 1. Select a large PDF file 2. Click “Upload” | Upload percentage updates continuously until completion | Pass |
| TC-018 | Upload Progress | Verify status changes from “uploading” to “complete” | User is on upload page | 1. Upload a valid PDF file 2. Wait for upload completion | Status changes from “uploading” to “complete” after upload finishes | Pass |
| TC-019 | Upload Progress | Verify upload progress during slow network | User is on upload page | 1. Simulate slow internet connection 2. Upload a file | Progress bar continues updating and does not freeze | Pass |
| TC-020 | Upload Progress | Verify failed upload shows error status | User is on upload page | 1. Disconnect internet during upload 2. Attempt file upload | Upload status changes to “failed” with error message displayed | Pass |