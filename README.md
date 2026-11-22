# cicdteam Homebrew tap

[ldaplens](https://github.com/cicdteam/ldaplens): a web UI to browse,
search and edit LDAP, for OpenLDAP and Active Directory.

```sh
brew install cicdteam/tap/ldaplens
ldaplens
```

It runs in local mode, opens the UI in your browser and keeps saved
connections in your user config directory. `brew upgrade` brings new
releases. macOS (Apple silicon and Intel) and Linux (amd64, arm64).

The formula installs the release binaries and is rendered from each
release's `ldaplens_checksums.txt` by `render.sh`; the Update workflow
does that once a day and on demand, and installs the result on both macOS
architectures.
