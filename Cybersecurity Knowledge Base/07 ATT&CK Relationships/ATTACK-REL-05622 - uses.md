---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0598"
target_object: "T1110.001"
stix_relationship_id: "relationship--ed00df58-4656-4c62-8ef1-8b859f46c1ed"
---
# Relationship 5622: S0598 — uses → T1110.001

**Source object:** [[01 ATT&CK/S0598 - P.A.S. Webshell|S0598: P.A.S. Webshell]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1110.001 - Password Guessing|T1110.001: Password Guessing]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[P.A.S. Webshell](https://attack.mitre.org/software/S0598) can use predefined users and passwords to execute brute force attacks against SSH, FTP, POP3, MySQL, MSSQL, and PostgreSQL services.(Citation: ANSSI Sandworm January 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ed00df58-4656-4c62-8ef1-8b859f46c1ed`.
