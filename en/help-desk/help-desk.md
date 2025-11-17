---
title: Incident Reporting and Analysis
icon: lucide/headset
---

# :lucide-headset: Incident Reporting and Analysis

!!! Abstract "Incident Reporting"

    - Save the original email (.eml) and related materials/evidence.
    - Send the original email as an attachment to <ssd@ocf.tw>.

The following outlines the accepted reportable scenarios, as well as key steps and evidence-collection guidelines for reporting phishing and scam emails, to help you provide information safely and effectively.

## Reportable Incident Types

### Fake or malicious websites

- Impersonating government, schools, healthcare, banks, shopping, or fundraising sites, or short links redirecting to suspected phishing pages.
- What to include in your report: full URL (including parameters), screenshots, and time discovered. If available: DNS/WHOIS information, TLS certificate fingerprint or serial number.

### Fake social media accounts/pages

- Impersonating official accounts or customer service, fake investment groups, fake giveaway campaigns.
- What to include in your report: account or post links, screenshots, snippets of suspicious direct messages.

### Malicious apps or distribution of fake apps

- Impersonated government or banking apps; unofficial APK download pages.
- What to include in your report: store page or download page link. If available: file hash (SHA-256), signature/developer info, screenshots (do not execute the file).

### Account security anomalies

- Suspected compromise of official accounts, unusual login alerts from other locations, or your organization appearing on suspected leak lists (PTT, Dcard, forums, Telegram channels).
- What to include in your report: source link or screenshots, affected platform and account ID, and time.

### DDoS or service availability anomalies

- Widespread simultaneous connection failures, multiple reports from users in the same area, DNS resolution anomalies.
- What to include in your report: time window, location or ISP. If available: error screen/code, brief traceroute/dig results.

### Extortion/threat emails and deepfake voice

- Impersonation of government agencies or supervisors, sextortion emails, AI deepfake voice scams.
- What to include in your report: raw email files (.eml, .msg), audio files, caller number and call log screenshots.

!!! warning "Evidence Collection and Safety Reminders"

    - Do not click suspicious links, enable macros, or run unknown files.
    - If you have obtained a file, do not open it.
    - If there is immediate financial loss or payment fraud, first call the 165 Anti-Fraud Consultation Hotline, or report to the police (110) as appropriate, and notify us at the same time for assessment.

## Phishing and Scam Email Reporting Guidelines

1. Common preliminary indicators
    - Suspicious sender domain; looks similar to the official domain but is different (e.g., letter substitution).
    - Urgent call to action (update account, sign in again, make a payment) with a link or attachment.
    - Displayed link differs from the actual destination; uses URL shorteners or unusual domains.
    - Attachments are executables or macro-enabled documents (.exe, .scr, .js, macro-enabled Office files).
    - Urgent tone, messy formatting, grammatical errors, or unreasonable requests.

2. What to include in your report
    - Raw email file: .eml or .msg with full headers and body (see the next section for how to export/package the email).
    - Screenshots: the received message view, the actual URL shown when hovering over links, attachment filename and size.
    - Basic info: time received (including time zone), sender address, subject line, and the email service/client and version you use.
    - If the email contains links or files: provide the link text and the actual URL (copy via right-click), and the file hash (SHA-256; do not execute the file).

3. How to export the raw email
    - Gmail (web): Open the email → More (three dots) in the top-right → Show original → Download Original (.eml).
    - Outlook (Windows desktop): Open the email → File → Save As → choose Outlook Item (.msg). For headers: File → Properties → copy Internet headers.
    - Outlook on the Web (OWA): Open the email → More (three dots) → View → View message details (you can copy headers). Some versions support downloading .eml (Download).
    - Apple Mail (macOS): Select the email → File → Save As… → choose “Raw Message” or .eml. Or View → Message → All Headers.
    - Mozilla Thunderbird: Select the email → File → Save As → File (.eml).

!!! info "Gmail (web)"

    - For Gmail (web), you can refer to [this page](https://ssd.ocf.tw/help/index.html){target="_blank"} for the steps.

## How We Handle Your Report

- Upon receipt, we immediately assign a case ID, perform initial malicious-file screening, and de-identify data.
- Expert analysis and community collaboration: Without involving personal data or sensitive operational information, we share publishable threat indicators (e.g., domains, IPs, file hashes, sample characteristics, attack techniques) with trusted security communities and academic/research partners for joint analysis; NDAs or restricted sharing are used when necessary.
- Cross-entity notification and referral: After confirmation, we notify affected parties according to roles and responsibilities, refer cases to platform providers or competent authorities as needed, and provide the community with updates on remediation progress and mitigation guidance.
- External feedback and information release: Once handling is complete, we provide concise feedback and publishable [IoCs](https://www.cloudflare.com/learning/security/what-are-indicators-of-compromise/){target="_blank"} (indicators of compromise; no personal data) and regularly compile trend insights and protective recommendations. Where appropriate, we include de-identified indicators in public/shared threat intelligence systems (e.g., [STIX/TAXII](https://www.cloudflare.com/learning/security/what-is-stix-and-taxii/){target="_blank"}) to help the ecosystem quickly block propagation.
- Transparency and protection: We strictly comply with personal data and legal requirements, share only the minimum necessary information, and protect reporter identities and sensitive details.

## How to Report

1. Prepare the raw email or materials required for the relevant scenario above.
2. Send the raw email and materials as email attachments to <ssd@ocf.tw>.
