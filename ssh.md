# setup ssh and clone in one command
`ssh-agent $(ssh-add <private-key>; git clone <repo>)`

# ssh keygen
ssh-keygen -t ed25519 -C "<email>"
