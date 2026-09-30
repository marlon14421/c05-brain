---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0483"
target_object: "T1566.001"
stix_relationship_id: "relationship--b7d44225-31cf-4766-b585-debf0ed8d965"
---
# Relationship 3294: S0483 — uses → T1566.001

**Source object:** [[01 ATT&CK/S0483 - IcedID|S0483: IcedID]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1566.001 - Spearphishing Attachment|T1566.001: Spearphishing Attachment]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[IcedID](https://attack.mitre.org/software/S0483) has been delivered via phishing e-mails with malicious attachments.(Citation: Juniper IcedID June 2020)(Citation: DFIR_Sodinokibi_Ransomware)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b7d44225-31cf-4766-b585-debf0ed8d965`.
