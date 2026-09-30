---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0037"
target_object: "T1204.002"
stix_relationship_id: "relationship--0b4b6ab2-df1f-4142-bbfa-5f26980d805b"
---
# Relationship 9421: C0037 — uses → T1204.002

**Source object:** [[01 ATT&CK/C0037 - Water Curupira Pikabot Distribution|C0037: Water Curupira Pikabot Distribution]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1204.002 - Malicious File|T1204.002: Malicious File]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Water Curupira Pikabot Distribution](https://attack.mitre.org/campaigns/C0037) delivered [Pikabot](https://attack.mitre.org/software/S1145) installers as password-protected ZIP files containing heavily obfuscated JavaScript, or IMG files containing an LNK mimicking a Word document and a malicious DLL.(Citation: TrendMicro Pikabot 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0b4b6ab2-df1f-4142-bbfa-5f26980d805b`.
