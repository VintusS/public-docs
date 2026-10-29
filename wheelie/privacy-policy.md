# Wheelie Privacy Policy

**Effective date: 29 October 2026**

**Developer: Dragomir Mindrescu**

This policy explains how Wheelie, also listed as **Wheelie: Radial Launcher**, handles information when you use the macOS app, contact its developer, or participate in beta testing.

## Overview

Wheelie is a menu bar launcher for apps, websites and workflows. Its configuration and routine action processing stay on your Mac. It does not require a Wheelie account, operate a developer-controlled backend, include advertising or third-party analytics SDKs, or sell personal information. Wheelie does not track you across other companies’ apps or websites.

Some actions deliberately pass information to apps, websites, Shortcuts or scripts you choose. Support messages and Apple’s distribution and beta-testing services involve separate data handling, described below.

## Information stored on your Mac

Wheelie saves your wheels and preferences locally in its macOS sandbox. This can include:

- Wheel and action names, symbols, order and appearance.
- App identifiers, website addresses, Shortcut names and action settings.
- Keyboard shortcut and trigger preferences, optional gesture/haptic preferences, and app-to-wheel assignments.
- Text you explicitly save as an action’s fallback input.
- References to files, folders, scripts and working directories you select, including macOS security-scoped bookmarks and local script approvals.
- Setup and interface preferences stored through macOS preferences.

Configuration is not uploaded to the developer or synchronized by Wheelie. It is not encrypted separately by Wheelie; protection depends on your Mac’s permissions and security settings. Copies in a folder you choose, device backups or cloud-backed storage are also subject to those services and settings.

Wheelie may preserve older configuration files during migration or recovery so that your settings are not lost. Those local backups can contain the same information as the original configuration.

## Information used to perform actions

### Clipboard and selected content

Wheelie reads clipboard text when you invoke a workflow configured to use Clipboard Text. If you choose a Shortcut output setting that copies results, it writes that result to the system clipboard.

When you use **Services → Show Wheel with Selection**, the source app supplies selected text or file references. A selected-text action may also attempt to read the originating app’s selection when macOS permissions and sandbox restrictions allow it. Wheelie does not substitute unrelated clipboard contents when selected input is missing.

Action input is processed in memory for the requested workflow rather than written to Wheelie’s configuration, unless you deliberately save text as fallback input. Output or recent execution details may remain visible in the app until cleared, replaced or the app quits. Receiving apps, Shortcuts, scripts and the system clipboard can retain their own copies.

### Files, scripts and automation

Wheelie accesses resources you explicitly select or configure for an action. Security-scoped bookmarks allow it to request access again later. Advanced actions may read a chosen script, use its selected working folder, pass configured arguments to a user-installed AppleScript attachment, or request a keyboard action in the originating app.

What those scripts and workflows do depends on their contents and permissions. They can change files or communicate with other services independently of Wheelie’s local configuration. Review them before running them and grant only the access you intend. Removing an action does not undo work already performed by a script or external app.

### App context, Focus and pointer input

Wheelie uses information about the originating app to choose an assigned wheel and route the requested action. If you configure a macOS Focus filter, it uses the wheel selection supplied by that system filter. This does not create a developer-accessible history of your app use or Focus activity.

Keyboard shortcut registration and recording are used to recognize or configure your trigger, not to record general typing. If you enable the shake gesture, Wheelie processes pointer movement and button/modifier state locally to recognize it. It does not save or transmit a pointer-movement history.

## Information passed to other apps or services

Opening a website passes its address to your browser. Running a Shortcut can pass the configured text or selected file URLs to Apple Shortcuts. Opening a file or app hands the request to macOS and the selected application. Script attachments and keyboard actions use the workflow and destination you configure.

Those destinations may process or transmit the information under their own privacy policies and your settings. Wheelie does not send an additional copy of that content to the developer. File URLs passed as text do not themselves transfer the file’s contents or grant access to it.

## Exports and sharing

Wheelie can export configurations or portable JSON wheel presets to a location you choose. Portable exports remove local resource bookmarks and script approvals, but can still include labels, app identifiers, URLs, Shortcut names, action settings and saved fallback text. Script files are not included in those exports.

Review an export before sharing it. A private copy of Wheelie’s original configuration can contain bookmark data and should be handled as a private backup. Wheelie does not automatically publish or upload your exports.

## Diagnostics, support and beta testing

### Wheelie diagnostics

