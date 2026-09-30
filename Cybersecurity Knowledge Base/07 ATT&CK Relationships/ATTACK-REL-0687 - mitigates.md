---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1048"
target_object: "T1027.006"
stix_relationship_id: "relationship--15e815c2-ab92-4490-b0ba-f94dddfe8b01"
---
# Relationship 0687: M1048 — mitigates → T1027.006

**Source object:** [[01 ATT&CK/M1048 - Application Isolation and Sandboxing|M1048: Application Isolation and Sandboxing]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1027.006 - HTML Smuggling|T1027.006: HTML Smuggling]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Use Browser Extensions or Built-in Security Tools that: - Monitor JavaScript API calls such as `Blob`, `URL.createObjectURL,` and `msSaveOrOpenBlob` - Intercept and analyze HTML5 `download` attributes for suspicious payload generation - Alert or block behaviors that match known HTML smuggling patterns (e.g., blob-to-disk payload construction) Apply Content Security Policy (CSP) headers to: - Restrict inline JavaScript and dynamic script generation - Disallow downloads from unauthorized sources or blob URIs - Prevent cross-origin resource sharing (CORS) abuse commonly used in smuggling chains Enable or enforce enterprise browser security controls, such as: - Endpoint's Network Protection and Attack Surface Reduction (ASR) rules, which can block Office and browser processes from creating child processes or writing to disk in suspicious ways - Google Chrome Enterprise Policies, which can control file download behavior, restrict extensions, and isolate risky browsing environments Deploy browser sandboxing solutions that can isolate JavaScript execution environments and enforce behavioral policy restrictions

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--15e815c2-ab92-4490-b0ba-f94dddfe8b01`.
