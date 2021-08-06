# notes
Encrypted wiki/dairy/zettlekasten powered by vimwiki, markdown, gpg, and a shell script

This setup uses my simple notes script in order to manage encryption, editing, and git anywhere on my system.

## usage

Add the notes script to your `$PATH`, and edit the `$WIKIDIR` variable to where you store your wiki

`notes [command]`

decrypt, open notes in $EDITOR, and encrypt on exit
`notes`

encrypt with gpg public key, commit, push to git remote
`notes push`

create new zettlekasten 
`notes zet new`

create new diary entry
`notes diary new`

view wiki
`notes wiki`
