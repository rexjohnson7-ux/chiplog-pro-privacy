# Privacy Policy for ChipLog Pro

**Effective Date:** February 4, 2026  
**Last Updated:** February 4, 2026

## Introduction

ChipLog Pro ("the App") is committed to protecting your privacy. This Privacy Policy explains how we handle information when you use our AI-powered electronic component scanner application.

## Data Collection

**ChipLog Pro does not collect, store, or transmit any personal information.**

The App operates entirely on your device and does not:
- Collect personal data (name, email, phone number, etc.)
- Track your location
- Gather usage analytics
- Share data with third parties
- Require user accounts or registration

## Camera Permission

ChipLog Pro requires access to your device's camera to function properly.

**How we use camera access:**
- Capture images of electronic components for identification
- Process images locally on your device
- Transmit images securely to our AI analysis service (see "AI Image Analysis" below)

**We do NOT:**
- Store captured images on external servers
- Use camera for any purpose other than component scanning
- Access your photo library without explicit permission
- Record video or audio

## Local Storage

All scanned component data is stored **locally on your device** using IndexedDB (browser storage).

**What is stored locally:**
- Component identification results (part numbers, manufacturers, descriptions)
- Captured images associated with scans
- Project information and metadata
- User preferences (theme settings)

**Data control:**
- You have full control over your data
- Data can be deleted at any time via the "Purge Vault" feature
- Uninstalling the app removes all local data
- No data backup or cloud sync

## AI Image Analysis

ChipLog Pro uses Google's Gemini AI API to identify electronic components from captured images.

**How it works:**
1. You capture an image using the app
2. Image is transmitted via secure HTTPS to our backend proxy server
3. The proxy forwards the image to Google's Gemini API
4. AI analyzes the image and returns identification data
5. Results are displayed in the app

**Data handling during AI analysis:**
- Images are transmitted securely using HTTPS encryption
- Images are processed by Google's Gemini AI service
- Images are **not stored** by our backend or Google's service after analysis
- Only the identification results (text data) are returned to the app
- No personal information is included in API requests

**Google Gemini Privacy:**
Images sent to Gemini are subject to Google's privacy policy and data processing practices. According to Google's enterprise API terms, data sent via API is not used to train AI models. For more information, see: https://policies.google.com/privacy

## Data Export

ChipLog Pro allows you to export your scanned data in two formats:

- **PDF:** Multi-page document with component details and images
- **ZIP:** Contains a CSV spreadsheet and high-resolution images

**Exported data:**
- Saved locally to your device
- Shared via your device's native share sheet
- Under your complete control
- Not transmitted to external servers

## Third-Party Services

ChipLog Pro uses the following third-party services:

**Google Gemini API:**
- Purpose: AI-powered component identification
- Data shared: Captured images (temporarily, for analysis only)
- Privacy Policy: https://policies.google.com/privacy

**No other third-party services** (no analytics, advertising, or tracking SDKs)

## Data Security

We implement appropriate security measures to protect data:

- HTTPS encryption for all network communications
- Secure authentication tokens for API access
- App secret validation to prevent unauthorized API access
- Local data stored using IndexedDB with browser security protections

## Your Rights

You have the following rights regarding your data:

- **Access:** All data is stored locally and accessible within the app
- **Deletion:** Use "Purge Vault" to delete all scanned data, or delete individual items
- **Export:** Export your data at any time via PDF or ZIP
- **Control:** Complete control over what you scan and save

## Children's Privacy

ChipLog Pro does not knowingly collect data from children under the age of 13. The App does not target children and is designed for professional and hobbyist use in electronics work.

## Changes to This Privacy Policy

We may update this Privacy Policy from time to time. Changes will be reflected by updating the "Last Updated" date at the top of this policy.

**How you'll be notified:**
- Updates will be published in the App Store listing
- Significant changes will be highlighted in app update notes
- Continued use of the App after changes constitutes acceptance

## Contact Information

If you have questions about this Privacy Policy or how ChipLog Pro handles data, please contact:

**Email:** rex.johnson7@gmail.com  
**Developer:** Rex Johnson  
**Support:** https://github.com/rexjohnson/chiplog-pro

## Compliance

This Privacy Policy is designed to comply with:
- Apple App Store Review Guidelines
- Google Play Store Developer Policies
- General Data Protection Regulation (GDPR) principles
- California Consumer Privacy Act (CCPA) principles

## Summary

To be clear:
- ✅ **No personal data collection**
- ✅ **No user tracking or analytics**
- ✅ **All data stored locally on your device**
- ✅ **Images sent to AI service only for analysis (not stored)**
- ✅ **You control all your data**
- ✅ **No advertising or third-party sharing**

---

**By using ChipLog Pro, you agree to this Privacy Policy.**

Last reviewed: February 4, 2026

