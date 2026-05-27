<div align="center">

<!-- Header with left text and right logo -->
<div style="display: flex; align-items: center; justify-content: space-between; width: 100%;">
  <div style="text-align: left;">
    <strong style="font-size: 1.2em;">Licensing, Simplified.</strong><br>
    <strong style="font-size: 1em;">Mantra:</strong> See licenses, grant access – no more, no less.<br>
    <strong style="font-size: 1em;">Tagline:</strong> Licensing, composed right.
  </div>
  <div>
    <img src="https://www.protee.org/images/wok_Krolific/wok_Krolific.png" alt="wok_Krolific Logo" width="60" style="border-radius: 12px;">
  </div>
</div>

<!-- Title and badges -->
# wok_Krolific

[![4D Component](https://img.shields.io/badge/4D-Component-blue)](#)
[![License: Commercial](https://img.shields.io/badge/License-Commercial-red.svg)](#license)
[![Platform: macOS & Windows](https://img.shields.io/badge/Platform-macOS%20%7C%20Windows-lightgrey)](#)
[![4D v21+](https://img.shields.io/badge/4D-v21%2B-brightgreen)](#)

</div>

## Overview

wok_Krolific is the centralized licensing system for the entire **ogTools suite**. It provides the essential infrastructure to manage, validate, and streamline licenses for all commercial components within the ecosystem. Think of it as the "gatekeeper" that ensures seamless, unified licensing across your 4D development projects.

It is a **mandatory dependency** for all paid ogTools components and must be installed alongside them.

---

## Key Features

- **Unified Registration**: Handles the registration process for every paid ogTools product, offering a single point of management.
- **Flexible Key Delivery**: Licenses can be provided programmatically within any registration method call OR via traditional license files, giving you deployment flexibility.
- **Multi-Language Support**: The system is fully localized in **English (EN)**, **French (FR)**, **Spanish (ES)**, and **German (DE)** to serve a global user base.
- **Integrated Suite Communication**: Every ogTools component automatically registers with wok_Krolific, creating a unified communication layer for seamless discovery and interaction.
- **Shared Resources**: Facilitates the automatic sharing of critical information (e.g., the location of a common resources folder) to ensure consistent configuration across the suite.

---

## Installation & Dependencies

### Prerequisites
- **4D v21** or higher (Project mode recommended).
- The [**4D SVG component**](https://github.com/4d/4D-SVG) must be available in your project.

### Installation via Dependencies Manager (GitHub)

Starting with 4D v21, the recommended way to install wok_Krolific (and any ogTools component) is through the **Dependencies Manager** using the **GitHub repository**:

1. In your 4D project, open the **Dependencies Manager** (`Project > Dependencies`).
2. Click the `+` button and select **Add a dependency from a Git URL**.
3. Enter the following Git URL:  
   `protee/wok_Krolific`
4. Choose the desired version (e.g., `main`, `latest`, or a specific release tag).
5. Confirm the installation – the component will be automatically fetched from GitHub, placed in the `Components` folder, and linked to your project.

> **Note**: For team development, commit the dependency configuration file (`dependencies.json`) to your source control so all team members automatically fetch the same version from GitHub.

### Required Companion Components

The following components are not mandatory for wok_Krolific to function alone, but they are required if you use other paid ogTools modules. They will automatically integrate with wok_Krolific when installed. Add them via the Dependencies Manager using their respective GitHub URLs (e.g., `protee/wox_Xlibrary`):

- `wox_Xlibrary` (Core utilities)
- `woc_Colours` (Advanced color engine)
- `waz_Wazar` (Intelligent UI widgets)
- `wob_Boxes` (File repository management)

---

## How It Works

1.  **Component Registration**: When you install any paid ogTools component, it automatically registers itself with the wok_Krolific system.
2.  **License Validation**: On application startup, wok_Krolific validates all licenses, ensuring compliance and access.
3.  **Key Management**: Licenses can be delivered via:
    - **Programmatic calls** within your registration logic.
    - **Traditional license files** stored in a secure location.
4.  **Resource Sharing**: Once validated, the system shares critical configuration paths (like resource folders) across all integrated components.

---

## Part of the ogTools Suite

wok_Krolific is the foundational licensing pillar of the comprehensive **ogTools suite**—an integrated development ecosystem for 4D. Other key components include:

| Component | Description |
|-----------|-------------|
| **zen_Nucleus** | The complete ORDA framework binding your database to a sophisticated UI. |
| **wox_Xlibrary** | Core utilities for everyday development tasks. |
| **woc_Colours** | Advanced, indexed color management engine. |
| **waz_Wazar** | Intelligent UI widgets for modern interfaces. |
| **wor_Recursive** | Manage hierarchical data with ease. |
| **wob_Boxes** | Secure, Dropbox-like file repository. |
| **wod_DevTools** | Instant documentation generation. |

> Together, these components form a powerful framework that allows developers to focus on unique business logic rather than reinventing the wheel.

---

## License

wok_Krolific is a **commercial component** and is part of the paid ogTools suite. A valid license is required for use. For licensing options and trial requests, please contact the sales team directly.

---

## Localization

wok_Krolific supports the following languages out-of-the-box:

- 🇺🇸 English (EN)
- 🇫🇷 French (FR)
- 🇪🇸 Spanish (ES)
- 🇩🇪 German (DE)

Localization affects error messages, UI prompts, and registration flows.

---

## Support & Resources

- **Official Website**: [https://www.protee.org](https://www.protee.org)
- **Documentation**: Full documentation and HDI (Host Database Interface) demos are included with your purchase.

For direct inquiries:
- **Email**: [og@protee.org](mailto:og@protee.org)
- **Phone**: +33 6 3718 5941

---

## About the Creator

wok_Krolific and the ogTools suite are developed by **Protée sarl**, a company with over 30 years of expertise in 4D development. Led by Olivier Grimbert, the team focuses on delivering high-quality, production-grade tools that enhance developer productivity and application reliability.

---

<div align="center">
  <sub>Built with ❤️ for the 4D community by Protée sarl. © 2016 - Present</sub>
</div>