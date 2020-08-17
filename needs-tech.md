# Visit-counter technical needs

Scenario: Recover across restarts of the server
that runs the visit-counter

  Given a server
  
  When the server restarts
  
  Then recover the visit count

Scenario: Reconcile counts if the sensor is offline for a while

  Given
  When
  Then
