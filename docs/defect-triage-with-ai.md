# AI in Defect Triage

## Problem
Defect triage is often:
- Time-consuming
- Inconsistent across teams
- Dependent on human interpretation

---

## AI Solution

### 1. Duplicate Detection
AI clusters similar bug reports.

### 2. Severity Suggestion
Based on:
- Impact area
- Frequency
- User journey criticality

### 3. Root Cause Hypothesis
AI suggests likely layers:
- UI
- API
- Database
- Infra

---

## Example

### Input Bug:
"Payment fails intermittently during checkout"

### AI Output:
- Possible API timeout issue
- Retry logic inconsistency
- Network latency dependency
- High severity due to revenue impact

---

## QA Responsibility
AI assists classification.  
QA validates severity and priority.
