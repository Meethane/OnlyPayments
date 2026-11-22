# OnlyPayments

A direct peer-to-peer bill settlement discovery platform built natively in Kotlin and Jetpack Compose. OnlyPayments connects verified individuals facing urgent bills directly with donors—without holding funds or acting as an escrow middleman.

## Download
Grab the latest signed Android APK from the **[Releases](../../releases)** page.

## Key Features
- **Zero-Escrow Direct Settlement:** Pay directly via UPI intents or official merchant payment links.
- **KYC & Invoice Verification:** Mandatory invoice and government ID photo verification with admin review before listings go live.
- **Anti-Abuse Architecture:** Hardware device binding, email verification gates, 30-day submission cooldowns, and server-enforced Firestore security rules.
- **Shareable Impact Cards:** Generates high-resolution PNG settlement summary cards for donors.

## Tech Stack
- **UI:** Kotlin, Jetpack Compose (Material 3)
- **Backend:** Firebase Authentication & Cloud Firestore
- **Security:** R8/ProGuard obfuscation, APK signature verification, and server-side RBAC
