---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0029"
target_object: "T1105"
stix_relationship_id: "relationship--8c6af9f3-6301-4d49-afff-1fda7db57e3a"
---
# Relationship 8218: C0029 — uses → T1105

**Source object:** [[01 ATT&CK/C0029 - Cutting Edge|C0029: Cutting Edge]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [Cutting Edge](https://attack.mitre.org/campaigns/C0029), threat actors leveraged exploits to download remote files to Ivanti Connect Secure VPNs.(Citation: Volexity Ivanti Zero-Day Exploitation January 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8c6af9f3-6301-4d49-afff-1fda7db57e3a`.
