# Zmind Android 1.0.11 staging

- Moves the staging account API to https://staging.www.infobition.com.
- Uses /api/v1/identity/ for sign-in and account status, and /api/v1/zmind/ for product services.
- Keeps the existing Android package and signing certificate for installation over the previous release.
- Staging only; production has not changed.

Validation: Flutter analysis passed, all 44 tests passed, and new and legacy staging API account responses and offline lease signatures passed verification.
