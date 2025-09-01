# Distrobox Assemble Files
Various Distrobox assemble files to use on first boot / container rebuilding

General container setup scripts are in the root of the repository (ex: base-containers.ini). Application specific containers that install and setup non-containerized (ex: .deb, .rpm, etc.) or Flatpak based applications are located in `app-specific`.

By default, each container has a seperate home and is located in the user's home folder under `Distrobox`.

## Quick start

1. Follow the steps as outlined in [Distrobox's website](https://distrobox.it/#installation) to install for your system / Distro
2. Clone the repo by doing:
```bash
git clone https://github.com/Zac-dot/distrobox-assemble-files.git
git cd distrobox-assemble-files
```
3. Run the following assemble file using `distrobox-assemble create --file /path/to/file.ini`
