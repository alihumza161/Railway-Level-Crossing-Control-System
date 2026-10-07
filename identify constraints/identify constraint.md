| ID | Constraint  | Why it is necessary |
|---|---|---|
| C1 | The barrier must not be open while a train is in the crossing. | Road vehicles could enter the path of the train and cause a collision. |
| C2 | Warning lights and the alarm must already be on before the barrier starts to close. | Drivers and pedestrians need time to clear the crossing before the barrier comes down. |
| C3 | The barrier may open only after the train has been confirmed completely clear. | Opening early could expose traffic to the train's rear section or a second train. |
| C4 | Whenever a train is approaching, the warning lights and alarm must be active. | Road users must be warned of the danger. |
| C5 | Whenever the barrier is not fully open, the road traffic signal must be red. | Drivers must not be told to proceed toward a closed or moving barrier. |
| C6 | If a train-detection sensor fails, the system must go to a safe state: barrier closed and the control center alerted. | A blind system cannot be trusted to know whether a train is present. |
| C7 | If communication is lost, the barrier must stay closed and the warnings must stay on. | The system cannot confirm the train's status, so it must assume danger. |
| C8 | If a barrier failure is detected, the control center must be alerted and a stop signal issued to the train. | A train must not enter a crossing that cannot be protected. |
| C9 | If sensor readings conflict, the barrier must not open. | Contradictory data cannot prove the crossing is safe, so the safe assumption is "train may be present". |
| C10 | If the train is within the minimum safe time of arrival, the barrier must already be fully closed. | A barrier that closes too late leaves no safe margin. |
| C11 | In an emergency, the barrier must be closed and the alarm on, and normal logic must not reopen it. | Emergencies must always resolve to the most protective state. |
| C12 | The barrier must not lower onto a vehicle stopped in the crossing zone. | Prevents vehicles being trapped or damaged, and prevents barrier-motor overload. |
