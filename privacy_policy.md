# Privacy Policy for Sinhala Guitar Chords

**Last Updated:** September 29, 2026  
**Effective Date:** September 29, 2026  
**Application Name:** Sinhala Guitar Chords  
**Developer / Publisher:** Amila Sampath  
**Contact Email:** [amila.champlnx@gmail.com]  

---

## 1. Introduction & Overview

Welcome to **Sinhala Guitar Chords** (referred to in this Privacy Policy as **"we"**, **"our"**, **"us"**, or the **"App"**). We respect your privacy and are committed to protecting it through transparent and privacy-preserving practices.

This Privacy Policy explains how our mobile application handles user information when you download, install, and use Sinhala Guitar Chords on mobile operating systems including **Google Android** and **Apple iOS**.

Our application is built on a **"Privacy by Design"** and **"Local-First"** architecture. **We do not require you to create an account, we do not collect personal identifying information, and we do not track you across other apps or websites.**

Please read this Privacy Policy carefully to understand our practices regarding your data. By downloading, accessing, or using the App, you agree to the collection and use of information in accordance with this policy.

---

## 2. Summary of Key Privacy Principles

| Category | Policy Summary |
| :--- | :--- |
| **Personal Data Collected** | **None.** We do not collect names, email addresses, phone numbers, or physical addresses. |
| **User Account / Sign-In** | **Not Required.** Full app features are available immediately without registration. |
| **Third-Party Advertising** | **None.** We do not include any third-party ad networks (e.g., AdMob, Unity, Meta Ads). |
| **Third-Party Analytics / Tracking** | **None.** We do not use user-tracking or behavioral analytics SDKs (e.g., Firebase Analytics, Mixpanel). |
| **Location Data** | **Not Accessed.** We do not request, access, or collect GPS or fine/coarse location data. |
| **Device Hardware Permissions (Microphone, Camera, etc.)** | **None Requested.** The App does not request or require access to your device microphone, camera, contacts, or GPS location. |
| **Local Storage (Sandbox)** | Used solely to save your on-device preferences (theme, font size, auto-scroll speed, favorites) in local device memory. |
| **Data Selling or Sharing** | **Never.** We do not sell, rent, monetize, or trade any user data to third parties. |

---

## 3. Information We Collect and Process

### A. Personal Information
We **do not collect, solicit, or store** any personally identifiable information (PII) such as:
- First or last name
- Email address
- Phone number
- Physical address
- Government identification or financial data
- Social media profiles or biometric identifiers

You can use all features of the App completely anonymously.

### B. Device Hardware Permissions & Sensor Data
The App is designed to function strictly as an offline chord reference, lyric viewer, and transposer without requiring sensitive device hardware permissions.
- **No Microphone Access:** The App does not request, access, or utilize your device's microphone or audio recording capabilities.
- **No Camera or Photos Access:** The App does not request access to your device camera, photo gallery, or media files.
- **No Location Tracking:** The App does not request, access, or track GPS, coarse, or fine location data.
- **No Contacts or Phone State:** The App does not read your device contacts, phone status, or system accounts.

### C. Local On-Device Storage (Preferences & Offline Data)
The App stores non-personal configuration data locally on your device within the secure OS sandbox using local storage. This data never leaves your device:
- **Display & Interface Preferences:** Light mode, dark mode, or system default; user-selected Material 3 seed color preset or custom hex color.
- **Musical Preferences:** Preferred accidental notation (Sharps `#` vs. Flats `♭`), default auto-scroll speed for lyrics.
- **Favorites & Bookmarks:** List of song IDs marked as favorites by you for quick access.
- **Recently Viewed Songs:** Recent song IDs stored locally to populate your "Recently Played" list.
- **Database Schema Version:** Local flag indicating the version of the bundled offline song database to handle seamless database updates.

**Note:** This data is strictly stored locally. We have no remote server receiving, indexing, or backing up this local data.

---

## 4. Third-Party Libraries and External Network Access

The App is designed to function primarily as an **offline-first application**.

However, to ensure a modern visual experience, the App utilizes select, reputable third-party software packages:

