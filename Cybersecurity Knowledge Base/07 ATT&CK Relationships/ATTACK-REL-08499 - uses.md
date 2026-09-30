---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9035"
target_object: "T1102.002"
stix_relationship_id: "relationship--d8a1fe73-2234-4d74-a09c-a84b9cf3e7d1"
---
# Relationship 8499: S9035 — uses → T1102.002

**Source object:** [[01 ATT&CK/S9035 - LAMEHUG|S9035: LAMEHUG]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1102.002 - Bidirectional Communication|T1102.002: Bidirectional Communication]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[LAMEHUG](https://attack.mitre.org/software/S9035) has used the Hugging Face API to query the Qwen2.5-Coder-32B-Instruct LLM to generate one-line Windows commands for the collection of system information and documents in specific folders on compromised hosts. [LAMEHUG](https://attack.mitre.org/software/S9035) subsequently executed the returned commands and exfiltrated the collected files and information to adversary-controlled C2 servers.(Citation: Nov AI Threat Tracker)(Citation: Splunk LAMEHUG SEP 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d8a1fe73-2234-4d74-a09c-a84b9cf3e7d1`.
