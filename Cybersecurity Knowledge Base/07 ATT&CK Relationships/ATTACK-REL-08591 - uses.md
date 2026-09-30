---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0259"
target_object: "T1027"
stix_relationship_id: "relationship--549fdc30-5269-48ee-9dc8-60db8deb836a"
---
# Relationship 8591: S0259 — uses → T1027

**Source object:** [[01 ATT&CK/S0259 - InnaputRAT|S0259: InnaputRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027 - Obfuscated Files or Information|T1027: Obfuscated Files or Information]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[InnaputRAT](https://attack.mitre.org/software/S0259) uses an 8-byte XOR key to obfuscate API names and other strings contained in the payload.(Citation: ASERT InnaputRAT April 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--549fdc30-5269-48ee-9dc8-60db8deb836a`.
