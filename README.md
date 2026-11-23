# Jermaine Baker

Security engineer. I build detection, response and prevention tooling from the kernel up, then attack it to find what breaks.

## Projects

**[EDR-platform](https://github.com/jbaker07/EDR-platform)**: Linux EDR in Rust and eBPF. Eight kernel sensors stream process, file, network, DNS and container socket activity to a Rust agent that runs 22 detection rules and 13 correlation playbooks. A BPF LSM guard blocks container runtime socket abuse, memfd execution and tampering with the agent. Both APIs require a bearer token and the detection policy carries an Ed25519 signature.

**[windows-incident-compiler](https://github.com/jbaker07/windows-incident-compiler)**: Rust pipeline that turns Windows event logs and ETW telemetry into MITRE ATT&CK mapped detections and a forensic incident timeline, with 30 detection playbooks.

**Network troubleshooting tools**: [packet-trace-playbook](https://github.com/jbaker07/packet-trace-playbook) (packet capture to a DHCP, DNS, TCP, TLS and ICMP timeline), [Http-tls-probe](https://github.com/jbaker07/Http-tls-probe), [mtu-blackhole-hunter](https://github.com/jbaker07/mtu-blackhole-hunter), [vpn-diagnostics](https://github.com/jbaker07/vpn-diagnostics) and [Switching-Lab](https://github.com/jbaker07/Switching-Lab), plus [support-log-pack](https://github.com/jbaker07/support-log-pack) for collecting logs for a ticket.

## Focus

Linux and Windows internals, eBPF and BPF LSM, detection engineering, incident response, network protocols.

Rust, C, Python, Bash, PowerShell, SQL.

## Education

Illinois Institute of Technology, Graduate Certificate in Cyber-Physical Systems (December 2026). Operating systems, cloud computing and advanced computer security.

Yale University, B.A. in Economics. Division I football, three-time Ivy League champion.
