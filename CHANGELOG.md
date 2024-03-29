# Changelog
All notable changes to `Toggle-WSL` will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).

## [1.2] - 2023-02-10
### Changed
- Minor improvements to console logging.
- Minor improvements to comments in code.
- Added license information to the script header.
- Updated README.md with Windows 11 and license information.

## [1.1] - 2021-02-11
### Added
- Show which features require double reboot, if any.
- Show script mode: possible values are SAVE and RESTORE.

### Changed
- Switch code formatting to K&R Stroustrup brackets style.
- Simplified `Settings` section.
- Bugfix: double reboot script was created before receiving user confirmation.
- Bugfix: remove hardcoded path making the script not work when launching itself with admin privileges.

### Removed
- Removed unused `globalPadding` variable (leftover from previous output formatting code).

## [1.0] - 2021-01-20
### Added
- Initial release.
