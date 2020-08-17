# Visit-counter for a Director

Scenario: Show patient visits during working days and holidays

  Given 
 I am director of an hospital
  When
  patient enters the premises of the hospital
  Then
  Take record of the patient (Entry/Exit)

Scenario: Compute parking slots to reserve for visiting specialists

  Given 
  i am director of an hosiptal
  When
  Parking capacity is near 90% 
  Then
  Reserve the rest(10%) for the specialists
