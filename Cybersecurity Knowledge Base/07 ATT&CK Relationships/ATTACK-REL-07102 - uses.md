---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1056"
target_object: "T1583.006"
stix_relationship_id: "relationship--5065baaf-7a17-47b4-9880-73c834029e69"
---
# Relationship 7102: G1056 — uses → T1583.006

**Source object:** [[01 ATT&CK/G1056 - TeamPCP|G1056: TeamPCP]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1583.006 - Web Services|T1583.006: Web Services]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[TeamPCP](https://attack.mitre.org/groups/G1056) has set up Clouflare Tunnels for malware C2.(Citation: Wiz Trivy Compromise MAR 2026)(Citation: Aqua Security Blog Trivy Compromise APR 2026)(Citation: Aikido TeamPCP Telnyx MAR 2026)(Citation: Trend Micro TeamPCP MAY 2026) [TeamPCP](https://attack.mitre.org/groups/G1056) has also used the session messenger network for decentralized, encrypted exfiltration via *.getsession[.]org to recipient ID `05f9e609d79eed391015e11380dee4b5c9ead0b6e2e7f0134e6e51767a87323026`.(Citation: Wiz Mini Shai-Hulud MAY 2026)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5065baaf-7a17-47b4-9880-73c834029e69`.
