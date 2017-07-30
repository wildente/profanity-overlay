# Gentoo Overlay for Profanity

## Description
simple and small gentoo portage overlay for profanity from git.
other user overlays are usually bloated with other stuff. i like
minimal repositories.


## Usage

```bash
cat >> /etc/portage/repos.conf/profanity-overlay.conf <<EOF
[profanity-overlay]
location = /usr/local/portage/profanity
sync-type = git
sync-uri = https://github.com/wildente/profanity-overlay.git
EOF
```

