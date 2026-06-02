# PunamIDE v0.1.0 Alpha

## Overview

PunamIDE v0.1.0 Alpha is the first public alpha release of PunamIDE, an AI-powered desktop IDE built with Rust and Tauri.

Most IDEs added AI.  
PunamIDE was built around surviving AI mistakes.

This release focuses on Windows alpha testing, native snapshots, AI-assisted workflows, technical debt intelligence, Git workflows, terminal workflows, and early diagnostics.

Website: [https://punamide.com](https://punamide.com)  
Discord: [https://discord.gg/PFp9KWY3eY](https://discord.gg/PFp9KWY3eY)

## Features

### AI Chat

Ask PunamIDE questions about your project, code structure, debugging problems, and development workflow.

### Native Snapshots

Create native project checkpoints before risky AI edits, refactors, or experiments.

Snapshots help you:

- Save a known-good state.
- Export backups as zip files.
- Restore when an AI change breaks your code.

### Technical Debt Intelligence

Analyze project complexity, identify refactor candidates, and understand technical debt signals inside the IDE.

### Git Integration

Use built-in Git-aware workflows to inspect and reason about project changes.

### Terminal Integration

Run commands and inspect terminal output inside the PunamIDE workspace.

### Error Reporting and Local Logs

PunamIDE includes early alpha diagnostics:

- Error reporting.
- Local log export.
- Diagnostics generation.
- Crash-friendly error screens.

## Known Issues

- Windows alpha only.
- Some workflows may be incomplete.
- Some UI states may change between alpha builds.
- AI provider setup may require manual configuration.
- Snapshot restore should be tested before relying on it for critical projects.
- Terminal behavior may vary by system configuration.
- Error reporting and diagnostics are still being refined.

## Installation

1. Download the installer asset:

   ```text
   PunamIDE-Setup.exe
   ```

2. Run the installer.
3. Launch PunamIDE.
4. Configure your AI provider if required.
5. Open a project folder.
6. Create a snapshot before trying risky AI edits.

## Feedback

Please report bugs using GitHub Issues and include:

- PunamIDE version.
- Windows version.
- Steps to reproduce.
- Screenshots.
- Exported logs or diagnostics if available.

Do not include API keys, tokens, private source code, or sensitive project data.

## Discord

Join the alpha community:

[https://discord.gg/PFp9KWY3eY](https://discord.gg/PFp9KWY3eY)

Use Discord for:

- Announcements.
- Download help.
- Bug reports.
- Feature requests.
- General discussion.

## Roadmap

Planned next steps:

- Improved installer and update flow.
- Stronger snapshot history and restore UX.
- More technical debt intelligence.
- Better Git diff and review workflows.
- Improved AI provider onboarding.
- More diagnostics and crash reporting.
- Expanded documentation.
- Future platform support after Windows alpha stabilizes.
