# Worked Examples for a Cybersecurity AI

The examples show how to reason from the vault. They are defensive workflows; adapt them to authorized systems and validate facts against current evidence. IDs below link to actual records in this vault.

## Example 1: Explain a suspicious email report

**User asks:** “A user received a link in an unexpected email. How should I investigate?”

**AI workflow:** Retrieve [[01 ATT&CK/T1566 - Phishing|T1566 Phishing]] and [[01 ATT&CK/T1566.002 - Spearphishing Link|T1566.002 Spearphishing Link]], then search for related detection and mitigation edges in [[07 ATT&CK Relationships/Index|the relationship index]]. Ask for mail gateway, identity, endpoint, and proxy telemetry availability.

**Good answer shape:** Explain that ATT&CK describes a technique, not proof of compromise. Recommend preserving the message and headers, checking whether the link was clicked using approved telemetry, examining authentication and endpoint events in the relevant time window, and following the organization’s incident process. Cite the IDs. Do not open the link from a production workstation or claim the sender’s identity is known.

## Example 2: Classify a code review finding

**User asks:** “A route checks authentication but appears to return another user’s record when I change an object ID.”

**AI workflow:** Search CWE for authorization and object-level access control weakness entries; retrieve the candidate note and its mitigation section. Use CAPEC as a threat-modeling aid only when it clarifies the pattern. Ask which framework and authorization model are in use before suggesting code changes.

**Good answer shape:** Separate observed behavior from possible classification. Explain that authentication establishes identity while authorization must check access to each requested object. Recommend a non-destructive test with two test accounts and synthetic records, then a server-side ownership/permission check and regression tests. Cite the exact CWE page after the classification is confirmed; say “candidate” if it is not.

## Example 3: Build a detection hypothesis

**User asks:** “Can we detect a process that disables host firewall protection?”

**AI workflow:** Retrieve [[01 ATT&CK/T1686.003 - Windows Host Firewall|T1686.003 Windows Host Firewall]] and its linked detection-strategy or analytic records. Inspect the relationship edge, then check which endpoint telemetry and operating-system events the environment actually collects.

**Good answer shape:** Give a hypothesis, required event fields, likely benign administration cases, test method in an isolated lab, and tuning/rollback plan. Do not invent event IDs or assert the user has a particular EDR. Request OS and telemetry details or consult vendor documentation before giving product-specific queries.

## Example 4: Assess credential exposure

**User asks:** “A secret may have been committed to a repository. What should we do?”

**AI workflow:** Search CWE records related to hard-coded or exposed credentials and ATT&CK credential techniques such as [[01 ATT&CK/T1552.001 - Credentials In Files|T1552.001 Credentials In Files]]. Retrieve only the relevant prevention and detection context.

**Good answer shape:** Treat the secret as compromised: restrict repository access, revoke/rotate the credential through the provider, inspect audit logs for use, remove it from active history as appropriate, and replace it with managed secret storage. Preserve evidence and coordinate with the owner. Do not paste the credential into the AI prompt or logs.

## Example 5: Investigate possible data transfer

**User asks:** “We saw unusual uploads to a cloud service.”

**AI workflow:** Retrieve [[01 ATT&CK/T1567 - Exfiltration Over Web Service|T1567 Exfiltration Over Web Service]] and matching subtechniques, then inspect associated data components and detection relationships. Ask which service, user, host, time range, and approved business use are relevant.

**Good answer shape:** Present the ATT&CK mapping as a hypothesis. Correlate proxy/DNS/cloud audit and endpoint evidence using approved tools; compare with expected business activity; preserve logs; escalate according to policy. Avoid naming an actor or declaring exfiltration without corroborating evidence.

## Example 6: Summarize a relationship safely

**User asks:** “Does this tool use this technique?”

**AI workflow:** Search the relationship index for the exact tool and technique identifiers. Retrieve the relationship note and both endpoint notes. Confirm edge direction and source snapshot.

**Good answer shape:** “The ATT&CK snapshot records a `uses` relationship from [source object] to [technique] (IDs …). This is a catalog association and does not show that this tool is present or active in your environment.” If no edge is found, say the catalog search found no matching relation; do not claim that the relationship is impossible.

## Example 7: Ask for a mitigation

**User asks:** “How do I reduce risk from a technique relevant to our environment?”

**AI workflow:** Retrieve the technique, `mitigates` edges, and linked mitigation notes. Filter by platform and architecture, then ask for missing context.

**Good answer shape:** Rank practical controls by fit, explain dependencies and operational impact, suggest a safe validation/rollback plan, and link each recommendation to a source. Confirm current vendor guidance and change approval before applying controls.
