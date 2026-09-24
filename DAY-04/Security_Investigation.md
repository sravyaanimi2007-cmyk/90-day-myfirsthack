# Security Investigation — Day 4

## Security Posture Summary

Assessment included a review of CPU security concepts, unfamiliar Windows processes, file paths, and network connections. Three unfamiliar processes were investigated and appeared legitimate based on their purpose and expected locations. One remote IP, `104.199.241.202:80`, was investigated through WHOIS and identified as part of the Google Cloud network.

## Actions Taken During Investigation

* [ ] Learned CPU and speculative execution
* [ ] Studied Spectre and Meltdown
* [ ] Reviewed RAM vs Storage
* [ ] Investigated three unfamiliar Windows processes
* [ ] Reviewed file paths as security indicators
* [ ] Used `netstat -an` to inspect network connections
* [ ] Identified a remote public IP
* [ ] Performed WHOIS lookup on `104.199.241.202`
* [ ] Identified the IP as part of Google Cloud

## Findings

* **WMI Provider Host** — Appeared legitimate
* **CTF Loader** — Appeared legitimate
* **Elevoc Control Service** — Appeared legitimate
* **Remote IP:** `104.199.241.202:80`
* **Network:** Google Cloud
* **Assessment:** No malicious activity was established from the IP lookup alone.

## Key Security Lesson

> An unfamiliar process, file path, or IP address is a **clue, not proof of compromise**. Further investigation and context are required before making a security conclusion.
