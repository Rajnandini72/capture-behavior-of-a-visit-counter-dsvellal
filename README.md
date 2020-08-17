# Visit-counter Behavior

This project works out the features of a
visit-counting software, called the 'Visit-counter'.

Here's the context in which the Visit-counter works:

```mermaid
graph TD
  A[Sensor] -->|Entry| B(Visit-counter)
  B -->|Aggregate| C[Report]
```

_Diagram not visible? Use the
[Mermaid live viewer](https://mermaid-js.github.io/mermaid-live-editor)
or use a [VScode plug-in](https://marketplace.visualstudio.com/items?itemName=bierner.markdown-mermaid)_

The **Sensor** could be one of:

- foot-fall counter at the door
- entry-card issuer
- hospital staff attendance system

The **Report** caters to the needs of specific stakeholders.
State the features of the visit-counter for the following stakeholders:

- Facilities manager (manages seating and parking)
- Director (ensures availability of beds and nursing staff)

Each feature would consist of scenarios.
Capture each scenario as:

- initial condition (Given...)
- event (When...)
- effect (Then...)

Place features given to each stakeholder in the corresponding file.

As always, avoid passive voice :)
