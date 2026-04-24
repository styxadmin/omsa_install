# omsa_install.sh

Simple automated script to install Dell OMSA on Dell PowerEdge R720.

Tested on Proxmox 9.1.9 which runs on Debian 13

For Dell R720, use option 2 (11.0.1.0)

## Requirements

- Git *(Needed for install and self-update to work)*

## Install

This script is self-updating. The self-update routine uses git commands to make the update so this script should be "installed" with the below command.

`git clone https://github.com/styxadmin/omsa_install.git`

**UPDATE: If you decide not to install via a git clone, you can still use this script, however, it will just skip the update check and continue on.**

## Usage

```bash
./omsa_install.sh [-dh]

  -h | h    - Display (this) Usage Output
  -d | d    - Enable Debug (Simulation-Only)

```

## Screenshot

![omsa_install](https://user-images.githubusercontent.com/48564375/150648855-f7de1207-dba3-44bd-b927-f559f19ade5a.png)
