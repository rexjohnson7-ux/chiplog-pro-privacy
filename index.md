<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Privacy Policy - ChipLog Pro | Long Run Investments</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        .privacy-content {
            max-width: 800px;
            margin: 0 auto;
            padding: 4rem 0;
        }

        .privacy-content h2 {
            margin-top: 2.5rem;
            margin-bottom: 0.75rem;
        }

        .privacy-content p,
        .privacy-content li {
            color: var(--text-secondary);
            line-height: 1.8;
            margin-bottom: 0.5rem;
        }

        .privacy-content ul {
            padding-left: 1.5rem;
            margin-bottom: 1rem;
        }

        .privacy-content ol {
            padding-left: 1.5rem;
            margin-bottom: 1rem;
            color: var(--text-secondary);
        }

        .summary-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 1rem;
            margin-top: 1rem;
        }

        .summary-item {
            background: rgba(255, 255, 255, 0.04);
            border: 1px solid rgba(255, 255, 255, 0.08);
            border-radius: 10px;
            padding: 1rem;
            font-size: 0.9rem;
            color: var(--text-secondary);
        }

        .last-updated {
            display: inline-block;
            background: rgba(99, 102, 241, 0.15);
            border: 1px solid rgba(99, 102, 241, 0.3);
            border-radius: 6px;
            padding: 4px 12px;
            font-size: 0.85rem;
            color: var(--accent);
            margin-bottom: 2rem;
        }
    </style>
</head>

