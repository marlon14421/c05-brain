---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1154"
target_object: "T1040"
stix_relationship_id: "relationship--fc57736f-1142-4385-82a1-8baf6b6eedc6"
---
# Relationship 9236: S1154 — uses → T1040

**Source object:** [[01 ATT&CK/S1154 - VersaMem|S1154: VersaMem]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1040 - Network Sniffing|T1040: Network Sniffing]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[VersaMem](https://attack.mitre.org/software/S1154) hooked the Catalina application filter chain `doFilter` on compromised systems to monitor all inbound requests to the local Tomcat web server, inspecting them for parameters like passwords and follow-on Java modules.(Citation: Lumen Versa 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fc57736f-1142-4385-82a1-8baf6b6eedc6`.
