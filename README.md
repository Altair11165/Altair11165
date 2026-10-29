<p align="center">
  <img src="assets/header.svg" alt="Rishabh Vyas" width="100%">
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1200&color=39D353&center=true&vCenter=true&width=600&height=45&lines=$+whoami;System+%26+Network+Engineer;Building+AI+agent+workflows;MSc+Cybersecurity+%C2%B7+CEH;Shipping+Frappe+%26+Django+apps;Securing+a+GitHub+org+with+custom+CI;Next+stop%3A+offensive+security" alt="whoami: System and Network Engineer, building AI agent workflows, MSc Cybersecurity and CEH, shipping Frappe and Django apps, moving into offensive security">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/CEH-EC--Council-B71C1C?style=for-the-badge&labelColor=0d1117" alt="CEH">
  <img src="https://img.shields.io/badge/MSc-Cyber%20Security-39d353?style=for-the-badge&labelColor=0d1117" alt="MSc Cyber Security">
  <img src="https://img.shields.io/badge/AI%20agents-Claude%20Code%20%C2%B7%20Codex-D97757?style=for-the-badge&logo=claude&logoColor=white&labelColor=0d1117" alt="AI agents: Claude Code and Codex">
  <img src="https://img.shields.io/badge/Django-production-44B78B?style=for-the-badge&logo=django&logoColor=white&labelColor=0d1117" alt="Django">
  <img src="https://img.shields.io/badge/Frappe-production-0089FF?style=for-the-badge&logo=frappe&logoColor=white&labelColor=0d1117" alt="Frappe">
  <img src="https://img.shields.io/badge/MikroTik-VPN-D29922?style=for-the-badge&logo=mikrotik&logoColor=white&labelColor=0d1117" alt="MikroTik">
  <img src="https://img.shields.io/badge/Tailscale-failover-BC8CFF?style=for-the-badge&logo=tailscale&logoColor=white&labelColor=0d1117" alt="Tailscale">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/merged%20PRs-127-39d353?style=flat-square&logo=github&labelColor=0d1117" alt="127 merged pull requests">
  <img src="https://img.shields.io/badge/production%20apps-3-0089FF?style=flat-square&labelColor=0d1117" alt="3 production apps">
  <img src="https://img.shields.io/badge/CI%20workflows-18-D29922?style=flat-square&logo=githubactions&logoColor=white&labelColor=0d1117" alt="18 CI workflows">
  <img src="https://img.shields.io/badge/agent%20plugins-9-D97757?style=flat-square&logo=claude&logoColor=white&labelColor=0d1117" alt="9 agent plugins">
</p>

```bash
rishabh@altair:~$ whoami
name       = "Rishabh Vyas"
role       = "System & Network Engineer @ Krystalline Salt Ltd."
builds     = ["AI agent workflows (Claude Code, Codex)", "Frappe & Django apps", "CI merge gates"]
education  = "MSc Cyber Security (First Class Honours), National College of Ireland"
certs      = ["CEH", "IBM Cybersecurity Analyst", "TryHackMe Pre Security"]
runs       = ["Django", "Frappe", "GitHub org CI", "MikroTik networks"]
leads      = "a team of developers"
homelab    = ["TrueNAS", "Jellyfin", "Carbonio"]
learning   = "offensive security"   # TryHackMe, Jr Penetration Tester next
motto      = "you can't break what you never built"
```

## Arsenal `$ ls ~/tools`

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,django,linux,bash,git,githubactions&theme=dark" alt="Python, Django, Linux, Bash, Git, GitHub Actions">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Claude%20Code-D97757?style=flat-square&logo=claude&logoColor=white" alt="Claude Code">
  <img src="https://img.shields.io/badge/OpenAI%20Codex-412991?style=flat-square" alt="OpenAI Codex">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/React%20Native-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React Native">
  <img src="https://img.shields.io/badge/Frappe-0089FF?style=flat-square&logo=frappe&logoColor=white" alt="Frappe">
  <img src="https://img.shields.io/badge/MikroTik-293239?style=flat-square&logo=mikrotik&logoColor=white" alt="MikroTik">
  <img src="https://img.shields.io/badge/Tailscale-242424?style=flat-square&logo=tailscale&logoColor=white" alt="Tailscale">
  <img src="https://img.shields.io/badge/TrueNAS-0095D5?style=flat-square&logo=truenas&logoColor=white" alt="TrueNAS">
  <img src="https://img.shields.io/badge/Synology-B5B5B6?style=flat-square&logo=synology&logoColor=black" alt="Synology">
  <img src="https://img.shields.io/badge/Jellyfin-00A4DC?style=flat-square&logo=jellyfin&logoColor=white" alt="Jellyfin">
  <img src="https://img.shields.io/badge/Kali%20Linux-557C94?style=flat-square&logo=kalilinux&logoColor=white" alt="Kali Linux">
  <img src="https://img.shields.io/badge/Burp%20Suite-FF6633?style=flat-square&logo=burpsuite&logoColor=white" alt="Burp Suite">
  <img src="https://img.shields.io/badge/Nmap-0E4429?style=flat-square" alt="Nmap">
</p>

## What I run `$ systemctl list-units`

<p align="center">
  <img src="assets/network.svg" width="100%" alt="Network: an Africa workstation reaches the India home lab (TrueNAS, Jellyfin, Carbonio) over a MikroTik site-to-site VPN, with Tailscale as the failover path">
</p>

<details open>
<summary><b>AI agent engineering</b> · agents that build, guarded by policy</summary>
<br>

