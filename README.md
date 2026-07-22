## My Contribution – Booking Management Module

This is an academic group project. My primary responsibility was the **Booking Management Module**, covering the user and administrator booking interfaces.

### Frontend Responsibilities

- Designed and implemented the Booking Dashboard with booking statistics and quick actions
- Developed the Create Booking form with resource, date, time, purpose, and attendee inputs
- Built the My Bookings page with search, filtering, status display, edit, and cancellation options
- Developed the Admin Manage Bookings page with booking review, approval, and rejection actions
- Integrated booking-related backend APIs using Axios through `bookingApi.js`
- Added pre-submission booking summaries
- Implemented status-based visual feedback, alerts, and booking indicators

### Conflict Prevention System

- Implemented real-time resource availability checking
- Added overlap detection for existing booking time slots
- Displayed visual feedback when a selected time slot was unavailable
- Prevented booking submission when a scheduling conflict was detected

### Frontend Validations

- Restricted bookings to business hours between 08:00 and 20:00
- Prevented selection of past dates and times
- Validated start-time and end-time sequences
- Applied booking-duration restrictions
- Validated attendee capacity against the selected resource

### Technologies Used

React, Vite, Tailwind CSS, JavaScript, Axios, REST APIs, Git, and GitHub

## Related Repository

- [Backend Repository](https://github.com/dinithi-uthpala/it3030-paf-2026-smart-campus-backend)

