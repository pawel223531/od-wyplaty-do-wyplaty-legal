# Data Safety draft for Google Play

This is a working draft for the Google Play Console Data Safety form. Confirm it against the final production build and AdMob configuration before publishing.

## Core app data

The app stores budget data locally on the device:

- payday day,
- payday amount,
- expense names,
- expense amounts,
- categories,
- notes,
- skipped occurrences,
- payday additions.

This budget data is not sent to the app publisher's server by the app.

## Ads / Google Mobile Ads SDK

The app uses Google Mobile Ads SDK / AdMob for banner and interstitial ads.

Google's SDK may collect/share data for:

- advertising,
- analytics,
- fraud prevention,
- security,
- diagnostics.

Possible data types according to Google Mobile Ads SDK documentation:

- IP address,
- device or other IDs, including advertising ID,
- app interactions / ad interactions,
- diagnostics,
- device information.

## Suggested Play Console answers

Use carefully; final answers are the developer's responsibility.

- Does your app collect or share user data? **Yes**, because Google Mobile Ads SDK may collect/share data.
- Is all collected user data encrypted in transit? **Yes**, for Google SDK network communication.
- Can users request data deletion? For local budget data, users can delete app data or uninstall the app. If no account/server-side user data exists, explain that no account-based server data is stored by the publisher.
- Does the app use advertising ID? **Yes**, because AdMob is included.
- Does the app contain ads? **Yes**.

## Financial services declaration note

The app helps users plan a personal budget. It does not provide:

- loans,
- credit,
- investment services,
- banking services,
- payments,
- financial advice.

In Play Console, describe it as a budgeting/personal finance utility rather than a regulated financial service.