### A. Google Fonts (`google_fonts` SDK)
- **Purpose:** The App utilizes Google Fonts to display clean, modern typography for lyrics, chords, and UI elements.
- **Data Handled:** When a specific font weight or character glyph is rendered for the first time and has not already been cached locally on your device, the `google_fonts` library fetches the required font file over an encrypted HTTPS connection from Google's content delivery network (`fonts.gstatic.com`).
- **Network Headers:** Like any standard internet connection, your device's operating system transmits standard HTTP request headers to Google's servers, which include your IP address, device operating system version, and user-agent.
- **Privacy Assurance:** Google Fonts operates independently from authenticated Google accounts. Google's documentation states that Google Fonts does not set or send cookies, does not collect user credentials, and uses IP addresses solely to serve font assets efficiently and diagnose rare operational anomalies.
- For more details, consult [Google's Privacy Policy](https://policies.google.com/privacy) and the [Google Fonts Privacy FAQ](https://developers.google.com/fonts/faq/privacy).

### B. No Advertising or Tracking SDKs
- We **do not** embed SDKs from Google AdMob, Meta Audience Network, Unity Ads, AppLovin, ironSource, or any other mobile advertising network.
- We **do not** embed third-party analytics trackers, session recorders, crash telemetry brokers, or user profiling tools (such as Firebase Analytics, Adjust, AppsFlyer, or Flurry).

---

## 5. Google Play Store "Data Safety" Disclosures

To comply with the Google Play Developer Policy and the **Google Play Data Safety** declaration, here is the official classification of how data is handled:

### Data Collection & Sharing Declaration:
- **Data Collected:** **No user data is collected** to be transmitted off-device or stored on external servers.
- **Data Shared:** **No user data is shared** with third-party companies, marketers, or data brokers.
- **Sensitive Permissions:** The App requests **no sensitive runtime permissions** (such as `RECORD_AUDIO`, `CAMERA`, or `ACCESS_FINE_LOCATION`).
- **Security Practices:**
  - **Data Transfer Encryption:** All network requests made by third-party font libraries use secure HTTPS/TLS protocols.
  - **Local Sandbox Storage:** User preferences and favorites are stored strictly within the private application directory governed by Android filesystem permissions.
  - **Independent Security Review:** The App follows standard industry practices for local data isolation.
- **Account Creation / Deletion:** Because the App does not require an account, there are no cloud accounts or credentials to delete. All local data can be erased directly by resetting preferences in the App or clearing app storage in Android settings.

---

## 6. Apple App Store "App Privacy" Nutrition Label Disclosures

In accordance with Apple App Store Review Guidelines (Section 5.1 - Privacy and Security) and the **App Privacy** nutrition label requirements in App Store Connect:

### A. Data Used to Track You
**None.** The App does not track users across apps and websites owned by other companies. The App does not access the Apple Advertising Identifier (IDFA), does not use the App Tracking Transparency (ATT) framework, and does not engage in cross-site tracking or data brokering.

### B. Data Linked to You
**None.** No personal data is collected or linked to your identity, Apple ID, device identity, or contact info.

### C. Data Not Linked to You
**None.** The App does not collect unlinked analytics or diagnostic data. (Network interactions with font servers during dynamic font downloads are transient HTTP requests governed by standard CDN delivery).

---

## 7. Data Retention and Deletion

Because all your user data (such as favorite songs, recent history, and custom theme colors) is stored **exclusively on your physical device**:

1. **In-App Data Reset:** You can clear your customized preferences and local database anytime by navigating to:
   - **Settings > Reset Database / Clear Data**
2. **Device-Level Data Erasure:** You can immediately erase all local application state, cache, and database files through your operating system:
   - *Android:* Settings > Apps > Sinhala Guitar Chords > Storage & Cache > Clear Storage
   - *iOS:* Deleting the App automatically removes all sandboxed documents and `NSUserDefaults` preferences.
3. **Uninstalling the App:** Uninstalling or deleting Sinhala Guitar Chords from your mobile device permanently purges all local databases, preferences, and cached assets.

We do not retain backup copies of your local settings on any remote servers.

---

## 8. Children’s Privacy (COPPA & GDPR-K Compliance)

Our App is safe for users of all ages and is suitable for musical education and hobbyists. 

- We **do not knowingly collect, request, or maintain** personal information from children under the age of 13 (or under 16 in the European Economic Area / UK), in strict compliance with the **Children’s Online Privacy Protection Act (COPPA)**, the **EU General Data Protection Regulation (GDPR)**, and Google Play's **Families Policy**.
- Because no personal information is solicited, collected, or transmitted by the App, children can practice and learn guitar chords without privacy risks.
- If you are a parent or guardian and believe that your child has provided us with personal information, please contact us immediately at **[amila.champlnx@gmail.com]**, and we will take immediate steps to address your concern.

---

## 9. Rights Under Global Privacy Laws

Depending on your jurisdiction, you may have specific statutory rights regarding personal data:

### A. European Economic Area (EEA) & United Kingdom (GDPR / UK GDPR)
Under the General Data Protection Regulation, individuals have rights regarding their personal data, including the right to access, rectify, port, erase, or restrict processing. Because our App does not collect or transmit personal identifiers or store data on remote servers, your local data remains entirely in your direct custody on your device.

### B. California Residents (CCPA / CPRA)
Under the California Consumer Privacy Act, as amended by the California Privacy Rights Act:
- **Right to Know / Access:** Disclosed in this Privacy Policy.
- **Right to Delete:** You can delete your local data at any time as detailed in Section 7.
- **Right to Opt-Out of Sale / Sharing:** **We do not sell, rent, or share personal information with third parties for monetary or commercial consideration.** We have not sold or shared any personal information in the preceding 12 months.
- **Non-Discrimination:** We do not discriminate against any user for exercising their privacy rights.

---

## 10. Information Security

We value your trust and prioritize the security of your device:
- The App operates within the secure sandboxed application environment enforced by Android and iOS.
- No network ports are opened on your device, and no background services listen for remote incoming connections.
- Communication with external font content delivery networks occurs strictly over secure **Transport Layer Security (TLS/HTTPS)**.

While no software or electronic storage mechanism is 100% impenetrable, our approach of **not collecting or storing personal data on external servers** eliminates the risk of remote server database breaches.

---

## 11. Links to External Resources

The App may contain links to external web pages, such as our official website, terms of service, or music artist educational pages. If you click on a third-party link, you will be directed to that site via your external browser. Note that external sites are not operated by us. We strongly advise you to review the Privacy Policy of any third-party websites you visit. We have no control over and assume no responsibility for the content, privacy policies, or practices of any third-party sites or services.

---

## 12. Changes to This Privacy Policy

We may update our Privacy Policy from time to time to reflect modifications in our features, legal requirements, or store guidelines. 

- Any updates will be posted directly within this document, and the **"Last Updated"** date at the top of this policy will be revised.
- For material changes that impact how data is handled, we will provide noticeable in-app notifications or release notes upon updating the application through the Google Play Store and Apple App Store.
- We encourage you to review this Privacy Policy periodically for any updates. Continued use of the App following changes constitutes acceptance of the revised policy.

---

## 13. Contact Us

If you have questions, feedback, or concerns regarding this Privacy Policy or our privacy practices, please contact us at:

- **Developer / Publisher:** Amila Sampath
- **Support Email:** [amila.champlnx@gmail.com]
