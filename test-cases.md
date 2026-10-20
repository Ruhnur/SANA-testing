# SANA — Test Cases

## Test Plan

Project: SANA personal development tracker
Repository: Ruhnur/SANA-testing
Status: PLANNED — тестілер әлі орындалған жоқ.

## TC-001 — Create a goal
- Preconditions: User can access the application.
- Steps: Open Goals, enter a valid goal, save it.
- Expected: The goal is saved and displayed.
- Actual: Not tested.
- Status: PLANNED

## TC-002 — Empty goal name
- Steps: Submit a goal without a name.
- Expected: Validation message is displayed; invalid goal is not saved.
- Actual: Not tested.
- Status: PLANNED

## TC-003 — Goal deadline
- Steps: Set a valid future deadline and save the goal.
- Expected: The selected deadline is displayed correctly.
- Actual: Not tested.
- Status: PLANNED

## TC-004 — Overdue task warning
- Preconditions: An incomplete task exists.
- Steps: Set its deadline to a past date and open the dashboard.
- Expected: The task is marked overdue and a warning is displayed.
- Actual: Not tested.
- Status: PLANNED

## TC-005 — Complete a task
- Steps: Mark an existing task as completed.
- Expected: The task status and related progress are updated.
- Actual: Not tested.
- Status: PLANNED

## TC-006 — Language switching
- Steps: Switch between Kazakh, English and Russian.
- Expected: Available interface text changes to the selected language.
- Actual: Not tested.
- Status: PLANNED

## TC-007 — Progress calculation
- Steps: Complete a task and inspect progress analytics.
- Expected: Progress reflects the saved task status according to the defined rules.
- Actual: Not tested.
- Status: PLANNED

## TC-008 — Data persistence
- Steps: Save a goal, reload the application and inspect the goal list.
- Expected: Saved data remains available according to the application's storage design.
- Actual: Not tested.
- Status: PLANNED

## TC-009 — Invalid deadline
- Steps: Attempt to enter an invalid deadline, if the interface permits it.
- Expected: Invalid input is rejected or a clear validation message appears.
- Actual: Not tested.
- Status: PLANNED

## TC-010 — Responsive layout
- Steps: Open the interface at desktop and mobile viewport sizes.
- Expected: Content and controls remain usable without unintended overflow.
- Actual: Not tested.
- Status: PLANNED

## Test Execution Notes
These are planned test cases. Do not report PASS or FAIL until each test has actually been executed and its observed result recorded .
