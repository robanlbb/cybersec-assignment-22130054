# Cybersecurity Assignment — Malware Analysis & Network Traffic Investigation

**Full Name:** Robert Abou Nader
**Student ID:** 22130054

---

## Malware Sample

| Field | Value |
|-------|-------|
| Sample Name | *(fill in after extraction)* |
| SHA-256 Hash | *(fill in after running certutil/Get-FileHash)* |

---

## Assignment Description

This assignment covers Modules 1–3 of the cybersecurity course and involves a full static and dynamic analysis of a real malware sample. Part A performs static analysis using `strings`, `FLOSS`, and `CFF Explorer` to identify file structure and embedded indicators of compromise (IOCs) without executing the sample. Part B performs dynamic analysis inside an isolated FLARE-VM using `Procmon` and `Wireshark` to observe real-time behavioral and network activity. Part C analyzes the captured network traffic in Wireshark and applies IDS/IPS concepts by writing Snort/Suricata detection rules.

**Tools used:** strings (Sysinternals), FLOSS, CFF Explorer, Procmon, Wireshark, ProcDOT, certutil, FLARE-VM.

---

## Report

[View Full Analysis Report](report/analysis_report.pdf)

---

## Repository Structure

```
cybersec-assignment-22130054/
├── README.md
├── report/
│   └── analysis_report.pdf
├── part-a-static/
│   ├── screenshots/          (SS-01 through SS-09)
│   └── strings_output.txt
├── part-b-dynamic/
│   ├── screenshots/          (SS-10 through SS-20)
│   ├── procmon_log.csv
│   ├── capture.pcap
│   └── procdot_graph.png
└── part-c-traffic/
    └── screenshots/          (SS-21 through SS-26)
```
