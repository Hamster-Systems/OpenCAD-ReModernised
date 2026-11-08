> [!CAUTION]
> **PROJECT ABANDONED — NOT RECOMMENDED FOR DEPLOYMENT**
>
> **OpenCAD ReModernised was started by Hamster Systems to revive, maintain and modernise the original OpenCAD project while preserving its history and open-source foundations.**
>
> After evaluating the inherited codebase, we concluded that the work required goes well beyond a normal modernisation effort. The amount of unfinished or problematic functionality, underlying architectural limitations and security concerns would require **a complete rebuild of core systems**, rather than a series of incremental fixes. Continuing this fork was therefore not a practical or responsible route to a maintainable CAD platform.
>
> **Security concerns are not limited to password exposure.** The review raised broader concerns about the design and handling of core functionality, including authentication, registration, credentials and the overall security foundations of the application. Possible disclosure of passwords through authentication-related responses was among the reported concerns, **not the sole reason for discontinuation**. These findings have not been published here as a fully reproduced, comprehensive security audit; individual suspected vulnerabilities should not be treated as independently confirmed.
>
> **Do not deploy this fork publicly, use real passwords or personal information, or depend on it for operational data.** It is not security-maintained or production-ready. No fixes, releases or support are planned. The repository is preserved for historical reference, attribution and transparency. This decision concerns the feasibility of this **revival effort**, not an assertion that every component of the original project has been independently proven insecure.
---

<div align="center">

<img src="assets/branding/opencad-remodernised-logo.png" alt="OpenCAD ReModernised logo" width="420" />

# OpenCAD ReModernised

**An attempted revival of the original OpenCAD project — now discontinued.**

An independent, now-discontinued effort to modernise the open-source Computer-Aided Dispatch (CAD) system for roleplay communities.

[![License: GPL-3.0](https://img.shields.io/badge/license-GPL--3.0-blue)](LICENSE)
[![Development status](https://img.shields.io/badge/status-abandoned-red)](https://github.com/Hamster-Systems/OpenCAD-ReModernised)
[![Maintained by Hamster Systems](https://img.shields.io/badge/maintained%20by-Hamster%20Systems-555)](https://github.com/Hamster-Systems)

</div>

## About the project

**OpenCAD ReModernised** was a revival and modernisation effort based on [OpenCAD](https://github.com/opencad-community/OpenCAD), an open-source dispatch platform for roleplay communities. The original goal was to preserve the existing project's foundations while working towards a more maintainable and accessible future.

This repository is an **independent, discontinued fork** published under [Hamster Systems](https://github.com/Hamster-Systems). It is not the official continuation of the original OpenCAD organisation and is not affiliated with its maintainers.

## Project branding

<div align="center">
  <img src="assets/branding/opencad-remodernised-icon.png" alt="OpenCAD ReModernised simplified shield icon" width="125" />
</div>

The official assets for this independent revival are maintained in [`assets/branding/`](assets/branding/):

- **[Full logo](assets/branding/opencad-remodernised-logo.png)** — for project documentation, repository presentation and wider branding.
- **[Simplified shield icon](assets/branding/opencad-remodernised-icon.png)** — for compact placements such as app icons, avatars and future favicons.

These assets identify the **OpenCAD ReModernised fork**, not the original OpenCAD project. Existing upstream artwork and original copyright notices remain part of the project's history.

## Project status

**Abandoned / discontinued.** This project began with the intention of updating the legacy application, improving compatibility and accessibility, and restoring it as a maintainable CAD system.

The assessment showed that a viable, secure modern version would require substantial replacement of the application’s underlying architecture and core systems—including authentication and registration—rather than ordinary maintenance. The scope became effectively a **full rebuild**, so work on this fork was stopped.

The reported password-exposure concern is only one part of the broader security concerns. The README is a project-status warning, **not a complete vulnerability disclosure or a claim that every reported risk has been independently reproduced**.

There is no active roadmap, supported release, or planned security maintenance.

## Getting started

The original OpenCAD README listed the following requirements. **These are inherited historical requirements, not yet independently validated for OpenCAD ReModernised:**

| Component | Requirements listed upstream |
| --- | --- |
| Operating system | Linux or Windows |
| Web server | Apache or Nginx |
| PHP | 8.0 or later |
| Database | MySQL 8.0+ or MariaDB 10.2+ |

These requirements are retained for historical context only. **Do not use them as deployment instructions.** No further installation or migration guidance is planned.

## Contributing and feedback

The project is no longer accepting development work as an active modernisation effort. [CONTRIBUTING.md](CONTRIBUTING.md) is retained for historical reference. Existing issues and pull requests document work identified before discontinuation.

## Credits and origins

This project would not exist without the work of the original **OpenCAD project and its contributors**.

- **Original project:** [opencad-community/OpenCAD](https://github.com/opencad-community/OpenCAD)
- **Original contributors and history:** [upstream contributor history](https://github.com/opencad-community/OpenCAD/graphs/contributors)
- **Revival and ongoing stewardship:** [Hamster Systems](https://github.com/Hamster-Systems)

See [CREDITS.md](CREDITS.md) for further attribution. Original copyright and licence notices must be preserved.

## Licence

Distributed under the **GNU General Public License v3.0**. See [LICENSE](LICENSE) for the licence text. Forking, redistribution and modifications are subject to its terms. The GPL licence does not imply affiliation with the upstream maintainers.

---

<div align="center"><sub>OpenCAD ReModernised is independently maintained by Hamster Systems and is not endorsed by or affiliated with the original OpenCAD team.</sub></div>
