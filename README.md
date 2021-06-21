# wiki
Encrypted wiki/dairy/notes powered by vimwiki, markdown, and gpg

Note: this wiki setup uses my simple [wiki script](https://github.com/skovati/scripts/blob/master/wiki) in order to manage encryption, editing, and git anywhere on my system.

## usage

Add the wiki script to your `$PATH`, and edit the `$WIKIDIR` variable to where you store your wiki

`wiki [command]`

decrypts, opens vimwiki in $EDITOR, and encrypts on exit
`wiki edit`

encrypts with gpg public key, commits, pushes to remote git repo
`wiki push`