- Built the company's agent kit for **Claude Code** and **OpenAI Codex**: one install sets up a developer machine with shared rules, a guard, model policy and plugins, and keeps itself updated daily.
- Spec-driven workflow: every change goes requirements → design → tasks → build → PR, with approval lines and a spec checker. Humans keep merge rights.
- Guard hooks stop agents from running destructive git commands, pushing to protected branches or editing their own settings and CI.
- Multi-agent orchestration: orchestrator, worker, verifier and scout sub-agents, each on a model and effort picked by policy.
- Pre-PR pipeline where agents rebuild a test site, run the server and UI suites, and record captioned walkthroughs for every role.
- Wrote 7 Claude Code mods (live agent pane, workflow board, session gauge, model picker and more), bundled in the kit's 9-plugin marketplace.

</details>

<details>
<summary><b>DevSecOps</b> · GitHub org, merge gates, security</summary>
<br>

- Own the company **GitHub organization**: rulesets, required checks, custom CI gates, least-privilege teams. Automated CD is in progress.
- Built merge gates for private repos without branch protection: exact-commit CI checks, reviewer sign-off, codeowner merge audit and alerts on main. 18 workflows across two app repos, with automatic version bumps on merge.
- Moving CI to self-hosted runners, keeping fork pull requests on isolated runners.
- Security monitoring: SIEM, intrusion detection and SOC operations.
- Found and fixed an information-disclosure exposure on a public website.

</details>

<details>
<summary><b>Business apps</b> · Frappe and Django in production</summary>
<br>

- **Fleet management** (Frappe): fuel orders with approval workflow, printable fuel slips, fuelling records with gauge photos and reports. 28 specs, 13 DocTypes, 39 merged PRs.
- **Petty cash** (Frappe): ported a legacy Django app to Frappe workflows with disbursements and an audit trail. 16 DocTypes, 78 merged PRs, release v0.6.0.
- **Litigation matter tracker** (Django): hearings, tasks, deadline alerts, email digests and calendar sync for the legal team.
- Run and harden the production **Django** and **Frappe** environments, and lead a team of developers on reviews and release flow.

</details>

<details>
<summary><b>Network</b> · routing, VPN, failover</summary>
<br>

- Configured MikroTik routers for a cross-continent VPN from Africa to my lab in India.
- Added Tailscale as an independent fallback, so the lab stays reachable if the tunnel drops.

</details>

<details>
<summary><b>Home lab</b> · storage and self-hosted services</summary>
<br>

- TrueNAS for storage, with Synology experience alongside it.
- Self-hosted Jellyfin (media) and Carbonio (mail and collaboration).

</details>

## Credentials `$ cat ~/.certs`

| Credential | Issuer | Year |
|---|---|---|
| CEH, Certified Ethical Hacker | EC-Council | Active |
| IBM Cybersecurity Analyst | IBM · Coursera | 2021 |
| Pre Security | TryHackMe | 2026 |
| MSc Cyber Security, First Class Honours | National College of Ireland | 2022 |
| BE Computer Science | Manipal University Jaipur | 2020 |

More certifications on [LinkedIn](https://www.linkedin.com/in/rishabh-vyas-6209791a0).

<details>
<summary><b>Projects</b></summary>
<br>

- **Blockchain in IoT to mitigate DDoS attacks** (MSc, 2022). Studied how to stop DDoS floods from many sources in IoT networks using blockchain.
- **Accident prevention with machine learning** (2020). Predicted road accidents in Rajasthan from public data.
- **[ShowTracker](https://github.com/Altair11165/TV_Tracker)** (2026). TV and movie tracker for a household: React Native (Expo) app with a Node and SQLite server on TMDB data.

</details>

## Offensive security log `$ cat progress.log`

<p>
  <a href="https://tryhackme.com/p/Altair11165"><img src="https://tryhackme-badges.s3.amazonaws.com/Altair11165.png" alt="TryHackMe live badge: rank, badges and level"></a>
</p>

- [x] Pre Security path
- [ ] Jr Penetration Tester path
- [ ] Web application testing
- [ ] Next certification

## Activity `$ git log --graph`

<p align="center">
  <img src="https://raw.githubusercontent.com/Altair11165/Altair11165/output/0-profile-details.svg" alt="Profile details and contributions" width="100%">
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/Altair11165/Altair11165/output/stats.svg" alt="GitHub stats" width="49%">
  <img src="https://raw.githubusercontent.com/Altair11165/Altair11165/output/streak.svg" alt="Contribution streak" width="49%">
</p>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Altair11165/Altair11165/output/github-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Altair11165/Altair11165/output/github-snake.svg">
  <img src="https://raw.githubusercontent.com/Altair11165/Altair11165/output/github-snake.svg" alt="Contribution snake" width="100%">
</picture>

## Reach me `$ ping rishabh`

<p align="center">
  <a href="https://www.linkedin.com/in/rishabh-vyas-6209791a0"><img src="https://img.shields.io/badge/LinkedIn-Rishabh%20Vyas-0A66C2?style=for-the-badge&labelColor=0d1117" alt="LinkedIn"></a>
  <a href="mailto:iamrishabhvyas@gmail.com"><img src="https://img.shields.io/badge/Email-iamrishabhvyas%40gmail.com-39d353?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0d1117" alt="Email"></a>
  <a href="https://tryhackme.com/p/Altair11165"><img src="https://img.shields.io/badge/TryHackMe-Altair11165-C11111?style=for-the-badge&logo=tryhackme&logoColor=white&labelColor=0d1117" alt="TryHackMe"></a>
</p>

<p align="center">
  <img src="assets/footer.svg" alt="" width="100%">
</p>
