# Funtoo Pyfa Overlay

The most recent [pyfa](https://github.com/pyfa-org/Pyfa) versions for Funtoo.
Forked from [gentoo-pyfa-overlay](https://github.com/ZeroPointEnergy/gentoo-pyfa-overlay.git).

## Add repo manually

To configure the repo manually add the following config to `/etc/portage/repos.conf/pyfa.conf`:

    [pyfa]
    priority = 50
    location = /var/git/pyfa
    sync-type = git
    sync-uri = git://github.com/ac0ra/funtoo-pyfa-overlay.git
    auto-sync = Yes
