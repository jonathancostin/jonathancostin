# Jonathan Costin

Software engineer in the Chicago area. I build full-stack web applications in TypeScript, React, Node.js and PostgreSQL, and I run the infrastructure under them.

## Open source

- **[factobot](https://github.com/8thlyr/factobot)** is a benchmark harness that runs an agent in a real, headless Factorio game and scores it on game time to a milestone. A Rust daemon supervises the server, drives it over RCON and serves a versioned JSON socket protocol. The agent works inside a bubblewrap sandbox, and a Lua mod holds it to what a player can do. Rust, Lua and Python.
- **Upstream:** 13 merged pull requests to [gsd-2](https://github.com/gsd-build/gsd-2/pulls?q=is%3Apr+author%3Ajonathancostin+is%3Amerged) (TypeScript), plus merged work in [hyprwhspr](https://github.com/goodroot/hyprwhspr/pulls?q=is%3Apr+author%3Ajonathancostin+is%3Amerged) and [AgentCraft](https://github.com/blendi-remade/agentcraft/pull/2).
- **[tuitree](https://github.com/8thlyr/tuitree)** is a terminal dashboard for git worktrees and GitHub pull requests. It shows which branches are ahead, behind or would conflict, next to each pull request and its review comments. Rust and ratatui, on plain threads with no async runtime.
- **[Fan Curve](https://github.com/8thlyr/fan-curve)** is a macOS menu-bar app that sets fan speed from CPU temperature. A root helper clamps every target to the fan's own limits and hands control back to macOS on sleep, quit or a lost heartbeat. Swift, installed as a Homebrew cask.

## Client work

I'm the only engineer on a production internal operations platform for a hospitality client. It has a React and TypeScript frontend, a Node.js and Express API, PostgreSQL with Drizzle, Microsoft Entra ID sign-in, and Terraform on Google Cloud. The code is private.

## Microsoft 365 automation

PowerShell I wrote as a systems specialist at a managed IT provider. These repos are archived.

- **[o365Reporter](https://github.com/jonathancostin/o365Reporter)** reports active and inactive users, licenses, MFA methods and devices to CSV, through Microsoft Graph and Exchange Online.
- **[pslib](https://github.com/jonathancostin/pslib)** is a PowerShell 7 module of 35 Microsoft 365 admin functions, with a terminal UI.
- **[Intune](https://github.com/jonathancostin/Intune)** gets domain-joined Windows devices enrolled in Intune automatically.
- **[intuneaudit](https://github.com/jonathancostin/intuneaudit)** audits Intune device compliance against a conditional-access group and writes the result to CSV.

## Smaller tools

- **[LenovoWarrantyAPI](https://github.com/jonathancostin/LenovoWarrantyAPI)** looks up Lenovo warranty and hardware specs by serial number. Node.js, with a CLI, a CSV batch mode and a REST API.
- **[invoicefinder](https://github.com/jonathancostin/invoicefinder)** downloads Microsoft 365 invoices as PDFs. Python and Playwright.

## What I work with

- Languages: TypeScript, JavaScript, Python, Go, Rust, Swift, C, SQL, PowerShell
- Web: React, Node.js, Express, REST APIs, PostgreSQL, SQLite
- Infrastructure: AWS, Azure, Google Cloud, Terraform, Docker, Linux, GitHub Actions
- Identity: Microsoft 365, Entra ID, Active Directory, OAuth 2.0

I use AI coding tools every day and review every change I ship.

[LinkedIn](https://www.linkedin.com/in/jonathan-costin)
