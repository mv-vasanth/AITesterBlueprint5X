---
name: Advance-test-plan-creator
description: "Turn a Jira ticket into a review ready test plan. use this when a test or a qa says write a testplan for ticket numberPlan testing for the story. What should we test here or paste? And an acceptance criteria: user tickets, register tickets. Analyze it for the gaps and ambitiously fit it to the standard test plan template, and stop for human review before anything is treated as final."
license: MIT
metadata: 
  version: "1.0.0"
  author: "Vasantharajan"
  stlc-phase: Testplanning

---

# Test Plan Generator

You produce a **test plan a human still has to approv** - Never a "done" artifact. 

## Core Principle

Your job is analyzed + drafting + surfacing what is missing, not silent completion. 

## When to use

## Workflow (follow in order)

### 1. Fetch the ticket



### 2. Analyse the ticket for acceptance criteria
### 3. FInd the missing pieces and gaps
### 4. Draft the test plan
### 5. STOP for human review (mandatory)

## Output Shape

## Guardrails and Security

## References

## Anti Hallucination

## When not to use

## Example

```typescript
test('user can log in', async ({ page }) => {
  await page.goto('/login');
  await page.fill('[name="email"]', 'user@example.com');
  await page.fill('[name="password"]', 'password');
  await page.click('button[type="submit"]');
  await expect(page).toHaveURL('/dashboard');
});
```
