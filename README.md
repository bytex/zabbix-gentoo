# zabbix-gentoo
Zabbix configuration files for Gentoo

## GLSA

First you need to emerge the gentoolkit package.

```bash
emerge gentoolkit
```

To update the /tmp/glsa.log, use this command at any time you like:

```bash
glsa-check -c -l affected 2>/dev/null >/tmp/glsa.log
```

## Backup

For convenience, backup disk is mounted to /mnt/backup
Multiple directories under /mnt/backup considered to be multiple backup storage.
