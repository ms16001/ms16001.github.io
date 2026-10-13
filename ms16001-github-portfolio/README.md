# Musa Scott | Cybersecurity Portfolio

U.S. Army veteran, CompTIA Security+ certified IT and cybersecurity professional, and NYU Tandon graduate. My experience spans healthcare IT operations, infrastructure administration, security investigations, and military logistics.

This portfolio documents controlled coursework and lab analysis for employers interested in security operations, network defense, and vulnerability management.

## Featured project: TCP Protocol Security

[Read the TCP case study](project-tcp.html) · [Browse the portfolio homepage](index.html)

The SEED Labs case study covers four experiments. The existing write-up includes screenshots extracted from the original graded submission.

| Experiment | Analysis documented | Evidence |
| --- | --- | --- |
| SYN flooding and SYN cookies | Comparison of connection behavior with protection enabled and disabled | [Comparison screenshots](assets/syn-cookie-comparison.jpg) |
| TCP reset spoofing | How a crafted reset can terminate an established Telnet connection when accepted | [Reset experiment](assets/tcp-reset-evidence.jpg) |
| TCP session hijacking | Packet injection using TCP sequence and acknowledgment information | [Session-hijacking screenshot](assets/session-hijacking-evidence.jpg) |
| Reverse shell via session hijacking | Impact of a compromised session in an isolated lab | [Reverse-shell screenshot](assets/reverse-shell-evidence.jpg) |

**Tools used:** Python, Scapy, C, Wireshark, Linux, and Docker.

**Defensive lessons:** Monitor anomalous connection patterns, use layered denial-of-service controls, replace Telnet with SSH, segment management traffic, and correlate outbound connections with endpoint telemetry.

### Evidence and limitations

- The case study documents coursework; it does not represent testing against production systems.
- The screenshots are from the original submission, not a new reproduction.
- Raw packet captures are not currently included.
- The session-hijacking submission omitted a required Wireshark frame showing injected code with SEQ/ACK values. The existing screenshot should not be treated as a substitute for that missing frame.
- Some C starter code originated with SEED Labs. Preserve upstream attribution and review its license before publishing source.

[SEED Labs TCP Attacks guide](https://seedsecuritylabs.org/Labs_20.04/Files/TCP_Attacks/TCP_Attacks.pdf)

## Professional background

At Mosaic Mental Health, I supported IT infrastructure and users, investigated recurring privileged-account lockouts using Windows Security logs and Sysinternals Process Monitor, and blocked suspicious external activity through a Cisco ASA firewall. My work also included endpoint hardening, access controls, VPN connectivity, and security awareness training.

In the U.S. Army, I coordinated repair parts and maintenance reporting across six battalion companies, supporting maintenance leadership and operational readiness.

## Education and certifications

- M.S., Computer Science and Engineering, Cybersecurity concentration — NYU Tandon, May 2026
- B.S., Information Technology Management — Berkeley College, August 2019
- CompTIA Security+ — July 2026
- Microsoft SC-200 — study in progress
- Cybersecurity Analytics Certificate — Fullstack Academy, April 2023

## Additional work to document

Splunk Enterprise exercises in Immersive Labs, ARP security, digital forensics, and Bluetooth/mobile security are areas for future case studies. They are not presented here as published projects until their supporting material is added.

Each new case study should include the objective, environment, actions taken, observed result, evidence, defensive implications, and limitations.

## Contact

[LinkedIn](https://www.linkedin.com/in/musa-scott/) · [GitHub](https://github.com/ms16001/)
