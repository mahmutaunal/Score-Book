# Store release checklist

## Required owner-provided values

- Host `privacy_policy_tr.md` and `privacy_policy_en.md` at public HTTPS URLs.
- Provide a monitored support email and support URL in both stores.
- Confirm the final app name, category, age rating, pricing and availability.
- Replace/sign with the production Android upload key and confirm Play App Signing.
- Confirm the Apple Developer team, distribution certificate and provisioning profile.

## Google Play

- Build and upload an Android App Bundle (`flutter build appbundle --release`).
- Complete Data safety. Current implementation: no off-device data collection or sharing; photos and profile/game data remain on-device.
- Add the public privacy policy URL, store descriptions, icon, feature graphic, phone/tablet screenshots and content rating.
- Test internal/closed tracks and pre-launch report before production rollout.

## App Store

- Archive with production signing and upload through Xcode/Transporter.
- Set App Privacy to “Data Not Collected” only while the implementation remains fully offline and third-party SDK behavior is unchanged.
- Add privacy policy URL, support URL, localized description, keywords, screenshots, age rating and review notes.
- Test on physical iPhone/iPad and distribute through TestFlight before App Review.

## QA gate

- `flutter analyze`
- `flutter test`
- Android release AAB build
- iOS release build without codesigning, then signed Xcode archive
- Verify backup/import, photo permissions, data deletion, dark mode, large text and Turkish/English on physical devices
