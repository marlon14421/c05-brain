---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-781"
status: "Draft"
---
# CWE-781: Improper Address Validation in IOCTL with METHOD_NEITHER I/O Control Code

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** C, C++, Windows NT

## Description

The product defines an IOCTL that uses METHOD_NEITHER for I/O, but it does not validate or incorrectly validates the addresses that are provided.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** If METHOD_NEITHER is required for the IOCTL, then ensure that all user-space addresses are properly validated before they are first accessed. The ProbeForRead and ProbeForWrite routines are available for this task. Also properly protect and manage the user-supplied buffers, since the I/O Manager does not do this when METHOD_NEITHER is being used. See References.
- **Architecture and Design:** If possible, avoid using METHOD_NEITHER in the IOCTL and select methods that effectively control the buffer size, such as METHOD_BUFFERED, METHOD_IN_DIRECT, or METHOD_OUT_DIRECT.
- **Architecture and Design:** If the IOCTL is part of a driver that is only intended to be accessed by trusted users, then use proper access control for the associated device or device namespace. See References.

## Related weaknesses

- CWE-1285 (ChildOf)
- CWE-822 (CanPrecede)

## Source

- [CWE-781 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/781.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
