# Reword Chrome Extension Privacy Policy

**Effective Date:** December 18, 2024  
**Last Updated:** June 11, 2025

## Overview

Reword is a Chrome extension that helps users rephrase and improve text using AI technology. This privacy policy describes how we collect, use, and protect your information when you use our extension. 

**Recent Updates (June 11, 2025):** We have simplified our extension by removing background scripts, developer tools, and new tab functionality to create a more focused, privacy-conscious experience.

## 1. Information We Collect

### 1.1 Text Content
- **What we collect:** When you use the rephrasing feature, we temporarily process the text you select (or the entire input content if no text is selected)
- **How we collect it:** Text is captured only when you actively click the reword button on text inputs, textareas, or contentEditable elements
- **Purpose:** To provide AI-powered text rephrasing services
- **Scope:** Limited to specific text inputs where you activate the feature

### 1.2 Local Settings and Preferences
- **What we collect:** 
  - Button position preferences
  - Domain-specific customizations
  - API configuration settings (OpenRouter API key)
  - Hover/focus mode settings
  - Usage preferences and interface customizations
- **Storage location:** All preferences are stored locally in your browser using Chrome's storage API
- **Purpose:** To maintain your personalized extension experience

### 1.3 Technical Information
- **What we collect:** Basic extension usage patterns (locally stored)
- **Purpose:** To improve extension functionality and user experience
- **Note:** No background tracking or persistent monitoring occurs

## 2. How We Use Your Information

### 2.1 Text Processing
- Text content is sent directly to OpenRouter API (which routes to OpenAI) for rephrasing
- Text is **never stored** by our extension after processing
- Text is **never used** for training, analytics, or any purpose other than providing the immediate rephrasing service
- Each rephrasing request is independent and temporary
- **No Background Processing:** Text is only processed when you actively trigger the reword function

### 2.2 Local Preferences
- Settings are used solely to customize your extension experience
- No preference data is transmitted to external servers
- Data remains on your device until you uninstall the extension or clear browser storage

### 2.3 Simplified Architecture
- **No Background Scripts:** The extension does not run persistent background processes
- **No Persistent Monitoring:** The extension only activates when you interact with text inputs
- **Minimal Permissions:** Uses only essential permissions (activeTab, storage, sidePanel)

## 3. Information Sharing and Third-Party Services

### 3.1 OpenRouter/OpenAI Integration
- **Service:** All text processing occurs through OpenRouter, which routes requests to OpenAI's API
- **Data shared:** Only the text you choose to rephrase when you click the reword button
- **Third-party policies:**
  - [OpenRouter Privacy Policy](https://openrouter.ai/privacy)
  - [OpenAI Privacy Policy](https://openai.com/policies/privacy-policy)
- **Your responsibility:** By using our extension, you agree to these third-party terms

### 3.2 No Data Sales or Marketing
- We **do not** sell, rent, trade, or otherwise transfer your personal information to third parties
- We **do not** use your data for advertising or marketing purposes
- We **do not** share data with analytics services or data brokers
- We **do not** collect browsing history or monitor web activity

### 3.3 Legal Compliance
We may disclose information when required by law, court order, or legal process, or to:
- Protect our rights and property
- Investigate fraud or security issues
- Comply with legal obligations

## 4. Data Security and Protection

### 4.1 Transmission Security
- All API communications use HTTPS encryption
- Text data is transmitted securely to processing services
- No data is stored in transit
- Communication is limited to OpenRouter API endpoints only

### 4.2 Local Storage Security
- Preference data is stored using Chrome's secure storage APIs
- No sensitive personal information is collected or stored
- Data is isolated to your browser profile
- API keys are stored securely using Chrome's encrypted storage

### 4.3 Minimal Attack Surface
- **No Background Scripts:** Reduces potential security vulnerabilities
- **Limited Permissions:** Uses only essential permissions for core functionality
- **On-Demand Processing:** Extension only activates when explicitly triggered

## 5. Data Retention and Deletion

### 5.1 Text Content
- **Retention period:** Zero - text is immediately discarded after rephrasing
- **Deletion:** Automatic upon completion of each rephrasing request
- **No Caching:** Text content is never cached or stored temporarily

### 5.2 Local Preferences
- **Retention period:** Until you uninstall the extension or clear browser storage
- **Manual deletion:** Available through Chrome's extension management or browser data clearing

## 6. Your Rights and Choices

### 6.1 Access and Control
- Review stored preferences through Chrome DevTools (chrome://extensions/)
- Modify settings through the extension's options page
- Full control over when text processing occurs (manual trigger only)

### 6.2 Deletion Rights
- Uninstall the extension to remove all local data
- Clear browser storage to remove preferences
- Disable the extension to stop all data processing

### 6.3 Processing Control
- You have complete control over what text gets processed
- Extension only processes text when you explicitly click the reword button
- You can disable the extension at any time
- No automatic or background text processing occurs

## 7. Children's Privacy

Our extension is not intended for use by children under 13. We do not knowingly collect personal information from children under 13. If you become aware that a child has provided us with personal information, please contact us so we can delete such information.

## 8. International Users

This extension is operated from the United States. If you are using our extension from outside the United States, please be aware that your information may be transferred to, stored, and processed in the United States where our servers are located and through OpenRouter's infrastructure.

## 9. Changes to This Privacy Policy

### 9.1 Notification of Changes
We will notify users of significant changes through:
- Updates to this policy with a new "Last Updated" date
- Chrome Web Store listing updates
- In-extension notifications for major privacy-related changes

### 9.2 Continued Use
Your continued use of the extension after privacy policy changes constitutes acceptance of the updated terms.

## 10. Contact Information

**Developer:** Ming Fang  
**Email:** mfang0126@gmail.com  

For privacy-related questions, concerns, or requests, please contact us at the email address above.

## 11. Chrome Web Store Compliance

This privacy policy is maintained in compliance with Chrome Web Store Program Policies. The extension uses minimal permissions and follows privacy best practices.

---

**Note:** This policy specifically addresses Chrome extension functionality and complies with Chrome Web Store requirements for privacy disclosure. The extension has been simplified to reduce privacy concerns and focus on core text rewording functionality.