# Visit-counter for a Facilities Manager

Scenario: Report visitor trends during a week of operation

  Given a week of operation
  
  When there are visitors
  
  Then generate a report

Scenario: Alert when seating capacity is full

  Given a limited seating capacity
  
  When 90% of the capacity is occupied
  
  Then raise an alert on email
