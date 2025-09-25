# Work Hours Tracker (Excel + VBA)

This Excel tool tracks work hours for jobs with variable schedules, such as construction work, freelance tasks, or any activity requiring time tracking.

## Features
- Calculates daily work hours, including overnight shifts (when work continues past midnight).
- Automatically deducts breaks from total hours.
- Calculates total hours per month and gross pay for reporting and analysis.
- Flexible template that can also be used for tracking time spent on any activity, not just work.

## How It Works
- The tracker automatically calculates:
  - **Total hours worked per day**
  - **Total hours worked per month**
  - **Gross pay** = Total hours × Hourly rate
- Break times are subtracted automatically from the total hours.

## How to Use
1. Enter the start and end times for each workday.
2. If the work continues past midnight (e.g., from 16:00 to 3:00 the next day), type `1` in the **"Overnight"** column.
3. Enter your hourly rate in the designated cell.
4. Use the summary sheet to analyze monthly totals.

## Notes
- A separate demo workbook is included as an example.
- Enable macros to allow automatic calculations.
