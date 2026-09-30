---
type: "Data Component"
source: MITRE ATT&CK
id: "DC0035"
source_url: "https://attack.mitre.org/datacomponents/DC0035"
created: "2021-10-20"
modified: "2026-05-12"
---
# DC0035: Process Access

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Data Component  
**ATT&CK ID:** DC0035  
**Platforms:** Not specified  
**Tactics:** Not specified

## Source description

Refers to an event where one process attempts to open another process, typically to inspect or manipulate its memory, access handles, or modify execution flow. Monitoring these access attempts can provide valuable insight into both benign and malicious behaviors, such as debugging, inter-process communication (IPC), or process injection. *Data Collection Measures:* - Endpoint Detection and Response (EDR) Tools: - EDR solutions that provide telemetry on inter-process access and memory manipulation. - Sysmon (Windows): - Event ID 10: Captures process access attempts, including: - Source process (initiator) - Target process (victim) - Access rights requested - Process ID correlation - Windows Event Logs: - Event ID 4656 (Audit Handle to an Object): Logs access attempts to system objects. - Event ID 4690 (Attempted Process Modification): Can help identify unauthorized process changes. - Linux/macOS Monitoring: - AuditD: Monitors process access through syscall tracing (e.g., `ptrace`, `open`, `read`, `write`). - eBPF/XDP: Used for low-level monitoring of kernel process access. - OSQuery: Query process access behavior via structured SQL-like logging. - Procmon (Process Monitor) and Debugging Tools: - Windows Procmon: Captures real-time process interactions. - Linux strace / ptrace: Useful for tracking process behavior at the system call level.

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: DC0035](https://attack.mitre.org/datacomponents/DC0035)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
