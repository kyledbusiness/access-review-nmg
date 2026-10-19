# Northstar Medical Group — Simulated IAM Access Review

## Problem Statement

Northstar Medical Group has 48 fictional users across Finance, HR, IT, and Operations. As the organization grew, user access accumulated across departments, applications, and administrative groups. But who was checking whether that access still made sense?

- Employees may retain permissions from previous responsibilities.
- Former contractors may still have active accounts.
- Users may hold privileged access without a clear business justification.
- There is no consistent record connecting access decisions to business needs, review ownership, and follow-up actions.
- The problem wasn't just who had access. It was whether that access was still justified, who was responsible for validating it, and what needed to happen next.

## Solution Overview

I built a simulated IAM access review to evaluate user permissions against job responsibilities, employment status, and documented business needs. Instead of treating every permission as either right or wrong, I classified findings, assessed the risk, and documented a recommended action for each case.

- I created an access review register covering Finance, HR, IT, and Operations.
- I evaluated permissions and identified scenarios involving excessive access, privileged accounts, and a former contractor.
- I documented priority findings and manager or review-owner decisions, including when access should be kept, removed, or revalidated.
- I organized the results into a summary to make findings and recommended follow-up easier to understand.

## Video Walkthrough
- Link

## Walkthrough

### 1. Inventory the Access

 - Established a fictional user population with departments, job roles, managers, employment status, and assigned groups.

### 2. Validate Business Need

- Compared assigned access against each user's responsibilities and employment status. A job title alone wasn't enough to prove that a permission was justified.

### 3. Identify and Classify Risk

- Flagged scenarios involving excessive permissions, elevated administrative access, expired employment, and access requiring further validation.

### 4. Document Decisions

- Recorded the recommended action and review ownership for priority cases. Missing justification triggered further review rather than automatically proving that access was inappropriate.

### 5. Summarize the Results

- Organized findings and outcomes to make it easier to see which permissions could be retained, which needed follow-up, and where remediation was recommended.

## Key IAM Principles

- Least privilege: Access should match current business responsibilities—not accumulate indefinitely.
- Accountability: Access decisions need an identifiable owner and a documented rationale.\
- Risk-based review: Privileged and potentially outdated access deserve closer scrutiny.
- Evidence-driven decisions: A suspicious permission is a reason to investigate; it isn't automatically proof of misuse.
- Remediation and verification: Recommending an access change is not the same as confirming that it was completed.

Key Achievements

- Built a structured access review register connecting user roles, assigned permissions, business justification, findings, and recommended actions.
- Evaluated realistic scenarios involving privileged access, outdated permissions, and a former contractor to determine appropriate next steps.
- Documented decision ownership and rationale, demonstrating how access reviews support least-privilege decisions and accountability.
