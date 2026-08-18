# Home Health Hub

Home Health Hub brings the health devices you already use — a glucose meter, a blood pressure cuff, a pulse oximeter ring, a smart scale — into one place, on a computer in your own home. No cloud account, no company reading your numbers. Your data stays yours.

## What's here

Each device has its own small program that talks to it, keeps its history, and can make you a report to bring to a doctor's visit. Home Health Hub ties them together into one view.

- **[Home Health Hub](https://github.com/home-health-hub/healthhub)** — the shared dashboard and design docs (early days — documentation only so far)
- **Glucose meter** (TrueMetrix) — [trividia-truemetrix-daemon](https://github.com/home-health-hub/trividia-truemetrix-daemon)
- **Pulse oximeter ring** (Viatom O2Ring) — [viatom-o2ring-daemon](https://github.com/home-health-hub/viatom-o2ring-daemon)
- **Smart scale** (Etekcity) — [etekcity-scale-daemon](https://github.com/home-health-hub/etekcity-scale-daemon)
- **Blood pressure monitor** (Etekcity) — [etekcity-bp-daemon](https://github.com/home-health-hub/etekcity-bp-daemon)

Each of those works fine on its own too — you don't need Home Health Hub just to use one device.

The remaining repositories here are the low-level Bluetooth/USB connections the programs above rely on — only really relevant if you're building or troubleshooting one of them yourself.

## License

Everything here is free and open source, under the GNU General Public License v3.0.

---

[![License: GPL-3.0](https://img.shields.io/badge/license-GPL--3.0-blue)](https://github.com/home-health-hub/healthhub/blob/main/LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/home-health-hub/healthhub#contributing)
[![Discussions](https://img.shields.io/badge/discussions-welcome-blue)](https://github.com/home-health-hub/healthhub/discussions)
[![Devices](https://img.shields.io/badge/devices-4-orange)](#whats-here)
[![Repositories](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Forgs%2Fhome-health-hub&label=repositories&query=%24.public_repos&color=blue)](https://github.com/orgs/home-health-hub/repositories)
[![Open Issues](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Fsearch%2Fissues%3Fq%3Dorg%3Ahome-health-hub%2Bis%3Aissue%2Bis%3Aopen&label=open%20issues&query=%24.total_count&color=yellow)](https://github.com/search?q=org%3Ahome-health-hub+is%3Aissue+is%3Aopen&type=issues)
[![Open PRs](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Fsearch%2Fissues%3Fq%3Dorg%3Ahome-health-hub%2Bis%3Apr%2Bis%3Aopen&label=open%20PRs&query=%24.total_count&color=purple)](https://github.com/search?q=org%3Ahome-health-hub+is%3Apr+is%3Aopen&type=pullrequests)
