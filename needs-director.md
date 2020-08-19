# Visit-counter for a Director

Scenario: Show patient visits during working days and holidays

Given the hospital is open and each patient is given a unique 

entry card
  
When the entry card triggers at the entrace
  
Then increment the visit count by 1

Scenario: Compute parking slots to reserve for visiting specialists

Given a hospital with parking slots
  
When a visiting specialist has an appointment
  
Then reserve a parking slot for them
