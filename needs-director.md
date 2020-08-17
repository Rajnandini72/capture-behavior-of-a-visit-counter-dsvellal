# Visit-counter for a Director

Scenario: Show patient visits during working days and holidays

  Given: Hospital open time is 10am-6pm for Working days and 10am-2pm for Holidays.
  When: Patient enters in this time slot, need to do new entry
  Then: patien_count variable will count the number of new entries.

Scenario: Compute parking slots to reserve for visiting specialists

  Given: 2-3 fix days of week when specialist visits
  When: Some x specialist going to visit, make sure X empty parking slots are available
  Then: To reserve X slots Print "No parking available or shift parking arena to other place"
