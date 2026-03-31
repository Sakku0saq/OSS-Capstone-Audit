OSS Capstone Audit: Mozilla Firefox

This project presents a detailed technical audit of Mozilla Firefox, performed in an open-source environment. The objective is to evaluate system transparency, security posture, and software integrity through a set of automated Linux shell scripts.

📁 Repository Overview
/report
Includes the finalized 16-page audit report in PDF format.
/scripts
A collection of Bash scripts used to perform automated checks and validations:
system_identity.sh – Retrieves and verifies operating system and kernel details
package_inspector.sh – Confirms Firefox installation and package information
disk_auditor.sh – Examines storage usage and file permission settings
log_analyzer.sh – Reviews system logs to assess environment stability
manifesto_gen.sh – Produces a digital audit certificate summarizing findings
🧰 Tech Stack
Operating System: Ubuntu 24.04.4 LTS (running on WSL2)
Scripting Language: Bash
Audit Subject: Mozilla Firefox (licensed under MPL 2.0)
▶️ Execution Guide

To reproduce the audit process, execute the scripts within your Ubuntu terminal environment. For example:

bash scripts/system_identity.sh
