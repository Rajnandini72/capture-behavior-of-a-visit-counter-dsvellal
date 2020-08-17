# Visit-counter for a Facilities Manager

Scenario: Report visitor trends during a week of operation

  Given:Visiting time 11am-2pm
  When:Person visiting has any patient admitted and want to meet or want to operate ,then make entry
  Then:Visitor_count will count the entries

Scenario: Alert when seating capacity is full

  Given:Working Hours of hospital
  When:Seating capacity is full or hospital premises has over-occupied
  Then:Try to reduce crowd and stop visitors for some time
