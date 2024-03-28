# Prerequisites for GPG signing

`export GNUPGHOME=path-to-keyring`

`gpg --list-secret-keys --keyid-format=long`

`git config --local user.signingkey key-id`

`git config --local commit.gpgsign true`
