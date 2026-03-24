# Release Information 

- **Version**: 1.0.0 
- **Certified**: No 
- **Publisher**: Fortinet 
- **Compatible Version**: FortiSOAR 7.4.0 and later 

# Overview 

An active Interlock ransomware campaign is exploiting a critical vulnerability (CVE-2026-20131) in Cisco Secure Firewall Management Center (FMC), enabling unauthenticated remote code execution as root. The campaign combines edge-device exploitation, custom malware tooling, and double extortion tactics, indicating a mature and targeted ransomware operation. 

 The **Outbreak Response - Interlock Ransomware Attack** solution pack works with the Threat Hunt rules in [Outbreak Response Framework](https://github.com/fortinet-fortisoar/solution-pack-outbreak-response-framework/blob/release/2.3.0/docs/background-information.md#threat-hunt-rules) solution pack to conduct hunts that identify and help investigate potential Indicators of Compromise (IOCs) associated with this vulnerability within operational environments of *FortiSIEM*, *FortiAnalyzer*.

 The [FortiGuard Outbreak Page](https://www.fortiguard.com/outbreak-alert/interlock-ransomware) contains information about the outbreak alert **Outbreak Response - Interlock Ransomware Attack**. 

## Background: 

Amazon threat intelligence identified an active Interlock ransomware campaign exploiting a critical Cisco Secure Firewall Management Center (FMC) vulnerability (CVE-2026-20131), enabling unauthenticated remote code execution on internet-facing devices. The vulnerability was exploited as a zero-day for over a month prior to disclosure, allowing attackers to gain early and widespread access.

Attackers leveraged compromised firewall infrastructure as an initial foothold into enterprise networks, deploying a multi-stage attack chain that includes fileless implants, custom malware, and remote access tooling. The campaign emphasizes stealth, persistence, and extensive reconnaissance, including collection of system, credential, and network data before ransomware deployment.

Overall, the campaign highlights a shift toward edge device exploitation as a primary entry point, combining zero-day vulnerabilities, fileless techniques, and double extortion to achieve full enterprise compromise with reduced detection opportunities.

FortiGuard Labs has previously tracked the Interlock threat actor and its associated activities since its emergence in September 2024, with continued evolution observed through 2025 campaigns and into early 2026, including detailed analysis published on January 29, 2026. 

## Announced: 

Organizations should immediately apply Cisco security patches for Cisco Secure Firewall Management Center (FMC), specifically addressing CVE-2026-20131, to mitigate active exploitation risk associated with Interlock ransomware operations.
 

## Latest Developments: 

March 18, 2026: Amazon threat intelligence identified an active Interlock ransomware campaign exploiting CVE-2026-20131
https://aws.amazon.com/blogs/security/amazon-threat-intelligence-teams-identify-interlock-ransomware-campaign-targeting-enterprise-firewalls/

January 29, 2026: Inside a multi-month Interlock ransomware intrusion and the evolving tradecraft behind it
https://www.fortinet.com/blog/threat-research/interlock-ransomware-new-techniques-same-old-tricks 

# Next Steps
 | [Installation](./docs/setup.md#installation) | [Configuration](./docs/setup.md#configuration) | [Usage](./docs/usage.md) | [Contents](./docs/contents.md) | 
 |--------------------------------------------|----------------------------------------------|------------------------|------------------------------|
