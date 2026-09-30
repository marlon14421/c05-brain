---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0102"
target_object: "T1558.003"
stix_relationship_id: "relationship--72b30ddb-137c-4799-bacd-ab17aa2d01fc"
---
# Relationship 5879: G0102 — uses → T1558.003

**Source object:** [[01 ATT&CK/G0102 - Wizard Spider|G0102: Wizard Spider]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1558.003 - Kerberoasting|T1558.003: Kerberoasting]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Wizard Spider](https://attack.mitre.org/groups/G0102) has used Rubeus, MimiKatz Kerberos module, and the Invoke-Kerberoast cmdlet to steal AES hashes.(Citation: DFIR Ryuk's Return October 2020)(Citation: FireEye KEGTAP SINGLEMALT October 2020)(Citation: DHS/CISA Ransomware Targeting Healthcare October 2020)(Citation: DFIR Ryuk 2 Hour Speed Run November 2020)(Citation: Mandiant FIN12 Oct 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--72b30ddb-137c-4799-bacd-ab17aa2d01fc`.
