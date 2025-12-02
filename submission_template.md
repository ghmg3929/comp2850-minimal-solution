**Student**: Matthew Gregson (201818662) **Submission date**: \[DD/MM/YYYY\] **Academic Year**: 2025-26

------------------------------------------------------------------------

## [Privacy & Ethics Statement](#privacy--ethics-statement){#privacy--ethics-statement}

-   I confirm all participant data is anonymous (session IDs use P1_xxxx format, not real names)
-   I confirm all screenshots are cropped/blurred to remove PII (no names, emails, student IDs visible)
-   I confirm all participants gave informed consent
-   I confirm this work is my own (AI tools used for code assistance are cited below)

**AI tools used** (if any): ChatGPT used to better understand pico.css and other concepts needed for improvements

------------------------------------------------------------------------

## [1. Protocol & Tasks](#1-protocol--tasks){#1-protocol--tasks}

### [Link to Needs-Finding (LO2)](#link-to-needs-finding-lo2)

**Week 6 Job Story #1**:

**Situation**: When I struggle to remember tasks  
**Motivation**: I want to quickly add the task the moment I come up with it  
**Outcome**: So I can rely on my task list to keep track of them  
**Underlying Need**: Meaning I can be certain I haven't forgotten anything I need to do (Cognitive Impairment)

**How Task 1 tests this**: It ensures tasks can be added swiftly and clearly


**Week 6 Job Story #2**:

**Situation**: When my descriptions of tasks begin to be unclear to me  
**Motivation**: I want either me or someone else to be able to rephrase them  
**Outcome**: So I can always understand what it is I need to do  
**Underlying Need**: So I always can maintain clarity on what it is I need to do (Cognitive Impairment, possibly with helper)

**How Task 2 tests this**: It ensures it is perfectly clear how to change the names of tasks


**Week 6 Job Story #3**:

**Situation**: When I'm scrolling through the task list  
**Motivation**: I want to be able to find the task I need quickly  
**Outcome**: So I reach the task with minimal effort  
**Underlying Need**: So I can reduce the physical strain of using the task list effectively (Motor Impairment)

**How Task 3 tests this**: It ensures it is easy to filter and unfilter the task list


**Week 6 Job Story #4**:

**Situation**: When the task list becomes cluttered  
**Motivation**: I want to be able to remove tasks I have completed  
**Outcome**: So I can focus on what I still need to do  
**Underlying Need**: To reduce any stress of trying to figure out what tasks are left (Anxiety)  

**How Task 4 tests this**: It ensures tasks can be removed swiftly and clearly

------------------------------------------------------------------------

### [Evaluation Tasks (4-5 tasks)](#evaluation-tasks-4-5-tasks){.header}

#### [Task 1 (T1): Add Tasks](#task-1-t1-task-name){.header}

-   **Scenario**: Add 3 tasks to the empty task list
-   **Action**: Add tasks with titles "Buy Milk", "Buy Eggs" and "Go Home"
-   **Success**: All 3 tasks appear in the task list, without error
-   **Target time**: 18 seconds
-   **Linked to**: Job Story #1

#### [Task 2 (T2): Edit Tasks](#task-2-t2-task-name){.header}

-   **Scenario**: Edit a task in the task list
-   **Action**: Edit "Buy Milk" to be "Buy Meat"
-   **Success**: Task appears with new name in task list, no duplicate of original task, without error
-   **Target time**: 20 seconds (Account for scrolling)
-   **Linked to**: Job Story #2

#### [Task 3 (T3): Filter Tasks](#task-3-t3-task-name){.header}

-   **Scenario**: Filter tasks so only relevant ones are shown
-   **Action**: Filter by the word "Buy"
-   **Success**: Only "Buy Meat" and "Buy Eggs" is shown in the task list, without error
-   **Target time**: 6 seconds
-   **Linked to**: Job Story #3

#### [Task 4 (T4): Unfilter Tasks](#task-3-t3-task-name){.header}

-   **Scenario**: Unfilter tasks to return to the full task list
-   **Action**: Remove the "Buy" Filter
-   **Success**: All tasks appear on the task list again
-   **Target time**: 6 seconds
-   **Linked to**: Job Story #3

#### [Task 5 (T5): Delete Tasks](#task-3-t3-task-name){.header}

-   **Scenario**: Delete all 3 tasks from the task list
-   **Action**: Delete all 3 tasks from the task list
-   **Success**: The task list is empty, without error
-   **Target time**: 20 seconds
-   **Linked to**: Job Story #4

------------------------------------------------------------------------

