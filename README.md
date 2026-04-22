# 23andMe Credential Stuffing Breach (2023) - Study Case

## Overview

This repository contains my technical analysis of the 23andMe data breach disclosed in October 2023.

The case is relevant because it shows how credential reuse, lack of mandatory MFA, and feature exposure can turn account-level compromise into large-scale data exposure.

## Repository Contents

- `REPORT.md`: full technical report with context, timeline, TTPs, impact, lessons learned, and defensive actions
- `fonti.txt`: source list used for the analysis

## Key Points

- attack pattern based on credential stuffing and password reuse
- compromise of customer accounts rather than platform-wide destructive intrusion
- secondary exposure amplified by the `DNA Relatives` feature
- strong defensive relevance for MFA policy, abuse controls, and identity monitoring

## Why This Case Matters

- it links identity security to privacy and compliance impact
- it shows how social or relationship features can amplify exposure
- it demonstrates the importance of monitoring leaked credentials and abnormal login behavior

## Main Sources

- [ArXiv - Anatomy of the 23andMe Credential Stuffing Attack](https://arxiv.org/pdf/2502.04303)
- [California Attorney General - Data Breach Notification](https://oag.ca.gov/system/files/CA%20AG%20-%20CA%20Notification%20Letters.pdf)
- [Wired - 23andMe Hack Exposed Genetic Data](https://www.wired.com/story/23andme-hack-genetic-data/)
- [TechCrunch - Hackers Access Millions of 23andMe Accounts](https://techcrunch.com/2023/10/09/23andme-hackers-breach-data/)
- [HIPAA Journal - 23andMe User Data Stolen](https://www.hipaajournal.com/23andme-user-data-stolen-credential-stuffing-campaign/)
- [UK ICO - Enforcement Action on 23andMe](https://ico.org.uk/action-weve-taken/enforcement/23andme-enforcement-notice/)

## Scope Note

This repository is a defensive study case based on public sources. It is intended for analysis, learning, and awareness.

## Author

Andrea Giovannoni
- LinkedIn: [Andrea Giovannoni](https://www.linkedin.com/in/andrea-giovannoni-253b1b54/)
- GitHub: [AndrewG83-sdt](https://github.com/AndrewG83-sdt)
