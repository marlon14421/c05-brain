---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "M1034"
attack_type: "Mitigation"
source: MITRE ATT&CK
---
# M1034: Limit Hardware Installation — Defensive Application

## Source record

- [[01 ATT&CK/M1034 - Limit Hardware Installation|M1034 source record]]
- ATT&CK class: Mitigation
- Platforms: Not specified
- Tactics: Not specified

## Source context

Prevent unauthorized users or groups from installing or using hardware, such as external drives, peripheral devices, or unapproved internal hardware components, by enforcing hardware usage policies and technical controls. This includes disabling USB ports, restricting driver installation, and implementing endpoint security tools to monitor and block unapproved devices. This mitigation can be implemented through the following measures: Disable USB Ports and Hardware Installation Policies: - Use Group Policy Objects (GPO) to disable USB mass storage devices: - Navigate to Computer Configuration > Administrative Templates > System > Removable Storage Access. - Deny write and read access to USB devices. - Whitelist approved devices using unique serial numbers via Windows Device Installation Policies. Deploy Endpoint Protection and Device Control Solutions: - Use tools like Microsoft Defender for Endpoint, Symantec Endpoint Protection, or Tanium to monitor and block unauthorized hardware. - Implement device control policies to allow specific hardware types (e.g., keyboards, mice) and block others. Harden BIOS/UEFI and System Firmware: - Set strong passwords for BIOS/UEFI access. - Enable Secure Boot to prevent rogue hardware components from loading unauthorized firmware. Restrict Peripheral Devices and Drivers: - Use Windows Device Manager Policies to block installation of unapproved drivers. - Monitor hardware installation attempts through endpoint monitoring tools. Disable Bluetooth and Wireless Hardware: - Use GPO or MDM tools to disable Bluetooth and Wi-Fi interfaces across systems. - Restrict hardware pairing to approved devices only. Logging and Monitoring: - Enable logging for hardware installation events in Windows Event Logs (Event ID 20001 for Device Setup Manager). - Use SIEM solutions (e.g., Splunk, Elastic Stack) to detect unauthorized hardware installation activities. *Tools for Implementation* USB and Device Control: - Microsoft Group Policy Objects (GPO) - Microsoft Defender for Endpoint - Symantec Endpoint Protection - McAfee Device Control Endpoint Monitoring: - EDRs - OSSEC (open-source host-based IDS) Hardware Whitelisting: - BitLocker for external drives (Windows) - Windows Device Installation Policies - Device Control BIOS/UEFI Security: - Secure Boot (Windows/Linux) Firmware management tools like Dell Command Update or HP Sure Start

## Defensive focus

Assess the control as an implementable safeguard with a defined owner, target population, configuration, exception path, and evidence of operation.

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Review checklist

- Which assets and versions support this control, and where are exceptions required?
- Does the control reduce the relevant exposure without disabling a legitimate business function?
- How is coverage measured and configuration drift detected?
- What compensating control applies where the primary safeguard is unavailable?
- What test demonstrates continued effectiveness after updates?

## Safe validation

Pilot configuration changes in a representative test group, obtain owner approval, and preserve a tested rollback plan. Define written scope, test window, accounts, data boundaries, and stop conditions in advance. Preserve only the evidence required to verify the control and protect it from unauthorized access.

## Evidence and response

Record the source and version, environment, time range, expected behavior, observations, alternative explanations, and telemetry gaps. A catalog mapping is a lead for analysis, not an incident finding. Escalate and contain only under approved response procedures; verify remediation with a measurable retest.

## Further reading

- [MITRE ATT&CK](https://attack.mitre.org/)
- [[../../04 Defensive Playbooks/Defensive Playbooks|Defensive Playbooks]]
- [[../../06 Sources/Source Register|Source Register and dataset caveats]]
