# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.0] - 2026-03-20

### Added
- **Initial public release** of BoardGame Loans.
- **Loan Management:** Complete backend UI (add, edit, renew, return, delete).
- **Waitlist System:** Track games in queue, with `Waitlisted` and `Available for Pickup` status logic.
- **Copy Tracking:** Identify specific physical copies using internal codes and copy numbers (1-10). 
- **Shortcodes:** `[bg_loans_list]` and `[bg_loans_waitlist]` to dynamically display data on frontend pages.
- **Visual Feedback:** Alerts and styling for Overdue items and Waitlisted games currently returning to the library.
- **Settings Page:** Customizable UI. Toggle Advanced forms, Waitlist logic, date formats, and sorting preferences.
- **Integrations:** Full compatibility with TablePress IDs for advanced catalog linking.
- **Internationalization (i18n):** Full support for translation, including a complete Italian `.po` dictionary bundle.
