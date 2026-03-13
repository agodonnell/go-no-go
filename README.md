# Go / No-Go

A readiness-driven training decision system.

Pulls performance and readiness measurements from the Garmin API and uses them to determine whether scheduled training should proceed as planned, be modified, or be deferred.

---

## Decision Output

| Decision | Meaning |
|----------|---------|
| Go | Proceed with scheduled training as planned |
| Modify | Complete training at reduced intensity or volume |
| No-Go | Defer — recovery takes priority |

---

## Planned Inputs

- Garmin API: HRV, recovery score, training load, sleep quality, body battery
- Scheduled training plan

---

## Status

Pre-build. Currently evaluating which Garmin performance and readiness measurements are most predictive before committing to a system design.

Development begins after the research engine project.
