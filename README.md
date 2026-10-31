# TrueClose

**Closed should mean closed.**

Some apps do not really close. You press X, the window disappears, and the app carries on
running in the background, holding memory until you restart the PC.

TrueClose fixes that. You pick which apps it should watch. When you close an app's last
window, TrueClose waits for the delay you chose, and if you have not reopened it by then,
the app is fully closed.

Everything else is left alone. TrueClose only ever touches the apps on your list.

## How it works

1. Add apps to your watchlist from a picker that lists the apps on your PC.
2. Choose a default delay for all your apps, from 10 seconds to 5 minutes, and give any
   single app its own if it needs longer.
3. Close the window and forget about it. Reopen it in time and nothing happens.
4. An optional notification tells you when an app has been fully closed.

TrueClose sits quietly in the notification area. It does not need administrator rights,
it does not install a service, and it has no account, no telemetry and no network use of
any kind. See [PRIVACY.md](PRIVACY.md).

## Getting TrueClose

TrueClose is free. It is on its way to the **Microsoft Store**, which is where it will be
available to download.

Windows now blocks unsigned apps on many PCs, so the Store version, which Microsoft signs
during publishing, is the one that will install and run cleanly. This page will be
updated with the Store link once it is live.

## Requirements

- Windows 10 version 2004 (build 19041) or newer, 64-bit

## Reporting a problem

Open an issue on this repository. Please say what you did, what you expected, and what
happened instead.

## About

TrueClose is free, closed source software by Natlab3d. The source code is not public.

© 2026 Michelangelo Natoli. All rights reserved.
