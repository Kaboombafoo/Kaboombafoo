# Hi, I'm Corbin 👋

Cybersecurity M.S. (WGU) with the full CompTIA security stack, building **AI agents and detection content on a blue-team foundation**. I write Python at the scripting level — agents, RAG pipelines, detection rules, test harnesses — and my rule is that every lab session leaves a committed, defensible artifact behind.

**Now:** targeting SOC / IAM analyst roles. **Long-term:** AI red teaming.

---

## Projects

### 🔍 [SOC Triage Agent](https://github.com/Kaboombafoo/SOC-Triage-Agent)
An LLM-based agent, written from scratch with no framework, that triages security indicators (IPs, domains, file hashes): extracts them from raw text, enriches against live threat-intel APIs (VirusTotal, IPinfo), and returns a verdict. Verdict logic is deterministic code, not model output, so every result is auditable — the model reasons, the code decides.

### 📚 [ATT&CK Knowledge RAG](https://github.com/Kaboombafoo/attack-knowledge-rag)
Retrieval-augmented generation over the full MITRE ATT&CK dataset (697 techniques, current to v19). Vector similarity implemented by hand first, then upgraded to Chroma; includes a confidence guardrail that refuses to answer when retrieval is weak instead of fabricating.

### 🛡️ [Medusa Ransomware Detections](https://github.com/Kaboombafoo/medusa-detections)
Six Sigma rules covering Medusa ransomware TTPs (CISA AA25-071A). Three are lab-validated — Atomic Red Team execution on a Sysmon-instrumented VM, detections confirmed in Splunk — and three are AI-assisted coverage rules, labeled as such in the README. The validated/generated distinction is kept explicit on purpose.

### 📡 [Wazuh SIEM Homelab](https://github.com/Kaboombafoo/wazuh-siem-homelab)
Wazuh deployed twice (Oracle Cloud, then AWS via Ansible), physical Windows 11 endpoint enrolled with Sysmon, custom Python → Discord alert integration, automated active response, and a documented false-positive investigation. Includes corrected ATT&CK mappings where the tool's own rule tags were stale or wrong.

---

## Education & Certifications

- **M.S., Cybersecurity & Information Assurance** — Western Governors University, 2026
- **B.S., Cybersecurity & Information Assurance** — Western Governors University, 2023
- **CompTIA:** A+ · Network+ · Security+ · CySA+ · PenTest+ · Project+
- **ITIL 4 Foundation**

## Toolkit

- **Security operations:** Splunk (SPL), Wazuh, Sigma, Sysmon, Atomic Red Team, MITRE ATT&CK
- **AI & automation:** LLM agents & tool use, RAG, embeddings, Chroma, Anthropic API, n8n
- **Scripting:** Python, SQL, Bash, PowerShell
- **Infrastructure:** AWS EC2, Oracle Cloud, Ansible, Linux, Windows, Git

## Currently

- 📈 TryHackMe SOC foundations path
- 🎯 Next up: Hack The Box AI Red Teamer path (garak, PyRIT, promptfoo on the tooling slate)

## Connect

- **LinkedIn:** [linkedin.com/in/corbin-m-griffin](https://linkedin.com/in/corbin-m-griffin)
- **Email:** corbinmgriffin@gmail.com
