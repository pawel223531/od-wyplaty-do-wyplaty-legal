# Google Play checklist

Use this checklist when preparing **Od wypłaty do wypłaty / From Payday to Payday** for Google Play.

## Store listing

- App name PL: `Od wypłaty do wypłaty`
- App name EN: `From Payday to Payday`
- Short description PL: `Prosty budżet od wypłaty do wypłaty: wydatki, kalendarz i prognoza wolnych środków.`
- Short description EN: `A simple payday-to-payday budget: expenses, calendar, and free funds forecast.`
- Privacy policy URL PL: `https://pawel223531.github.io/od-wyplaty-do-wyplaty-legal/`
- Privacy policy URL EN: `https://pawel223531.github.io/od-wyplaty-do-wyplaty-legal/en/`

## Data safety notes

The app stores budget data locally on the user's device.

The app uses Google Mobile Ads SDK / AdMob. According to Google's Google Mobile Ads SDK disclosure, the SDK may collect and share data for ads, analytics, diagnostics, and fraud prevention, including:

- IP address
- device or advertising identifiers
- ad interactions
- diagnostics
- device information

Confirm the final Data Safety answers in Play Console based on the final app build and AdMob settings.

## App content

- Privacy policy: required and provided.
- Ads: yes, app contains ads.
- Target audience: choose the correct age group before release.
- Data safety: complete with AdMob disclosures.
- Financial features: this app helps track personal budget; it does not provide financial advice, loans, banking, investing, or payments.

## Before production

- Replace test AdMob IDs with production AdMob IDs.
- Confirm `targetSdkVersion` is 36 or newer.
- Upload an Android App Bundle (`.aab`) for production, not only a debug APK.
- Test on at least one small and one large screen.
