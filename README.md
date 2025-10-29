# Disable_DevTools

> **Important:** These scripts are intended for **legitimate** developer, accessibility, or personal-use purposes only (e.g., debugging your own web apps, accessibility tweaks for your own environment, or educational experiments on pages you control). **Do not use these scripts to circumvent website protections, violate terms of service, or access content or functionality you do not have permission to use.**

---

## Table of Contents
- [About](#about)
- [Scope & Intended Use](#scope--intended-use)
- [Installation (Tampermonkey)](#installation-tampermonkey)
- [Usage](#usage)
- [Troubleshooting](#troubleshooting)
- [Contributing](#contributing)
- [License](#license)
- [Disclaimer & Legal / Ethical Notice](#disclaimer--legal--ethical-notice)
- [Contact](#contact)

---

## About
This repository collects user scripts (Tampermonkey/Greasemonkey-compatible) that automate or modify browser behavior for **legitimate** development and personalization tasks. Examples of acceptable purposes include:
- Streamlining development workflows on sites you own.
- Accessibility improvements for your personal browsing environment (where permitted).
- Educational demonstrations and experiments on test pages you control.

---

## Scope & Intended Use
**Do use these scripts if:**
- You are the site owner or have explicit permission to test or modify the site.
- You are using scripts for local development, debugging, or accessibility enhancements in your own environment.
- You are conducting research in a legal and ethical manner with consent.

**Do NOT use these scripts to:**
- Bypass website security features, restrictions, or anti-debugging safeguards on third-party sites.
- Circumvent paywalls or other access controls.
- Violate any site's terms of service or applicable laws.

By using anything in this repository you confirm you will follow the rules above.

---

## Installation (Tampermonkey)
> These are generic, safe steps for installing user scripts in a browser via Tampermonkey. Follow only for scripts you are permitted to run.

1. Install Tampermonkey (browser extension) from the official store for your browser:
   - Chrome / Edge / Brave: search the browser's extension store for "Tampermonkey".
   - Firefox: install the Tampermonkey add-on from Mozilla Add-ons.
   - (Follow your browser's normal extension installation flow.)

2. After Tampermonkey is installed:
   - Click the Tampermonkey icon in your browser toolbar.
   - Choose **Dashboard** or **Create a new script**.

3. To add a script from this repository:
   - Open the script file (*.user.js) in this repo.
   - Copy the script contents.
   - In Tampermonkey, click **Create a new script**, paste the contents, then **File → Save** (or the Save icon).
   - Make sure the script is enabled in the Tampermonkey dashboard.

4. Verify:
   - Visit the target page (only pages you control or are authorized to test).
   - Confirm the extension is active and the script is enabled.

---

## Usage
- Each script in this repository includes a short header comment describing what it does, what pages it targets, and any configuration options.
- Use the Tampermonkey dashboard to enable/disable scripts, edit them, or configure per-site execution.
- Keep scripts up to date and review their code before installing.

---

## Troubleshooting
- Script not running? Check Tampermonkey's dashboard to ensure the script is enabled and the `@match` / `@include` metadata matches the page URL.
- Script causes page problems? Disable the script and reload the page. Only re-enable after making changes in a test environment.
- Browser console errors? Use the browser DevTools console to inspect runtime errors — alway
