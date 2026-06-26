# Hi, I'm Corbin 👋

I'm a Cybersecurity M.S. graduate building toward a career in AI-driven
security automation. My background leans blue-team / detection, and right
now I'm spending most of my time learning to build with LLMs and agents —
and applying that to security operations.

I learn by building labs, breaking them on purpose, and writing up what
actually went wrong.

## 🎯 What I'm working on now
- **[SOC Triage Agent](https://github.com/Kaboombafoo/soc-triage-agent)** — an AI agent (hand-built, no framework) that triages security indicators using tools and live threat-intel APIs. My first real applied-AI security project.
- Learning AI agent architecture from the ground up: tool use, the agent loop, and the line between verified tool data and model knowledge.
- Extending the agent with real reputation/verdict checks (VirusTotal) next.

## 🎓 Education & Certifications
- **M.S.**, Cybersecurity & Information Assurance — Western Governors University
- **B.S.**, Cybersecurity & Information Assurance — Western Governors University
- **CompTIA:** A+ · Network+ · Security+ · CySA+ · PenTest+ · Project+
- **ITIL 4 Foundation**

## 🧰 Tools I work with
- **Security Ops:** Wazuh, Microsoft Sysmon, Windows Event Logs, MITRE ATT&CK
- **Cloud / Infra:** AWS EC2, Oracle Cloud (OCI), Ubuntu, Ansible
- **Dev / Automation:** Python, Bash, PowerShell, Git, n8n
- **Currently learning:** LLM/agent orchestration, detection engineering, cloud security

## 📂 Projects
### Cloud SIEM + Automated Active Response — Wazuh · AWS · Ansible
Deployed Wazuh on AWS EC2, enrolled a Windows 11 endpoint with Sysmon for
deeper telemetry, and used Ansible to automate the manager setup. Added
active-response rules that auto-block hosts on high-severity alerts. This was
a rebuild of an earlier Oracle Cloud version — the second pass added
infrastructure-as-code and automated containment.

### Cloud SIEM + Custom Discord Alerting — Wazuh · Oracle Cloud · Python
The first version. Wrote a Python integration to push Wazuh alerts to Discord
as severity-color-coded embeds, and documented the real bugs I hit along the
way (null-field payload rejections; a BOM/CRLF issue that made Linux misread
the Python script as Bash).

## 📫 Contact
- 📧 corbinmgriffin@gmail.com
- 💼 LinkedIn: https://linkedin.com/in/corbin-m-griffin
