<p align="center">
  <img src="assets/icon.png" alt="WSpoof Icon" width="128">
</p><h1 align="center">WSpoof</h1><p align="center">
  A Windows utility for system configuration, identification testing, and profile management.
</p><p align="center">
  <a href="https://github.com/duckycashy/wspoof">
    <img src="https://img.shields.io/badge/Platform-Windows-0078D4?style=for-the-badge&logo=windows&logoColor=white" alt="Platform: Windows">
  </a>
  <a href="https://github.com/duckycashy/wspoof">
    <img src="https://img.shields.io/badge/Language-C%23-512BD4?style=for-the-badge&logo=csharp&logoColor=white" alt="Language: C#">
  </a>
  <a href="https://github.com/lepoco/wpfui">
    <img src="https://img.shields.io/badge/UI-WPF%20UI-647CFF?style=for-the-badge" alt="UI: WPF UI">
  </a>
  <a href="LICENSE">
    <img src="https://img.shields.io/badge/License-GPL--3.0-blue?style=for-the-badge&logo=gnu&logoColor=white" alt="License: GPL-3.0">
  </a>
  <img src="https://img.shields.io/badge/Status-Planning-orange?style=for-the-badge" alt="Status: Planning">
</p>---

Overview

WSpoof is a planned Windows utility for managing supported system settings, testing identification values, and applying reusable configuration profiles.

Built with C# and Windows Presentation Foundation (WPF), WSpoof uses the actual "WPF UI" (https://github.com/lepoco/wpfui) library for its Fluent Design interface.

Planned Features

- Dashboard — System information, hardware status, network status, and quick actions.
- Windows — Windows information and supported system settings.
- Hardware — Hardware information, supported device settings, and simulated identification values for testing.
- Network — Network adapter information and supported network settings.
- Games — Game testing profiles and supported application settings.
- Browser — Browser identification and user-agent testing.
- Applications — Application profiles and supported configuration options.
- Profiles — Create, preview, apply, import, and export profiles.
- Restore Center — Restore supported settings when original values have been saved.
- Logs — Review changes, errors, and operation results.
- Settings — Application preferences, themes, and update settings.
- GitHub Releases — Check for updates and view release information inside the app.

Interface

WSpoof is planned to include:

- Fluent Design styling using real WPF UI controls.
- Dark and light themes.
- Windows system accent colors.
- A custom title bar with standard window controls.
- A dashboard displaying real detected system information.
- In-app status messages and operation history.
- No toast notifications.

Profiles and Recovery

Profiles will group supported settings into reusable configurations.

Before applying a profile, WSpoof will preview the planned changes and request confirmation. Original values will be saved wherever restoration is supported.

If an operation fails during profile application, WSpoof will stop at the first failure, preserve earlier successful changes, and mark remaining changes as skipped. Automatic rollback is not planned.

Profiles are intended to use local storage with JSON import and export.

Transparency and Safety

WSpoof aims to distinguish actual system changes from simulated testing values.

- Features will identify whether they change Windows or only use simulated values.
- Changes will be verified wherever possible.
- Unsupported operations will be clearly identified.
- Restoration will only be offered when supported.
- Imported profiles will be validated and will not execute arbitrary commands.
- The project is not intended to bypass anti-cheat systems, licensing restrictions, or security protections.

Not every hardware identifier can be changed through ordinary Windows settings.

Updates

WSpoof is planned to check GitHub Releases for newer stable versions at startup.

Update information will appear inside the application. Updates will never be forced, and WSpoof will remain usable if an update check fails.

Development Status

"Development Status" (https://img.shields.io/badge/Development-Planning-orange?style=flat-square)

WSpoof is currently in the planning stage. The features described above are planned and may change during development.

License

WSpoof is licensed under the GNU General Public License v3.0 (GPL-3.0).

See ""LICENSE"" (LICENSE) for the full license text.

Acknowledgements

- "WPF UI" (https://github.com/lepoco/wpfui) — Fluent Design controls and components for WPF.
- "Shields.io" (https://shields.io/) — Project badges.

---

<p align="center">
  Made with C# and WPF UI.
</p>