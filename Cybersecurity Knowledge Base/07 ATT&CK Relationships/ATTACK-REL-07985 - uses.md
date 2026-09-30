---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0436"
target_object: "T1204.001"
stix_relationship_id: "relationship--d15c7116-2d00-48cd-9003-1ab6fc4a0076"
---
# Relationship 7985: S0436 — uses → T1204.001

**Source object:** [[01 ATT&CK/S0436 - TSCookie|S0436: TSCookie]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1204.001 - Malicious Link|T1204.001: Malicious Link]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[TSCookie](https://attack.mitre.org/software/S0436) has been executed via malicious links embedded in e-mails spoofing the Ministries of Education, Culture, Sports, Science and Technology of Japan.(Citation: JPCert TSCookie March 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d15c7116-2d00-48cd-9003-1ab6fc4a0076`.
