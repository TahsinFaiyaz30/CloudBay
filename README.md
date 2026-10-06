# CloudInlet legacy update bridge

CloudBay is now **CloudInlet**. The source, issues, documentation and current releases are at [TahsinFaiyaz30/CloudInlet](https://github.com/TahsinFaiyaz30/CloudInlet).

This repository exists only because published CloudBay updaters require this exact repository path, `updates-v1.json`, and the old package filenames. It provides the static **1.1.2** upgrade to CloudInlet. After installing it, CloudInlet checks the new repository for subsequent releases. The old filenames contain the same CloudInlet installer bytes as the canonical release.

Existing accounts, backups, transfer recovery and installation choices are retained. Check for updates inside your existing app. Choose the same Release/Debug flavor and EXE/MSI format when installing manually.

Historical published versions and the full source history remain in the [canonical CloudInlet releases](https://github.com/TahsinFaiyaz30/CloudInlet/releases). Keep this bridge available for users who have not upgraded; do not rename or delete it.