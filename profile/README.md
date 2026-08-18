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
