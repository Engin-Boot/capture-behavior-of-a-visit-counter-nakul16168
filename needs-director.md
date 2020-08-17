# Visit-counter for a Director

Scenario: Show patient visits during working days and holidays

  Given a hospital with a visit counter
  
  When a patient enters
  
  Then increment the visit count by 1

Scenario: Compute parking slots to reserve for visiting specialists

  Given a hospital with parking slots
  
  When a visiting specialist has an appointment
  
  Then reserve a parking slot for them
