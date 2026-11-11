# PS4GoldenHell

PS4GoldenHell is a multilingual information portal for the PS4 homebrew community.

## Features

- 13 interface languages: Spanish, English, Portuguese, French, German, Italian, Russian, Japanese, Korean, Simplified Chinese, Arabic, Turkish and Indonesian.
- Firmware lookup based on the firmware list shown in the official GoldHEN v2.4b18 GitHub release.
- Informational modes for listed firmware, unlisted firmware and homebrew information.
- Activity log for page events: startup, language and mode changes, selected firmware, compatibility checks and interface errors.
- Export and clear controls for the activity log.
- Error handling that leaves the page visible and does not request an automatic console shutdown or restart.
- Direct links to the official GoldHEN project and release notes.
- Automatic static deployment through GitHub Pages.

## Activity log behavior

The activity log records only events that this website can actually observe. It is not an exploit trace and does not claim that GoldHEN or a jailbreak has been executed. The log is kept in page memory and can be exported as a text file.

If the page detects an error, it records the error and leaves the console running. It does not call a shutdown or reboot function. The user decides whether to leave the page or restart the console.

## Compatibility data

The lookup marks a firmware as "listed" only when it appears in the official GoldHEN v2.4b18 GitHub release notes. Firmware 12.50 has a separate status in the interface: community documentation describes a homebrew route that uses a Blu-ray-based entry point, but this site does not include or launch that method. The official GoldHEN v2.4b18 GitHub release list checked by this project does not include 12.50. This status is informational, not a compatibility guarantee.

Always check the official release notes for later changes. Do not assume that a payload made for one firmware is compatible with another.

## Scope

This is an informational homebrew portal. It does not contain or execute jailbreak exploits, install GoldHEN, host third-party payload binaries, or distribute commercial game files.

## Enable GitHub Pages

1. Open **Settings → Pages**.
2. Select **GitHub Actions** under **Build and deployment**.
3. Push to `main` or run the workflow from the Actions tab.
4. Open the Pages URL shown in repository settings after a successful deployment.

## Official references

- GoldHEN repository: https://github.com/GoldHEN/GoldHEN
- GoldHEN releases: https://github.com/GoldHEN/GoldHEN/releases

PS4GoldenHell is an independent community project and is not affiliated with Sony or the GoldHEN developers.
