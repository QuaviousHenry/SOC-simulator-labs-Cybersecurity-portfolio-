# SOC Simulator: Hijacked Discord Invite to ClickFix Loader

## Overview
This repository contains my documented solution and investigation notes for the **"Hijacked Discord Invite to ClickFix Loader: Tracing the Lure"** training operation on **SOC Simulator**[span_2](start_span)[span_2](end_span). As a self-taught cybersecurity student, I completed this lab to build practical skills in threat analysis, log investigation, and Security Operations Center (SOC) workflows.

## Lab Details
* **Platform:** SOC Simulator[span_3](start_span)[span_3](end_span)
* **Operation:** Hijacked Discord Invite to ClickFix Loader: Tracing the Lure[span_4](start_span)[span_4](end_span)
* **Difficulty:** Easy[span_5](start_span)[span_5](end_span)
* **Core Skills:** SIEM, Firewall (FW) Analysis, Threat Intelligence (INTEL)[span_6](start_span)[span_6](end_span)
* **Status:** Completed (100%)[span_7](start_span)[span_7](end_span)

## Scenario Summary
A finance analyst at Halcyon Wealth Partners followed a recycled Discord invite that quietly redirected their browser to a fake verification page. Upon executing the page's prompts, the workstation was compromised within an hour, running a remote-access trojan (RAT) and an info-stealer that exfiltrated browser data[span_8](start_span)[span_8](end_span).

## Investigation Steps & Findings
1. **Tracing the Lure:** Analyzed proxy and firewall logs to trace how the user moved from the Discord invitation link to the malicious verification domain.
2. **Endpoint Monitoring:** Inspected workstation telemetry to identify the execution patterns of the ClickFix loader.
3. **C2 Beacon Detection:** Tracked network traffic to locate outbound Command and Control (C2) beaconing activity.
4. **Data Theft Identification:** Confirmed data exfiltration signatures associated with the info-stealer shipping sensitive browser data out of the network.

## Key Takeaways
* Gained hands-on experience tracing social engineering vectors (Discord lures) using proxy and firewall logs.
* Learned how to identify initial loader execution and map out C2 communication channels.
* Built foundational incident response workflows applicable to entry-level SOC roles.
