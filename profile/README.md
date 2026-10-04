# Basalt OS

A Linux distribution based on Fedora, built security and AI first, by
[OpenBasalt](https://openbasalt.org).

AI agents can do real work on the system through typed, auditable actions,
always confined, previewed and confirmed by a person. When security and AI pull
apart, security sets the limits.

Basalt OS is pre-alpha. Nothing is released as stable yet, and there is nothing
to download: today you can build the installer from the source and try it in a
virtual machine.

Working in the source today: SELinux enforcing on every install, LUKS2 disk
encryption unlocked by the TPM2, a snapshot before and after every package
change with rollback, Secure Boot, signed packages from
[obpkg.org](https://obpkg.org), a confined local assistant that applies nothing
without your confirmation, and a desktop shell prototype. In development: a
desktop edition with voice, approvals from a paired phone, and a live ISO.

| Repository | What |
|---|---|
| [basalt-os](https://github.com/basalt-os/basalt-os) | The system and its tools. |
| [basalt-shell](https://github.com/basalt-os/basalt-shell) | The desktop shell prototype. |
| [vsm](https://github.com/basalt-os/vsm) | The small decision model behind the assistant: overview, results and release verification. |
| [feedback-worker](https://github.com/basalt-os/feedback-worker) | The service behind the feedback form. |
| [basalt-os.org](https://github.com/basalt-os/basalt-os.org) | The website. |

Details, the roadmap and a way to tell us what you think are on
[basalt-os.org](https://basalt-os.org). A person reads every message.

Basalt OS is an independent project, not affiliated with or endorsed by the
Fedora Project or Red Hat.
