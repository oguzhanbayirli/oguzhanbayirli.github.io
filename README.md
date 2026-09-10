# ShiftSheet

Staff rota, employee scheduling and timesheets inside Google Sheets™.

- **Site:** https://shiftsheet.me
- **Google Workspace Marketplace™:** https://workspace.google.com/marketplace/app/shiftsheet_employee_timesheet_shift_sche/898911767169

ShiftSheet turns a Google Sheets™ tab into a monthly staff rota, checks it for
scheduling mistakes, and prints a signed timesheet for each person. There is no
separate app to learn and no account to create — you open a spreadsheet you
already own.

## What it does

It draws a monthly work schedule grid, one row per person and one column per
day. Then it checks that grid for the seven mistakes a spreadsheet lets through
silently:

- overlapping shifts
- double bookings
- too little rest between shifts
- over the weekly hour limit
- too many consecutive days
- unknown shift codes
- names in the grid that are not on the staff list

Findings go to their own tab with the person and the date on each line, so you
fix them before the week starts rather than after someone does not turn up.

It also produces a printable timesheet per person, month by month, with employee
and manager signature lines already on it.

## Free and paid

The free version has no head-count limit and no time limit: the rota, all seven
checks, normal, overtime and total hours per person, and a per-person timesheet.

The paid version is a single $39 payment — not a subscription — and adds pay
rates, overtime pay and labour cost on the totals sheet, plus printing every
timesheet in one go.

## Privacy

The add-on makes no network calls of any kind. Your schedule stays in your own
Google account.

## Guides

- [Seven mistakes in a Google Sheets shift schedule, and the formulas that find them](https://shiftsheet.me/google-sheets-shift-schedule-mistakes.html)
- [Overnight shift hours in Google Sheets, and why the total comes out negative](https://shiftsheet.me/google-sheets-overnight-shift-hours.html)
- [Weekly overtime on a monthly Google Sheets rota, and the week that belongs to two months](https://shiftsheet.me/google-sheets-weekly-overtime-monthly-rota.html)

## About this repository

This repository holds the shiftsheet.me website. The add-on source is kept
separately.

Google Sheets™, Google Drive™, Gmail™, Google Calendar™ and Google Workspace
Marketplace™ are trademarks of Google LLC. ShiftSheet is an independent product
and is not endorsed by or affiliated with Google LLC.
