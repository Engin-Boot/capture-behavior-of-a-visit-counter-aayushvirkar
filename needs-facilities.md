# Visit-counter for a Facilities Manager

Scenario: Report visitor trends during a week of operation

  Given 
  Patient gets visitors
  When
  Patient has to undergo operation
  Then
  Record the no. of visitors and their duration of visit of the Patient 

Scenario: Alert when seating capacity is full

  Given
  i am facility manager at an hospital
  When
  The no. of hospital beds reach threshold capacity(90%)
  Then
  Send a notification/alert of lack of beds
  and announce it on led boards for general public