### [Consent Script (They Read Verbatim)](#consent-script-they-read-verbatim){.header}

**Introduction**: "Thank you for participating in my HCI evaluation. This will take about 15 minutes. I'm testing my task management interface, not you. There are no right or wrong answers."

**Rights**:

-   "Your participation is voluntary. You can stop at any time without giving a reason."
-   "Your data will be anonymous. I'll use a code (like P1) instead of your name."
-   "I may take screenshots and notes. I'll remove any identifying information."
-   "Do you consent to participate?" \[Wait for verbal yes\]

**Recorded consent timestamp**: \[e.g., "P1 consented 22/11/2025 14:05"\]

------------------------------------------------------------------------

## [2. Findings Table](#2-findings-table){.header} {#2-findings-table}

**Instructions**: Fill in this table with 3-5 findings from your pilots. Link each finding to data sources.

::: table-wrapper
| Finding (1–5)             | Data Source                   | Observation (Quote/Timestamp)     | WCAG       | Impact (1–5) | Inclusion (1–5)  | Effort |
|---------------------------|-------------------------------|-----------------------------------|------------|--------------|------------------|--------|
| Unfilter not obvious (1)  | P1 notes + metrics.csv L7–10  | “How do I remove the filter?”     | WCAG 3.3.2 | 3            | 3                | 2      |
| Hard to edit (2)          | P1 notes                      | Observation 2                     | WCAG 1.3.2 | 2            | 1                | 3      |
| Outline not visible (3)   | P2 notes                      | “The outline is a bit faint”      | WCAG 2.4.7 | 4            | 2                | 1      |
| Edit without js (4)       | P3 notes                      | Observation 2                     | WCAG 4.1.2 | 3            | 3                | 5      |

:::

**Priority formula**: (Impact + Inclusion) - Effort

**Top 3 priorities for redesign**:

1.  Finding 3 - Priority 5
2.  Finding 1 - Priority 4
3.  Finding 2 - Priority 0

**How to complete this table** (decision tree):

