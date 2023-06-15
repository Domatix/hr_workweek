# HR Workweek

This repository is designed to manage and track employee workweeks in Odoo. It integrates with the Timesheets module to create workweeks for each employee, allowing for a clear record of worked hours based on the employee's assigned calendar. Additionally, it enables employees to compensate for overtime hours.

## Features

- Automatic creation of workweeks for employees based on their assigned calendar.
- Option for employees to compensate overtime hours by choosing between time off or financial compensation.
- Weekly generated emails: one of them is sent to each employee with their own analytics for the week (hours worked, hours to work and total difference), and the other one is sent only to previously selected users, displaying analytics for all employees sorted by their calendars, excluding any calendars set in the settings.

## Usage

1. Each workweek will be created and displayed in the Timesheets module and in each employee's form.
2. Employees can request a compensation, and their compensation manager will decide whether it is approved or not.
3. Compensation managers can be directly set in the employee's form.
4. There are settings available for the weekly reports, including summary notification recipients and excluded calendars.

## Available addons

| addon        | version           | summary  |
| ------------- |:-------------:| :-----|
| hr_workweek |15.0.1.0.1  | Manage employee workweeks and compensations. |
| hr_workweek_reports |15.0.1.0.1  | Receive weekly emails with analytics. |