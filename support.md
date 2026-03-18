<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SavingsFlow - Help &amp; Support</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
            line-height: 1.6;
            color: #333;
            background-color: #f5f5f7;
            padding: 20px;
        }
        
        .container {
            max-width: 800px;
            margin: 0 auto;
            background: white;
            padding: 40px;
            border-radius: 12px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }
        
        h1 {
            color: #1d1d1f;
            font-size: 2.5em;
            margin-bottom: 10px;
            font-weight: 700;
        }
        
        h2 {
            color: #1d1d1f;
            font-size: 1.5em;
            margin-top: 30px;
            margin-bottom: 15px;
            font-weight: 600;
        }
        
        h3 {
            color: #1d1d1f;
            font-size: 1.15em;
            margin-top: 20px;
            margin-bottom: 10px;
            font-weight: 600;
        }
        
        p {
            margin-bottom: 15px;
            color: #333;
        }
        
        ul, ol {
            margin-left: 30px;
            margin-bottom: 15px;
        }
        
        li {
            margin-bottom: 8px;
        }

        a {
            color: #0071e3;
            text-decoration: none;
            font-weight: 500;
        }

        a:hover {
            text-decoration: underline;
        }
        
        .contact-box {
            background-color: #e8f5e9;
            border-left: 4px solid #4caf50;
            padding: 20px;
            margin: 20px 0;
            border-radius: 4px;
        }

        .contact-box strong {
            color: #2e7d32;
        }

        .warning {
            background-color: #f8d7da;
            border-left: 4px solid #dc3545;
            padding: 15px;
            margin: 20px 0;
            border-radius: 4px;
        }

        .info {
            background-color: #e3f2fd;
            border-left: 4px solid #2196f3;
            padding: 15px;
            margin: 20px 0;
            border-radius: 4px;
        }

        hr {
            border: none;
            border-top: 1px solid #e0e0e0;
            margin: 30px 0;
        }

        .encryption-list {
            background-color: #f5f5f7;
            padding: 15px 15px 15px 45px;
            border-radius: 8px;
            margin: 15px 0;
        }

        .encryption-list li {
            margin-bottom: 6px;
        }

        .copyright {
            text-align: center;
            color: #86868b;
            font-size: 0.85em;
            margin-top: 40px;
            font-style: italic;
        }

        .subtitle {
            color: #86868b;
            font-size: 1em;
            margin-bottom: 30px;
        }
        
        @media (max-width: 600px) {
            .container {
                padding: 20px;
            }
            
            h1 {
                font-size: 2em;
            }
            
            h2 {
                font-size: 1.3em;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>SavingsFlow Support</h1>
        <p class="subtitle">Help, frequently asked questions, and how to get in touch.</p>

        <div class="contact-box">
            <p><strong>Contact Us</strong></p>
            <p>For support, questions, or feedback:</p>
            <p><strong>Email:</strong> <a href="mailto:pandemoniumsoftwareltd@gmail.com">pandemoniumsoftwareltd@gmail.com</a></p>
            <p style="margin-bottom: 0;">We aim to respond within 48 hours.</p>
        </div>

        <hr>

        <h2>Frequently Asked Questions</h2>

        <h3>I forgot my passcode. How do I get back in?</h3>
        <p>You have two recovery options:</p>
        <ol>
            <li><strong>Recovery Key</strong> &mdash; The 16-character code (XXXX-XXXX-XXXX-XXXX) shown when you first set up the app. Enter it on the lock screen to reset your passcode.</li>
            <li><strong>Security Question</strong> &mdash; Answer the question you set during onboarding to reset your passcode.</li>
        </ol>
        <div class="warning">
            <p>If you have lost both your recovery key and cannot answer your security question, your data cannot be recovered. This is by design &mdash; your data is encrypted with AES-256 and we have no access to it under any circumstances.</p>
        </div>

        <hr>

        <h3>What happens if I delete the app?</h3>
        <p>All data is permanently deleted. Export an encrypted backup first if you want to keep your data. Go to Settings &rarr; Export Backup before deleting the app.</p>

        <hr>

        <h3>How do I transfer data to a new phone?</h3>
        <ol>
            <li>Open SavingsFlow on your old device</li>
            <li>Go to Settings &rarr; Export Backup</li>
            <li>Set a password and save the .savingsflow file</li>
            <li>Send the file to your new device (AirDrop, Files, email)</li>
            <li>Install SavingsFlow on your new device</li>
            <li>Go to Settings &rarr; Import Backup</li>
            <li>Select the file and enter your password</li>
        </ol>
        <div class="info">
            <p>Your backup file is encrypted with 600,000 rounds of key hardening. Without your password, the file cannot be opened &mdash; so make sure you remember the password you set.</p>
        </div>

        <hr>

        <h3>Is my data stored in the cloud?</h3>
        <p>No. All financial data is stored exclusively on your device and encrypted with AES-256. We do not operate servers that store your data. We cannot access it under any circumstances.</p>

        <hr>

        <h3>How do I cancel my subscription?</h3>
        <ol>
            <li>Open your iPhone <strong>Settings</strong></li>
            <li>Tap your <strong>name</strong> at the top</li>
            <li>Tap <strong>Subscriptions</strong></li>
            <li>Tap <strong>SavingsFlow</strong></li>
            <li>Tap <strong>Cancel Subscription</strong></li>
        </ol>
        <p>You retain access to premium features until the end of your current billing period. Your data is never deleted when a subscription lapses.</p>

        <hr>

        <h3>How do I request a refund?</h3>
        <p>All purchases are processed by Apple. Visit <a href="https://reportaproblem.apple.com" target="_blank">reportaproblem.apple.com</a> or contact Apple Support to request a refund. We do not process refunds directly.</p>

        <hr>

        <h3>Are my mortgage calculations accurate?</h3>
        <p>SavingsFlow provides estimates for planning purposes only. Actual mortgage terms, rates, and fees offered by lenders may differ. Always confirm figures with your lender before making financial decisions.</p>

        <hr>

        <h3>What encryption does SavingsFlow use?</h3>
        <ul class="encryption-list">
            <li>AES-256 encryption on all data at rest</li>
            <li>Encryption key stored in your device&rsquo;s secure hardware (iOS Keychain)</li>
            <li>100,000-round passcode hashing</li>
            <li>600,000-round backup encryption with HMAC-SHA256 tamper detection</li>
            <li>Face ID / Touch ID biometric authentication (optional)</li>
            <li>Escalating lockout on failed passcode attempts</li>
            <li>Privacy blur in app switcher</li>
        </ul>

        <hr>

        <h2>Report a Bug</h2>
        <p>Email us at <a href="mailto:pandemoniumsoftwareltd@gmail.com">pandemoniumsoftwareltd@gmail.com</a> with:</p>
        <ul>
            <li>What you expected to happen</li>
            <li>What actually happened</li>
            <li>Your device model and iOS version</li>
            <li>Screenshots if possible</li>
        </ul>

        <hr>

        <p style="text-align: center; margin-top: 30px;">
            <a href="privacy-policy.html">Privacy Policy</a> &nbsp;&bull;&nbsp;
            <a href="terms-of-service.html">Terms of Service</a>
        </p>

        <p class="copyright">&copy; 2026 Pandamonium Software Ltd. All rights reserved.</p>
    </div>
</body>
</html>