1.  **Identify finding**: From pilot observations, metrics.csv anomalies (high times, errors), or WCAG violations
2.  **Link data source**: Cite specific metrics.csv line numbers (e.g., "L47-49") OR pilot notes timestamps (e.g., "P2 notes 14:23")
3.  **Check WCAG**: If accessibility-related, find the criterion using [W3C WCAG 2.2 Quick Reference](https://www.w3.org/WAI/WCAG22/quickref/)
4.  **Score priority**: Use [Week 10 Lab 1 prioritisation scales](../wk10/wk10-lab1-analysis-prioritisation.html#prioritisation-framework) to rate Impact (1-5), Inclusion (1-5), Effort (1-5), then calculate Priority = (Impact + Inclusion) - Effort

------------------------------------------------------------------------

## [3. Pilot Metrics (metrics.csv)](#3-pilot-metrics-metricscsv){.header} {#3-pilot-metrics-metricscsv}

**Instructions**: Paste your raw CSV data here OR attach metrics.csv file

[Metrics csv file](data/metrics.csv)

**Participant summary**:

-   **P1**: Laptop with HTMX on
-   **P2**: Laptop with HTMX on, Keyboard Only
-   **P3**: Laptop with no JS

**Total participants**: 3

------------------------------------------------------------------------

## [4. Implementation Diffs](#4-implementation-diffs){.header} {#4-implementation-diffs}

**Instructions**: Show before/after code for 1-3 fixes. Link each to findings table.

### [Fix 1: Clear Filter Button](#fix-1-fix-name){.header}

**Addresses finding**: Finding 1
**Path and File**: index.peb Line 80

**Before**:

[Original code](evidence/screenshots/filter-buttons-before.png)

**After**:

[Fixed code](evidence/screenshots/filter-buttons-after.png)

**What changed**: Added a remove filter button which clears any filter

**Why**: This fixes Labels and Instructions, making it clearer how to remove any filter

**Impact**: This provides a specified button for removing the filter, which is much clearer than it was otherwise

------------------------------------------------------------------------

### [Fix 2: Increase Outline Visibility](#fix-2-fix-name){.header}

**Addresses finding**: Finding 3
**Path and Line**: base.peb Line 54

**Before**:

[Original code](evidence/screenshots/focus-outline-before.png)

**After**:

[Fixed code](evidence/screenshots/focus-outline-after.png)

**What changed**: Added some css to add outlines around certain buttons.

**Why**: This fixes Focus Visible, which means keyboard only users and those with visual impairments can tell when a button is selected.

**Impact**: By adding an outline when a button is selected, it is much clearer than just a slight darkening effect

------------------------------------------------------------------------

## [5. Verification Results](#5-verification-results){.header} {#5-verification-results}

### [Part A: Regression Checklist (20 checks)](#part-a-regression-checklist-20-checks){.header}

**Instructions**: Test all 20 criteria. Mark pass/fail/n/a + add notes.
**Axe Report**: [Report Here](evidence/screenshots/Regression-Axe-Report.png)

::: table-wrapper
### Keyboard (5)

| Check | Criterion                             | Level  | Result            | Notes                                                       |
|-------|---------------------------------------|--------|-------------------|-------------------------------------------------------------|
| K1    | 2.1.1 All actions keyboard accessible | A      | pass              | Tested Tab/Enter on all buttons                             |
| K2    | 2.4.7 Focus visible                   | AA     | pass              | 2px blue outline on all interactive elements                |
| K3    | No keyboard traps                     | A      | pass              | Can Tab through filter, edit, delete without traps          |
| K4    | Logical tab order                     | A      | pass              | Top to bottom, left to right                                |
| K5    | Skip links present                    | AA     | fail              | It doesn't take you straight to the task list               |

### Forms (3)

| Check | Criterion              | Level | Result        | Notes                                              |
|------|-------------------------|-------|---------------|----------------------------------------------------|
| F1   | 3.3.2 Labels present    | A     | pass          | All inputs have label or aria-label                |
| F2   | 3.3.1 Errors identified | A     | pass          | This did not get corrected during my fixes         |
| F3   | 4.1.2 Name/role/value   | A     | pass          | All form controls have accessible names            |

### Dynamic (3)

| Check | Criterion                | Level | Result      | Notes                                              |
|-------|--------------------------|-------|-------------|----------------------------------------------------|
| D1    | 4.1.3 Status messages    | AA    | pass        | Status div has role=status                         |
| D2    | Live regions work        | AA    | pass        | Tested with NVDA, announces “Task added”           |
| D3    | Focus management         | A     | pass        | Focus moves to error summary after submit          |

### No-JS (3)

| Check | Criterion               | Level | Result      | Notes                                             |
|-------|-------------------------|-------|-------------|---------------------------------------------------|
| N1    | Full feature parity     | —     | fail        | edit task does not work without js                |
| N2    | POST-Redirect-GET       | —     | pass        | No double-submit on refresh                       |
| N3    | Errors visible          | A     | pass        | Error summary shown in no-JS mode                 |

### Visual (3)

| Check | Criterion               | Level | Result      | Notes                           |
|-------|-------------------------|-------|-------------|---------------------------------|
| V1    | 1.4.3 Contrast minimum  | AA    | pass        | All text 7.1:1 (AAA) via CCA    |
| V2    | 1.4.4 Resize text       | AA    | pass        | 200% zoom, no content loss      |
| V3    | 1.4.11 Non-text contrast| AA    | pass        | Focus indicator 4.5:1           |

### Semantic (3)

| Check | Criterion                | Level | Result      | Notes                                          |
|-------|--------------------------|-------|-------------|------------------------------------------------|
| S1    | 1.3.1 Headings hierarchy | A     | pass        | h1 → h2 → h3, no skips                         |
| S2    | 2.4.1 Bypass blocks      | A     | pass        | `role="main"` landmark for filter              |
| S3    | 1.1.1 Alt text           | A     | pass        | No images                                      |

:::

**Summary**: 18/20 pass, 2/20 fail **Critical failures** (if any): Full Feature Parity

------------------------------------------------------------------------

### [Part B: Before/After Comparison](#part-b-beforeafter-comparison){.header}

**Instructions**: Compare Week 9 baseline (pre-fix) to Week 10 (post-fix). Show improvement.

::: table-wrapper
  |Metric                   |Before (Week 9, n=X)  |After (Week 10, n=Y)  |Change            |Target Met?  |
  |-------------------------|----------------------|----------------------|------------------|-------------|
  |Unfilter                 | 4700ms, n=3          | 3700ms, n=2          |-1000ms           |Yes          |
  |Focus Outline            | 21s, n=1             | 19.5s, n=1           |-1500ms           |Yes          |
:::

**Re-pilot details**:

-   **P4** (post-fix): Computer with HTMX on - 2/12/2025
-   **P5** (post-fix): Computer with HTMX on, Keyboard Only - 2/12/2025

**Limitations / Honest reporting**: There was a modest improvement in time due to the two fixes I implemented. These were only intended to be improvements to clarity, as I am not proficient enough to begin making more substantial changes like no-js task editing.

------------------------------------------------------------------------

## [6. Evidence Folder Contents](#6-evidence-folder-contents){.header} {#6-evidence-folder-contents}

**Instructions**: List all files in your evidence/ folder. Provide context.

### [Screenshots](#screenshots){.header}

::: table-wrapper
|Filename                   |What it shows                            |Context/Link to finding               |
|---------------------------|-----------------------------------------|--------------------------------------|
|regression-axe-report.png  |axe DevTools showing 0 violations        |Verification Part A                   |
|filter-buttons-before.png  |code showing the apply filter button     |Fix 1                                 |
|filter-buttons-after.png   |the added remove filter button code      |Fix 1                                 |
|focus-outline-before.png   |code showing the original css for buttons|Fix 2                                 |
|focus-outline-after.png    |the added outline css code for buttons   |Fix 2                                 |
:::

**PII check**:

-   All screenshots cropped to show only relevant UI
-   Browser bookmarks/tabs not visible
-   Participant names/emails blurred or not visible

------------------------------------------------------------------------

### [Pilot Notes](#pilot-notes){.header}

**Instructions**: Attach pilot notes as separate files (P1-notes.md, P2-notes.md, etc.). Summarize key observations here.

**P1**: [Link to notes](evidence/pilot_notes/P1-notes.md)  
        Strange to unfilter  
        A lot of traversal  
**P2**: [Link to notes](evidence/pilot_notes/P2-notes.md)  
        Strange to unfilter  
        Not enough outline contrast  
**P3**: [Link to notes](evidence/pilot_notes/P3-notes.md)  
        Problems with edit

------------------------------------------------------------------------

## [Evidence Chain Example (Full Trace)](#evidence-chain-example-full-trace){.header}

**Instructions**: Pick ONE finding and show complete evidence trail from data → fix → verification.

**Finding selected**: \[e.g., "Finding #1 - SR errors not announced"\]

**Evidence trail**:

1.  **Data**: metrics.csv lines 47-49 show P2 (SR user) triggered validation_error 3 times
2.  **Observation**: P2 pilot notes timestamp 14:23 - Quote: "I don't know if it worked, didn't hear anything"
3.  **Screenshot**: before-sr-error.png shows error message has no role="alert" or aria-live
4.  **WCAG**: 3.3.1 Error Identification (Level A) violation - errors not programmatically announced
5.  **Prioritisation**: findings-table.csv row 1 - Priority score 7 (Impact 5 + Inclusion 5 - Effort 3)
6.  **Fix**: implementation-diffs.md Fix #1 - Added role="alert" + aria-live="assertive" to error span
7.  **Verification**: verification.csv Part A row F2 - 3.3.1 now PASS (tested with NVDA)
8.  **Before/after**: verification.csv Part B - SR error detection improved from 0% to 100%
9.  **Re-pilot**: P5 (SR user) pilot notes - "Heard error announcement immediately, corrected and succeeded"

**Complete chain**: Data → Observation → Interpretation → Fix → Verification ✅

------------------------------------------------------------------------

## [Submission Checklist](#submission-checklist){.header}

Before submitting, verify:

**Files**:

-   This completed template (submission-template.md)
-   metrics.csv (or pasted into Section 3)
-   Pilot notes (P1-notes.md, P2-notes.md, etc. OR summarised in Section 6)
-   Screenshots folder (all images referenced above)
-   Privacy statement signed (top of document)

**Evidence chains**:

-   findings-table.csv links to metrics.csv lines AND/OR pilot notes timestamps
-   implementation-diffs.md references findings from table
-   verification.csv Part B shows before/after for fixes

**Quality**:

-   No PII in screenshots (checked twice!)
-   Session IDs anonymous (P1_xxxx format, not real names)
-   Honest reporting (limitations acknowledged if metrics didn't improve)
-   WCAG criteria cited specifically (e.g., "3.3.1" not just "accessibility")

**Pass criteria met**:

-   n=2+ participants (metrics.csv has 2+ session IDs)
-   3+ findings with evidence (findings-table.csv complete)
-   1-3 fixes implemented (implementation-diffs.md shows code)
-   Regression complete (verification.csv has 20 checks)
-   Before/after shown (verification.csv Part B has data)

------------------------------------------------------------------------

**Ready to submit?** Upload this file + evidence folder to Gradescope by end of Week 10.

**Estimated completion time**: 12-15 hours across Weeks 9-10

**Good luck!**
