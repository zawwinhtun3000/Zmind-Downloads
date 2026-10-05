# Zmind Android 1.0.11 staging

- Moves the staging account API to https://staging.www.infobition.com.
- Uses /api/v1/identity/ for sign-in and account status, and /api/v1/zmind/ for product services.
- Keeps the existing Android package and signing certificate for installation over the previous release.
- Staging only; production has not changed.

Validation: Flutter analysis passed, all 44 tests passed, and new and legacy staging API account responses and offline lease signatures passed verification.

Download: https://staging.www.infobition.com/download/apk

Immutable APK: https://raw.githubusercontent.com/zawwinhtun3000/Zmind-Downloads/cd0c06a9637f1784ca821054527dc0aa5b06bbb9/staging/1.0.11/Zmind-Android-1.0.11-staging.apk

SHA-256: `5e2d986336429b74ccda97399f2a4b9994e2355f1df464145627146032179a01`
