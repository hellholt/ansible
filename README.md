# Hellholt::Ansible

This repository contains the inventory, roles, etc for managing Hellholt, my homelab.

This is super-specific to my evolving (but still thoroughly stupid) understanding of computers, networks, virtualization, Kubernetes, Ansible, etc.  It's public mostly just in case someone might find something useful here.

## Notes

### Naming

Each individual host is given the name of a major house from _A Song of Ice and Fire_.  You know, the _Game of Thrones_ books.  Each cluster of hosts is given the name of a castle.  Those two conventions combined don't really make a whole lot of sense, but individually they kinda do, and it gives me a few hundred interesting names with personal associations, color schemes, emoji, etc to work with.

### Vault

Although this repository does contain a vault, its contents are limited in number and restricted to essential information.

The structure of the vault is as follows:

```yaml
vault:
  proxmox:
    nodes:
      ryswell:
        api:
          username: <string>
          password: <string>
      ...

```

### Bash Scripts

I mostly use Bash for the actual day-to-day CLI stuff.  For these scripts, see the [bash repo](https://github.com/hellholt/bash).
