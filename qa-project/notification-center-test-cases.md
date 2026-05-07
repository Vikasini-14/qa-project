# Notification Center Test Cases

| TC ID | Module | Test Description | Pre-conditions | Test Steps | Expected Result | Status |
|------|---------|------------------|----------------|-------------|-----------------|--------|
| TC-026 | Notification Center | Verify unread notification count badge | User receives a new notification | 1. Upload files 2. Observe notification bell icon | Unread notification count badge is displayed on bell icon | Pass |
| TC-027 | Notification Center | Verify notification panel opens on bell icon click | User is on dashboard page | 1. Click notification bell icon | Notification panel opens displaying notifications | Pass |
| TC-028 | Notification Center | Verify marking notification as read | Notification exists in notification panel | 1. Open notification panel 2. Mark one notification as read | Notification changes to read status and unread count decreases | Pass |
| TC-029 | Notification Center | Verify “Mark All as Read” functionality | Multiple unread notifications exist | 1. Open notification panel 2. Click “Mark All as Read” | All notifications are marked as read and unread badge disappears | Pass |
| TC-030 | Notification Center | Verify notifications persist after page refresh | Notifications exist in system | 1. Refresh the page 2. Open notification panel | Notifications are still displayed after page refresh | Pass |
| TC-031 | Notification Center | Verify notifications are sorted by latest first | Multiple notifications exist | 1. Open notification panel | Notifications are displayed in descending order based on latest timestamp | Pass |