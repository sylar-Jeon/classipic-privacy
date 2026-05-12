# Privacy Policy (ClassiPic)

**Effective date: May 6, 2026**
**Last updated: May 12, 2026**

ClassiPic ("the App") respects your privacy. This policy explains what information the App accesses, how it is used, and what rights you have. The App is operated by an individual developer based in the Republic of Korea.

---

## 1. Operator

| Item | Detail |
|---|---|
| App | ClassiPic |
| Operator | sylar |
| Contact | sylar32a+support@gmail.com |
| Privacy Officer | sylar (same address) |

## 2. Core Principle: 100% On-device

The App analyzes your photos and metadata **entirely on your device**. Your photos are never uploaded to the operator's or any third party's server for the purpose of analysis or classification.

## 3. Information We Access

### 3.1 Device-only access (no external transmission)

| Data | Purpose | Storage |
|---|---|---|
| Photo library (PHAsset) | AI classification, album display, duplicate detection | Local device only |
| Photo location metadata (EXIF GPS) | Location-based classification | Local device only |
| App preferences (UserDefaults) | Settings, locked-album IDs, classification preferences | Local device only |
| StoreKit receipts | Lifetime purchase verification | Apple StoreKit |
| Reverse-geocoding coordinates (CLGeocoder) | Location-based auto-naming (e.g. "Gangnam-gu, Yeoksam-dong"): the photo's GPS coordinates are sent to Apple's servers to be resolved to a textual address | Only the resolved address text is cached on device (90 days). The operator stores neither the coordinates nor the resolved address. |

### 3.2 Information used for ads / measurement (free tier only)
The App shows ads from Google AdMob to free-tier users. The following may be transmitted to Google during ad delivery:
- Advertising identifier (IDFA), only if you allow it via Apple's App Tracking Transparency prompt
- Approximate IP address (city/country level)
- Device model, OS version, app version
- Ad impression and click events

If you deny ATT, ads are still shown but limited to non-personalized ads. See Google's privacy policy:
https://policies.google.com/privacy

### 3.3 Information we do NOT collect
The App does not collect:
- Account credentials, email, name, or phone number
- Contacts, calendar, or health data
- Your photos or classification results (no server storage)
- Transmission of location data to the operator's servers or to advertising third parties (note: coordinates may be sent to Apple's CLGeocoder service for location-based naming — see section 3.1)

## 4. Retention and Deletion

Data stored locally (preferences, classification cache) is removed when you uninstall the App. Because the App does not store your data on any server, no separate deletion request is required.

## 5. Your Rights

You can at any time:
- Revoke Photos / Location access via iOS Settings → ClassiPic
- Revoke advertising identifier access via iOS Settings → Privacy → Tracking
- Delete the App to wipe all local data
- Contact us at the email above for additional requests

## 6. Children

The App is not directed at children under 13 (or 14 in Korea), and we do not knowingly collect their personal information.

## 7. Third Parties

| Party | Role | Data |
|---|---|---|
| Google LLC (AdMob) | Ad delivery (free tier) | IDFA (if allowed), IP, device info, ad events |
| Apple Inc. (StoreKit) | In-app purchase processing | Apple-ID-scoped purchase receipts |
| Apple Inc. (CLGeocoder) | Reverse geocoding for location-based auto-naming | GPS coordinates from photo EXIF |

We do not sell or share your information beyond the entries above.

## 8. Changes

We will post updates to this page when this policy changes. For material changes, we will also note the change in the App's release notes.

## 9. Contact

For privacy questions, please contact:
- Email: sylar32a+support@gmail.com

---

> 한국어 버전: [Privacy Policy (Korean)](privacy-kr.html)
