---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0031"
target_object: "T1104"
stix_relationship_id: "relationship--a6962782-1942-42f5-a627-f205376e2ec2"
---
# Relationship 3469: S0031 — uses → T1104

**Source object:** [[01 ATT&CK/S0031 - BACKSPACE|S0031: BACKSPACE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1104 - Multi-Stage Channels|T1104: Multi-Stage Channels]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[BACKSPACE](https://attack.mitre.org/software/S0031) attempts to avoid detection by checking a first stage command and control server to determine if it should connect to the second stage server, which performs "louder" interactions with the malware.(Citation: FireEye APT30)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a6962782-1942-42f5-a627-f205376e2ec2`.
