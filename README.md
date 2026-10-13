# Contractor Route Checker

A lightweight standalone planner for manually entering booked contractor estimates, checking possible new appointment windows, and opening the entered stops in Google Maps.

## Features
- Separate appointment schedules by contractor and date
- Add and remove booked estimate appointments
- Suggest possible openings based on work hours, estimate duration, buffer time, and rough ZIP-code matches
- Open the starting location and estimate stops in Google Maps
- Copy the daily schedule and export/import a local backup

## Important limitations
- Appointment data and settings are saved in the browser's local storage on the device where you use the app. They are not synced between browsers or devices.
- This app does not connect to GoHighLevel (GHL).
- Suggested openings are schedule-based. ZIP-code matching is only a rough clue; the app does not calculate actual drive times or automatically optimize route order. Check Google Maps before confirming an appointment.
- Do not store private customer details in this public repository. Appointment entries are stored locally by the running app and are not uploaded to GitHub.

## Publish with GitHub Pages
In the repository, open **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, select branch **main** and folder **/(root)**, then click **Save**. After GitHub finishes publishing, the site should be available at:

https://joyceyap101782-pixel.github.io/contractor-route-checker/

