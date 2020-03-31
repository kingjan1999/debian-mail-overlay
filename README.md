## hardware/debian-mail-overlay

### Fork of [hardware/debian-mail-overlay](https://github.com/hardware/debian-mail-overlay) with updated dependencies

This overlay base image contains Debian 10 "Buster" slim (remove some extra files that are normally not necessary within containers, such as man pages and documentation), compile skarnet.org's small & secure supervision software suite (skalibs, execline, s6) and build Rspamd, the fast, free and open-source spam filtering system.

Software built from source:

* Skalibs 2.9.2.0 : https://skarnet.org/software/skalibs/
* Execline 2.6.0.0 : https://skarnet.org/software/execline/
* s6 2.9.1.0 : https://skarnet.org/software/s6/
* Rspamd 2.4 : https://rspamd.com/
* Gucci 0.1.0 : https://github.com/noqcks/gucci/

Please see the [main repository](https://github.com/kingjan1999/mailserver) for instructions.
