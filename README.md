# DIA Agent updates

## Rhino Agent dev.145

- New versions are announced without signing into GitHub.
- The normal **Install update** button opens browser sign-in only if the private download requires it, then continues automatically.
- Existing sign-ins are reused. Cancelled login, missing repository permission and connection errors have clear, retryable messages.
- Current Git for Windows credential-manager locations are supported, including ucrt64 runtimes.
- Installer checksums and package versions are verified before installation. Restart Rhino after installing to load the update.

Source code and installers remain private. Signing in does not grant access automatically; your account must have repository permission.

Anyone can read the current Rhino Agent version in [rhino.json](rhino.json), without a GitHub account.

In supported versions of DIA Agent, use **Install update**. If the installer requires GitHub access, the agent opens browser sign-in after Install is clicked and continues automatically when sign-in succeeds. Access to a private installer still requires permission from its repository administrator.

This repository contains public release metadata only. Source code, installers, customer projects and credentials are not published here.

Versions before 0.1.1-dev.145 need a one-time installation of dev.145 or later to gain signed-out update discovery. Obtain the published installer from the [Rhino Agent release page](https://github.com/Daniel-Inocente-Architecture/DIA-rhino-agent/releases).
