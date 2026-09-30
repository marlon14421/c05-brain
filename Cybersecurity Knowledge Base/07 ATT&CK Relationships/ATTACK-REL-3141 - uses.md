---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0061"
target_object: "T1047"
stix_relationship_id: "relationship--fd763f17-409d-428b-825c-f731b0ad88cc"
---
# Relationship 3141: G0061 — uses → T1047

**Source object:** [[01 ATT&CK/G0061 - FIN8|G0061: FIN8]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1047 - Windows Management Instrumentation|T1047: Windows Management Instrumentation]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[FIN8](https://attack.mitre.org/groups/G0061)'s malicious spearphishing payloads use WMI to launch malware and spawn `cmd.exe` execution. [FIN8](https://attack.mitre.org/groups/G0061) has also used WMIC and the [Impacket](https://attack.mitre.org/software/S0357) suite for lateral movement, as well as during and post compromise cleanup activities.(Citation: FireEye Obfuscation June 2017)(Citation: Bitdefender FIN8 July 2021)(Citation: FireEye Know Your Enemy FIN8 Aug 2016)(Citation: Symantec FIN8 Jul 2023)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fd763f17-409d-428b-825c-f731b0ad88cc`.
