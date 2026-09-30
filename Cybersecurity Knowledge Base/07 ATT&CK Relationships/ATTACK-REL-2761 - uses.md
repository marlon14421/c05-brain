---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0136"
target_object: "T1020"
stix_relationship_id: "relationship--ae8a95fa-c0ad-40b4-a573-a9441ed94fab"
---
# Relationship 2761: S0136 — uses → T1020

**Source object:** [[01 ATT&CK/S0136 - USBStealer|S0136: USBStealer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1020 - Automated Exfiltration|T1020: Automated Exfiltration]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[USBStealer](https://attack.mitre.org/software/S0136) automatically exfiltrates collected files via removable media when an infected device connects to an air-gapped victim machine after initially being connected to an internet-enabled victim machine. (Citation: ESET Sednit USBStealer 2014)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ae8a95fa-c0ad-40b4-a573-a9441ed94fab`.
