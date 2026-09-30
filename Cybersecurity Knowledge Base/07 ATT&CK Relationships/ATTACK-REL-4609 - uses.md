---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0170"
target_object: "T1132.001"
stix_relationship_id: "relationship--e68ff1c2-ef03-486b-96df-167a1652a97b"
---
# Relationship 4609: S0170 — uses → T1132.001

**Source object:** [[01 ATT&CK/S0170 - Helminth|S0170: Helminth]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1132.001 - Standard Encoding|T1132.001: Standard Encoding]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

For C2 over HTTP, [Helminth](https://attack.mitre.org/software/S0170) encodes data with base64 and sends it via the "Cookie" field of HTTP requests. For C2 over DNS, [Helminth](https://attack.mitre.org/software/S0170) converts ASCII characters into their hexadecimal values and sends the data in cleartext.(Citation: Palo Alto OilRig May 2016)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e68ff1c2-ef03-486b-96df-167a1652a97b`.
