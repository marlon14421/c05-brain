---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1023"
target_object: "T1554"
stix_relationship_id: "relationship--5f14394c-2b44-4187-a2a4-7ccb4109fdb1"
---
# Relationship 8761: G1023 — uses → T1554

**Source object:** [[01 ATT&CK/G1023 - APT5|G1023: APT5]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1554 - Compromise Host Software Binary|T1554: Compromise Host Software Binary]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[APT5](https://attack.mitre.org/groups/G1023) has modified legitimate binaries and scripts for Pulse Secure VPNs including the legitimate DSUpgrade.pm file to install the ATRIUM webshell for persistence.(Citation: Mandiant Pulse Secure Zero-Day April 2021)(Citation: Mandiant Pulse Secure Update May 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5f14394c-2b44-4187-a2a4-7ccb4109fdb1`.
