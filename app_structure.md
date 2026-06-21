# LIPHIMBO App Structure (MVP)

## Screens
- Login
- Register
- Home Feed
- Report Issue
- Task Details
- Profile

## Data Models

### User
- id
- name
- email
- points

### Issue
- id
- title
- description
- image
- location
- status

### Task
- id
- issueId
- assignedTo
- status

### Proof
- id
- taskId
- image
- verificationStatus