<body>
    <header>
        <div class="container">
            <nav>
                <div class="logo"><a href="index.html" style="color:var(--text-primary);">Long Run Investments</a></div>
                <div class="nav-links">
                    <a href="index.html">Home</a>
                    <a href="chiplog-pro.html">Our Apps</a>
                    <a href="support.html">Support</a>
                </div>
            </nav>
        </div>
    </header>

    <main class="container">
        <div class="privacy-content">
            <h1>Privacy Policy for ChipLog Pro</h1>
            <span class="last-updated">Last Updated: April 7, 2026</span>

            <h2>Introduction</h2>
            <p>ChipLog Pro ("the App") is committed to protecting your privacy. This Privacy Policy explains how we
                handle information when you use our AI-powered object identification scanner application.</p>

            <h2>Data Collection</h2>
            <p>ChipLog Pro does not collect, store, or transmit any personal information. The App operates primarily on
                your device and does <strong>NOT:</strong></p>
            <ul>
                <li>Collect personal data (name, email, phone number, etc.)</li>
                <li>Track your location</li>
                <li>Link usage analytics, scans, or vault data to your personal identity</li>
                <li>Share data with third parties beyond what is described below</li>
                <li>Require user accounts or registration</li>
            </ul>

            <h2>Camera Permission</h2>
            <p>ChipLog Pro requires access to your device's camera for scanning objects. How we use camera access:</p>
            <ul>
                <li>Capture images of objects for identification</li>
                <li>Transmit images securely to our AI analysis service (see "AI Image Analysis" below)</li>
            </ul>
            <p>We do NOT:</p>
            <ul>
                <li>Store captured images on external servers</li>
                <li>Use camera for any purpose other than object scanning</li>
                <li>Access your photo library without explicit permission</li>
                <li>Record video or audio</li>
            </ul>

            <h2>Local Storage</h2>
            <p>All scanned object data is stored locally on your device. What is stored locally:</p>
            <ul>
                <li>Object identification results (part numbers, manufacturers, descriptions)</li>
                <li>Captured images associated with scans</li>
                <li>Project information and metadata</li>
                <li>User preferences (theme settings)</li>
            </ul>
            <p>Data control:</p>
            <ul>
                <li>You have full control over your data</li>
                <li>Data can be deleted at any time via the "Purge Vault" feature</li>
                <li>Uninstalling the app removes all local data</li>
                <li>No data backup or cloud sync</li>
            </ul>

            <h2>AI Image Analysis</h2>
            <p>ChipLog Pro uses a third-party Artificial Intelligence service to identify objects from captured images. How it
                works:</p>
            <ol>
                <li>You capture an image using the app</li>
                <li>Image is securely transmitted to our AI provider</li>
                <li>AI analyzes the image and returns identification data</li>
                <li>Results are displayed in the app and saved locally</li>
            </ol>
            <p>Data handling during AI analysis:</p>
            <ul>
                <li>Images are transmitted securely using HTTPS encryption</li>
                <li>Images are processed by our AI provider</li>
                <li>Images are <strong>NOT</strong> stored by our AI provider after analysis</li>
                <li>Only the identification results (text data) are returned to the app</li>
                <li>No personal information is included in API requests</li>
            </ul>
            <p>Our AI provider processes your images momentarily for the sole purpose of identifying the object. Once the identification is complete, the image data is discarded from the processing servers. Our AI provider is strictly prohibited from using your transmitted images to train their AI models.</p>

            <h2>In-App Purchases</h2>
            <p>ChipLog Pro offers a Pro subscription through Apple's App Store in-app purchase system. Subscription
                payments are processed entirely by Apple. Long Run Investments LLC does not collect or store any payment
                information. Subscriptions are managed via your Apple ID settings.</p>

            <h2>Data Export</h2>
            <p>ChipLog Pro allows you to export your scanned data (PDF or ZIP). Exported data is:</p>
            <ul>
                <li>Saved locally to your device</li>
                <li>Shared via your device's native share sheet</li>
                <li>Under your complete control</li>
                <li>Not transmitted to external servers</li>
            </ul>

            <h2>Third-Party Services</h2>
            <p>ChipLog Pro uses the following third-party services:</p>
            <ul>
                <li><strong>Third-Party AI Analysis</strong> — Purpose: AI-powered component identification. Data shared:
                    Captured images (temporarily, for analysis only).</li>
                <li><strong>RevenueCat</strong> — Purpose: Manages in-app subscriptions and unlocks premium features. Data shared: Anonymous app-user IDs and purchase history to validate subscriptions securely.</li>
                <li><strong>PostHog</strong> — Purpose: Anonymous product telemetry to understand aggregate app usage, identify crashes, and improve the app. Data shared: Anonymous usage events (e.g., "scan initiated", "vault item saved"). This data is strictly non-personally identifiable.</li>
            </ul>
            <p>No advertising SDKs or cross-site tracking systems are included in the app. Your Vault contents are never sent to analytics providers.</p>

            <h2>Data Security</h2>
            <p>We implement appropriate security measures to protect data:</p>
            <ul>
                <li>HTTPS encryption for all network communications</li>
                <li>Secure authentication tokens for API access</li>
                <li>App secret validation to prevent unauthorized API access</li>
                <li>Local data stored securely on your device</li>
            </ul>

            <h2>Your Rights</h2>
            <p>You have the following rights regarding your data:</p>
            <ul>
                <li><strong>Access:</strong> All data is stored locally and accessible within the app</li>
                <li><strong>Deletion:</strong> Use "Purge Vault" to delete all scanned data, or delete individual items
                </li>
                <li><strong>Export:</strong> Export your data at any time via PDF or ZIP</li>
                <li><strong>Control:</strong> Complete control over what you scan and save</li>
            </ul>

            <h2>Children's Privacy</h2>
            <p>ChipLog Pro does not knowingly collect data from children under the age of 13. The App is designed for
                professional and hobbyist use in electronics work.</p>

            <h2>Changes to This Privacy Policy</h2>
            <p>We may update this Privacy Policy from time to time. Changes will be reflected by updating the "Last
                Updated" date at the top of this policy. Significant changes will be highlighted in app update notes.
                Continued use of the App after changes constitutes acceptance.</p>

            <h2>Contact Information</h2>
            <p>If you have questions about this Privacy Policy or how ChipLog Pro handles data, please contact:</p>
            <p><strong>Long Run Investments LLC</strong><br>
                Email: <a href="mailto:support@longruninv.com">support@longruninv.com</a><br>
                Support page: <a href="support.html">longruninv.com/support</a></p>

            <h2>Compliance</h2>
            <p>This Privacy Policy is designed to comply with:</p>
            <ul>
                <li>Apple App Store Review Guidelines</li>
                <li>General Data Protection Regulation (GDPR) principles</li>
                <li>California Consumer Privacy Act (CCPA) principles</li>
            </ul>

            <h2>Summary</h2>
            <div class="summary-grid">
                <div class="summary-item">✅ No personal data collection</div>
                <div class="summary-item">✅ Anonymous telemetry only</div>
                <div class="summary-item">✅ All data stored locally on your device</div>
                <div class="summary-item">✅ Images sent to AI service only for analysis (not stored)</div>
                <div class="summary-item">✅ You control all your data</div>
                <div class="summary-item">✅ No advertising or third-party sharing</div>
            </div>
        </div>
    </main>

    <footer>
        <div class="container">
            <p>&copy; 2026 Long Run Investments LLC. All rights reserved.</p>
            <p><a href="index.html">Home</a> | <a href="support.html">Support</a></p>
        </div>
    </footer>
</body>

</html>
