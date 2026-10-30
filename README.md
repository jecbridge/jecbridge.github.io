# JecBridge — Official Website

Official website for **JecBridge Desktop**, a Windows desktop application that connects local project folders to AI assistants through the Model Context Protocol (MCP).

🌐 **Website:** https://jecbridge.github.io/

## About JecBridge

JecBridge helps you bring your local development workspaces into your AI workflow. Add the folders you choose, start an MCP connection, and connect the endpoint to an MCP-compatible AI client.

### Highlights

- **Local project access** — choose and manage the project folders you want to connect.
- **MCP connectivity** — expose a project connection for compatible AI clients.
- **Simple desktop workflow** — manage connections from a graphical Windows application.
- **Self-contained installer** — the Windows installer includes the required runtime; users do not need to install Node.js, npm, or Git separately.

## Download

JecBridge Desktop **0.1.0** is available for:

- Windows 10 / Windows 11
- 64-bit (x64)

The installer is named:

`JecBridge Desktop Setup 0.1.0.exe`

> **Release hosting note:** GitHub blocks regular Git commits containing files larger than 100 MB. The current Windows installer is approximately 154 MB, so it should be uploaded as an asset to a GitHub Release (or hosted through Git LFS / another download host), rather than committed directly to this website repository. The website's download link expects the installer at `releases/JecBridge Desktop Setup 0.1.0.exe`; update that link to the published release asset URL when the release is uploaded.

## Website

This is a lightweight static website built with:

- HTML5
- CSS
- Google Fonts — DM Sans and Space Grotesk

No build step or JavaScript framework is required. GitHub Pages serves the site directly from the repository.

### Project structure

```text
.
├── index.html
├── README.md
├── assets/
│   └── icon.png
└── releases/
    └── JecBridge Desktop Setup 0.1.0.exe
```

## Author

Created by **Abbos** — [@abbosby](https://x.com/abbosby).

---

© JecBridge. Built for local-first AI workflows.
