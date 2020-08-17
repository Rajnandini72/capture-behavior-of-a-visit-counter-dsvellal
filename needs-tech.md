# Visit-counter technical needs

Scenario: Recover across restarts of the server
that runs the visit-counter

  Given:restart of visitor count system or server has get down due to software /internal issues
  When:Last time updated visitor count,save it and should be saved each time 
  Then: when system resumes should restore all data

Scenario: Reconcile counts if the sensor is offline for a while

  Given:Sensor is off
  When: If any visitor enters in working hours
  Then:Do manual enteries and when sensor resumes add up the count
