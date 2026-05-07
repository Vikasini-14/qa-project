# Notification Center Test Cases

| TC ID | Module | Test Description | Pre-conditions | Test Steps | Expected Result | Status |
|------|---------|------------------|----------------|-------------|-----------------|--------|
| TC-026 | Notification Center | Verify unread notification count badge appears | User receives a new notification | 1. Upload files to generate notification 2. Observe bell icon | Bell icon displays unread notification count badge | Pass |
| TC-027 | Notification Center | Verify notification panel opens on bell icon click | User is on dashboard page | 1. Click notification bell icon | Notification panel/page opens successfully | Pass |
| TC-028 | Notification Center | Verify marking notification as read decreases unread count | Unread notifications exist | 1. Open notification panel 2. Mark one notification as read | Notification changes to read status and unread count decreases | Pass |
| TC-029 | Notification Center | Verify “Mark All as Read” functionality | Multiple unread notifications exist | 1. Open notification panel 2. Click “Mark All as Read” | All notifications are marked as read and unread badge disappears | Pass |
| TC-030 | Notification Center | Verify notifications persist after page refresh | Notifications already exist | 1. Refresh the page 2. Open notification panel | Notifications are still displayed after page refresh | Pass |
| TC-031 | Notification Center | Verify notifications are sorted by most recent first | Multiple notifications exist | 1. Open notification panel 2. Observe notification order | Latest notifications appear at the top of the list | Pass |