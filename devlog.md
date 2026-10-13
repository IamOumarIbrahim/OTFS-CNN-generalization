# Development Log

Record all design decisions, configuration changes, experiment runs, and codebase modifications here.

---

## Log Template

Copy and paste this template at the top of the **Entries** section for every new log:

```markdown
### [YYYY-MM-DD] [HH:MM] - <Brief Title / Summary of Change>

- **Author**: Oumar Ibrahim
- **Component(s)**: [e.g., config / signal / learning / detectors / evaluation / scripts]
- **Type**: [Architecture | Parameter Change | Bug Fix | Optimization | Experiment Run]

#### Summary of Changes
- <What changed and why>

#### Simulation & Model Parameters Affected
- **Parameter(s)**: [e.g., SNR range, M x N grid, Doppler, learning rate]
- **Old Value**: 
- **New Value**: 

#### Verification / Test Outcome
- **Sanity check passed**: [Yes / No / Pending]
- **Notes / Observations**: 
```

---

## Entries

<!-- Add new entries below this line (newest on top) -->

### [2026-10-14] [03:27] - Defined project structure

- **Author**: Oumar Ibrahim
- **Component(s)**: [config / signal / learning / detectors / evaluation / scripts]
- **Type**: [Architecture]

#### Summary of Changes
- Created initial file structure.

#### Simulation & Model Parameters Affected
- **Parameter(s)**: N/A
- **Old Value**: N/A
- **New Value**: N/A

#### Verification / Test Outcome
- **Sanity check passed**: [N/A]
- **Notes / Observations**: This is the initial commit.

---


### [2026-10-14] [03:30] - Delayed GRU and Mamba Implementation

- **Author**: Oumar Ibrahim
- **Component(s)**: [config / signal / learning / detectors / evaluation / scripts]
- **Type**: [Architecture]

#### Summary of Changes
- Delayed GRU and Mamba for after CNN performance is established. 
- GRU and Mamba will only be implemented and tested for the time domain representation.

#### Simulation & Model Parameters Affected
- **Parameter(s)**: N/A
- **Old Value**: N/A
- **New Value**: N/A

#### Verification / Test Outcome
- **Sanity check passed**: [N/A]
- **Notes / Observations**: This is an architectural design choice change, no files were affected.



---

