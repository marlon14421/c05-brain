---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1047"
target_object: "T1566.003"
stix_relationship_id: "relationship--9b91755d-2b83-438c-bd25-0e71c540310a"
---
# Relationship 0654: M1047 — mitigates → T1566.003

**Source object:** [[01 ATT&CK/M1047 - Audit|M1047: Audit]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1566.003 - Spearphishing via Service|T1566.003: Spearphishing via Service]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Implement auditing and logging for interactions with third-party messaging services or collaboration platforms. Monitor user activity and review logs for signs of suspicious links, downloads, or file exchanges that could indicate spearphishing attempts. Effective auditing allows for the quick identification of malicious activity originating from compromised service accounts.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9b91755d-2b83-438c-bd25-0e71c540310a`.
