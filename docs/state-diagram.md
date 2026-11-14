State Diagram
Hearing-Aid Battery Life Prediction Workflow

The following diagram represents the basic workflow of the system.

text
       START
         |
         v
  Register Patient
         |
         v
  Register Hearing Aid
         |
         v
  Add Battery Details
         |
         v
  Record Daily Usage
         |
         v
  Calculate Battery Life
         |
         v
  Predict Replacement Date
         |
         v
  Is Battery Running Low?
       /       \
     YES        NO
      |          |
      v          v
 Schedule     Continue
 Shipment     Monitoring
      |          |
      v          |
 Send Reminder   |
      |          |
      +-----+----+
            |
            v
       Update Records
            |
            v
           END

Description
Patient information is registered.
Hearing-aid and battery details are stored.
Daily usage is recorded.
The system predicts the remaining battery life.
If the battery is running low, a shipment and reminder are scheduled.
Otherwise, the system continues monitoring battery usage.
