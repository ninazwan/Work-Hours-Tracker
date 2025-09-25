# Work Hours Tracker (Excel + VBA)

This Excel tool tracks work hours for jobs with variable schedules, such as construction work, freelance tasks, or any activity requiring time tracking.

## Features
- Calculates daily work hours, including **overnight shifts** (when work continues past midnight).
- Automatically deducts breaks from total hours.
- Aggregates total hours per month for reporting and analysis.
- Flexible template that can also be used for tracking time spent on any activity, not just work.
- Calculates **gross pay** and **net pay (after taxes)** based on hourly rates and tax percentage.

## How It Works
- Enter the start and end times for each workday.
- If the work continues past midnight (e.g., from 16:00 to 17:00 the next day), type `1` in the **"Overnight work"** column.
- Enter your hourly rate in the designated cell and the tax rate if applicable.
- The tracker automatically calculates:
  - **Total hours worked per day**
  - **Total hours worked per month**
  - **Gross pay** = Total hours × Hourly rate
  - **Net pay** = Gross pay × (1 – Tax rate)
- Break times are subtracted automatically from the total hours.

## How to Use
1. Open the Excel file.
2. Fill in daily start and end times, breaks, and mark `1` in the **"Overnight work"** column if the shift crosses midnight.
3. Enter your hourly rate and tax rate in the designated cells.
4. Total hours, gross pay, and net pay are calculated automatically.
5. Use the summary sheet to analyze monthly totals or daily patterns.

## Notes
- The `Demo` sheet contains example entries to showcase functionality.
- The `Template` sheet is ready for your own data.
- Enable macros if prompted to ensure full functionality.
