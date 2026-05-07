# Notifications — Real-Time Test Cases

| TC ID | Module | Test Description | Pre-conditions | Test Steps | Expected Result | Status |
|------|---------|------------------|----------------|-------------|-----------------|--------|
| TC-021 | Real-Time Notifications | Verify upload progress notification appears | User is on upload page | 1. Select more than 3 PDF files 2. Click “Upload” | “Upload in progress” notification banner appears immediately | Pass |
| TC-022 | Real-Time Notifications | Verify success notification after bulk upload completion | User is on upload page | 1. Upload multiple PDF files 2. Wait until upload completes | Success notification is displayed after upload completion | Pass |
| TC-023 | Real-Time Notifications | Verify notifications persist after navigation | User starts bulk upload | 1. Upload multiple files 2. Navigate to another page 3. Return to upload page | Notification is still displayed after returning | Pass |
| TC-024 | Real-Time Notifications | Verify notification contains file count and timestamp | User uploads multiple files | 1. Upload more than 3 files 2. Open notification | Notification displays number of uploaded files and timestamp | Pass |
| TC-025 | Real-Time Notifications | Verify notification appears without page refresh | User uploads files | 1. Upload multiple files 2. Observe notification area | Notification appears automatically without refreshing the page | Pass |