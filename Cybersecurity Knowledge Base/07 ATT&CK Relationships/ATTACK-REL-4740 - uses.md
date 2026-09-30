---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0357"
target_object: "T1557.001"
stix_relationship_id: "relationship--0318431e-ad44-44c7-97be-686d4efe79f4"
---
# Relationship 4740: S0357 — uses → T1557.001

**Source object:** [[01 ATT&CK/S0357 - Impacket|S0357: Impacket]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1557.001 - Name Resolution Poisoning and SMB Relay|T1557.001: Name Resolution Poisoning and SMB Relay]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Impacket](https://attack.mitre.org/software/S0357) modules like ntlmrelayx and smbrelayx can be used in conjunction with [Network Sniffing](https://attack.mitre.org/techniques/T1040) and [Name Resolution Poisoning and SMB Relay](https://attack.mitre.org/techniques/T1557/001) to gather NetNTLM credentials for [Brute Force](https://attack.mitre.org/techniques/T1110) or relay attacks that can gain code execution.(Citation: Impacket Tools)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0318431e-ad44-44c7-97be-686d4efe79f4`.
