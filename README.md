# FUTURE_CS_02
# Phishing Email Analysis using Email Header Analyzer

## Overview

This project analyzes a suspicious email using Gmail's Original Message feature and Google Messageheader Analyzer. The goal was to identify phishing indicators, review email authentication results, and assess potential risks.

## Tools Used

* Gmail (Show Original)
* Google Messageheader Analyzer
* Microsoft Word
* GitHub

## Analysis Process

1. Collected a suspicious email from the Spam folder.
2. Examined the email header.
3. Analyzed SPF, DKIM, and DMARC results.
4. Reviewed sender information and links.
5. Identified suspicious indicators and classified the risk.

## Key Findings

* Sender: [noreply@jobalertshub.com](mailto:noreply@jobalertshub.com)
* Subject: BSNL Junior Telecom Officer Job Notification
* SPF: PASS
* DKIM: PASS
* DMARC: PASS
* Email contained tracking links.
* Sender domain did not match the organization being represented.

## Risk Assessment

**Classification:** Suspicious

Although authentication checks passed, the email used a third-party domain and was delivered to the Spam folder, requiring caution before interacting with any links.

## Recommendations

* Verify sender domains.
* Avoid clicking unknown links.
* Check email authenticity before sharing information.
* Report suspicious emails.

## Deliverables

* Email Header Analysis
* Risk Assessment
* Security Recommendations
* Final PDF Report
