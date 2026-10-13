# Arborist for macOS

Careful cleanup for Git worktrees, with a restorable Trash.

Download Arborist and read release notes on the [Releases page](https://github.com/ten-thousand-hammers/arborist/releases).

Arborist requires macOS 14 or later and supports Apple Silicon and Intel Macs.
The app checks for updates through GitHub releases. Use **Arborist → Check for Updates…** to check manually.

This repository hosts downloads and release notes. Application source code is maintained separately.

## Reporting a problem

Describe what happened, what you expected, and the Arborist and macOS versions in a [bug report](https://github.com/ten-thousand-hammers/arborist/issues/new?template=bug-report.yml).

For builds with the diagnostic menu, select **Help → Send Diagnostic Report…**.
Describe the problem, review the snapshot, and select **Send Report**.
The report goes to the Arborist BugSink server at `bugsink.10000hammers.com`. Keep its report ID for support.
Your description is included exactly as typed.
You can also select **Help → Save Diagnostic Report…** and attach the JSON file to a GitHub issue.
Reports include scan progress, operation timing, and failures. Repository paths, command arguments, output, environment values, and session contents are excluded.
Hover over a repository in the sidebar to match its current-session diagnostic ID.
Nothing is uploaded automatically.

If the app does not respond, newer builds retain diagnostic snapshots in `~/Library/Application Support/Arborist/Diagnostics/`.
Attach `current.json` and, after a restart, `previous.json` if available.
For versions without diagnostics, open Activity Monitor, select Arborist, use **Sample Process**, and save the sample.
Review samples and screenshots before attaching them to this public repository.
