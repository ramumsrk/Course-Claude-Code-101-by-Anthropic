# Installing Claude Code
```bash
mkdir ${HOME}/Documents/ata_1_0_TiB/claude.ai/

curl --silent --show-error --location --output-dir ${HOME}/Documents/ata_1_0_TiB/claude.ai/ --remote-name --url 'https://claude.ai/install.sh'

sudo --user root --group root /bin/bash ${HOME}/Documents/ata_1_0_TiB/claude.ai/install.sh
[sudo] password for ramumsrk: 
Error: do not run this installer with sudo.

Claude Code installs into your home directory and does not need root access.
With sudo, the installation would go into root's home directory instead of
yours, and the 'claude' command would not work from your own shell.

Please re-run the same command without sudo, e.g.:
    curl -fsSL https://claude.ai/install.sh | bash

To intentionally install Claude Code for the root user, re-run with
CLAUDE_INSTALL_ALLOW_SUDO=1 set in the installer's environment, e.g.:
    curl -fsSL https://claude.ai/install.sh | sudo CLAUDE_INSTALL_ALLOW_SUDO=1 bash

/bin/bash ${HOME}/Documents/ata_1_0_TiB/claude.ai/install.sh
Setting up Claude Code...

✔ Claude Code successfully installed!

  Version: 2.1.312

  Location: ~/.local/bin/claude

  Next: Run claude --help to get started

✅ Installation complete!
```