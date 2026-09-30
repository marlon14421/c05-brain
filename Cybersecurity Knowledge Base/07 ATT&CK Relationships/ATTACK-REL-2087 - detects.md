---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0275"
target_object: "T1140"
stix_relationship_id: "relationship--9c92cb61-d6a7-4dc3-9bf8-1ebcc1b2cc73"
---
# Relationship 2087: DET0275 — detects → T1140

**Source object:** [[01 ATT&CK/DET0275 - Detect Adversary Deobfuscation or Decoding of Files and Payloads|DET0275: Detect Adversary Deobfuscation or Decoding of Files and Payloads]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1140 - Deobfuscate-Decode Files or Information|T1140: Deobfuscate/Decode Files or Information]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9c92cb61-d6a7-4dc3-9bf8-1ebcc1b2cc73`.
