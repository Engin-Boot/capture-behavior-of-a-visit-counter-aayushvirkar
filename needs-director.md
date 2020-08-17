# Visit-counter for a Director

Scenario: Show patient visits during working days and holidays

  Given
  People visit the hospital
  When
  patient enters the premises of the hospital
  Then
  take record of the patient
Scenario:Compute parking slots to reserve for visiting specialists

  Given
  Patients and Working staff park their vehicles
  When
  Parking capacity is near 90%
  Then
  Reserve the rest(10%) for the specialists
