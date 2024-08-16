# gitconfig-template

## Configuration
|Setting|Command|
|---|---|
|Disable rebase on pull|`git config --global pull.rebase false`|
|Enable commit signing (not compatible with Azure DevOps|`git config --global commit.gpgsign true`|
|Enable ssh commit signing|`git config --global gpg.format ssh`|
|Set user signing key|`git config --global user.signingkey 'PATH_TO_PUBLIC_KEY'`|
|Prune on fetch|`git config --global fetch.prune true`|
|Enable learning of merge conflicts|`git config --global rerere.enabled true`|
|Use columns on list commands|`git config --global column.ui auto`|
|Sort branches by comitter date|`git config --global branch.sort committerdate`|
|Enable auto setup remote|`git config --global push.autosetupremote true`|