The diagnostics feature creates a local report that you can preview and choose to copy. It contains version/build and operating-system information, source revision, aggregate action/wheel counts, display count and status information such as hotkey registration, file recovery, login-item and Accessibility trust status.

That report excludes wheel/action names, website addresses, file paths, bookmarks, clipboard and selected text, saved fallback text, and script input/output. Wheelie does not automatically upload the report. It also writes limited operational messages to macOS system logging, such as editor presentation state; these are separate from the diagnostic report and managed by macOS.

### Contacting the developer

If you contact support, the developer receives the contact information, message and any attachments you provide. This information is used to answer your request, investigate reported problems and maintain Wheelie. Email providers process the correspondence to deliver and store it.

Send only information needed to explain the issue. Avoid passwords, private configuration files or unreviewed script output. GitHub issues and comments are public if you choose to post there; use email for private requests.

### Apple services and TestFlight

Apple handles App Store downloads, updates and platform-level diagnostics under its own terms and privacy policies. The developer may receive the reports and aggregate information that Apple makes available through those services.

If you install a beta through TestFlight, Apple automatically collects crash logs and usage information and shares them with the developer; this collection is part of TestFlight and cannot be disabled within Wheelie. Invitations and feedback may also expose your name, email address, device/build information, screenshots or comments, depending on how you join and what you send. The developer uses this information to manage testing and diagnose or improve Wheelie, and does not share TestFlight-provided personal information with third parties.

See [Apple’s TestFlight & Privacy notice](https://www.apple.com/legal/privacy/data/en/test-flight/) for details and Apple’s retention and privacy controls.

## Retention and deletion

- **Local settings:** retained until you remove or replace them. Delete unwanted actions and saved text in Settings. To remove all local configuration, use **Settings → Diagnostics → Show Configuration in Finder**, quit Wheelie, and remove its configuration and any preserved backup files. Also remove any exports, preferences or device backups you no longer want. Deleting the app alone may leave local data behind.
- **Temporary action data:** held in memory for invocation or execution/result handling. Clear available result views or quit Wheelie to discard the app’s in-memory results. This does not delete copies held by the clipboard, another app, a script or an external service.
- **Support and downloaded diagnostic records:** retained only as needed to handle the request, investigate related issues, or meet applicable legal obligations. Records no longer needed are deleted or anonymized. You can request deletion using the contact details below.
- **Apple-hosted beta and diagnostic records:** managed under Apple’s retention rules. Any copies downloaded by the developer are kept only while needed to investigate or resolve the relevant issues. Contact the developer about information received from Apple; use Apple’s privacy controls for data held by Apple.

The developer cannot remotely read or delete Wheelie configuration stored only on your Mac. Removing local data does not remove copies you have already shared or that remain in backups.

## Your choices and rights

You can disable optional triggers and feedback, change input/output settings, remove configured actions, and manage file access and script approvals. macOS manages system-level permissions and login-item approval; review those in System Settings. Withdrawing access can prevent the related action from working.

Depending on the law that applies to you, you may have rights to access, correct, delete or receive a copy of personal information held by the developer, or to object to or restrict its use. Where processing depends on consent, you can withdraw it. Contact the developer to make a request or raise a concern; you may also have the right to contact your local data-protection authority.

Support correspondence is used to provide the help you request. Troubleshooting and beta records are used for the developer’s interest in maintaining a reliable app, subject to applicable law. Processing needed to comply with a legal obligation is limited to that purpose. This policy does not replace any permission or consent required for an optional feature.

Wheelie does not ask for your age or create profiles of children. If you believe a child has sent personal information to support, contact the developer so it can be reviewed and removed where appropriate.

## Security and services outside the app

Wheelie uses App Sandbox, hardened runtime and macOS-supported resource-access mechanisms. These controls do not make files, messages or workflows immune from loss or unauthorized access. Protect your Mac and review scripts and exports before using or sharing them.

This policy is hosted on GitHub. Visiting it is subject to [GitHub’s Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement). The developer’s website, email, Apple services and destinations you choose can process information in countries other than your own under their respective policies. Their hosting and communications practices are separate from Wheelie’s local operation.

## Changes to this policy

Updates will be published at this document’s existing address with a revised effective date. Previous versions remain available in the repository’s commit history. If a change requires additional notice or consent, it will be provided as required by applicable law.

## Contact

**Dragomir Mindrescu**

Privacy and support: [dmindrescu03@gmail.com](mailto:dmindrescu03@gmail.com)

Website: [www.dragosh.dev](https://www.dragosh.dev)

Please identify Wheelie in your message and describe the information or request involved.
