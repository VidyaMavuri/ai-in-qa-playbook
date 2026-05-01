# Prompt Engineering for QA

## What is a QA Prompt?
A structured instruction used to extract test-relevant intelligence from LLMs.

---

## Effective QA Prompt Structure

### Template:
Context: [System description] Task: [What QA needs] Constraints: [Rules, limits] Output format: [Test cases / JSON / table]
---

## Example Prompt

### Weak Prompt:
"Write test cases for login"

### Strong QA Prompt:
Context: Web application login supports OAuth2, MFA, and session timeout. Task: Generate comprehensive test cases. Constraints:
* Include negative and security scenarios
	•	Include boundary conditions Output: Structured table format with ID, scenario, expected result
---

## Prompt Patterns Used in QA

### 1. Coverage Expansion Prompt
- Expands basic test cases into full matrices

### 2. Adversarial Prompt
- Forces AI to generate failure scenarios

### 3. Consistency Prompt
- Re-runs same input under variations

---

## Insight from a Senior QA
Bad prompts = noisy tests  
Good prompts = production-grade QA intelligence
