# vpngate-pool

Live list of public [VPN Gate](https://www.vpngate.net/) relays for the «VPN одной кнопкой» Windows app.

- `servers.csv` — relays that answer right now, newest first, in the VPN Gate "iphone" CSV format
  (+ `FirstSeen` / `LastAlive` unix columns). Updated automatically every 10 minutes.
- `app/version.json` — the newest app release (build, SHA-256, download link, ed25519 signature). The app checks it
  at start and every 6 hours and updates itself; it installs only releases signed with the key built into it.
- Only public relay addresses from vpngate.net; no accounts, keys or personal data.

Download the app: [Releases](../../releases/latest).
