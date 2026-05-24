# Phishing Analysis Lab

## Overview
SOC Analyst home lab - analyzing phishing emails using industry tools and methodology.

## Tools Used
- Kali Linux
- oletools (olevba)
- curl / ipinfo.io
- Manual header analysis

## Skills Demonstrated
- Email header analysis
- SPF / DKIM / DMARC validation
- IP investigation and geolocation
- IOC documentation
- Threat report writing

## Sample Analysis Summary
- Identified typosquatting domain (amaz0n vs amazon)
- Detected SPF, DKIM, DMARC all failed = spoofed sender
- Traced email origin to suspicious VPS server
- Extracted malicious .tk domain URL
- Produced full IOC report with remediation recommendations
