# Changelog

## 0.17.0 (2026-10-12)

The SDK's first release as its own repository; before this it lived in the AudienceKit monorepo at `sdk/kotlin`.

### Breaking

- The door calls for staff (`doorVenues()`, `venueDoor(venueId, night)`, `scanAdmission(venueId, code)`) and their
  models (`DoorVenue`, `DoorNight`, `DoorTickets`, `DoorCover`, `ScanResult`, `ScanOutcome`) moved to StaffKit for
  Android. Members' own passes (`admissions()`, `Admission.scanCount`, `checkedInAt`) stay here.
