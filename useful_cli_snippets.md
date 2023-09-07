# Useful command line snippets

A few handy snippets I've come across for basic day-to-day use in the Unix/Linux environment. 

## Quick review of previous commands, and re-running a particular command:
`history -n` (with "n" being the number of history)
`!<number>`  (run a chosen previous command based on the number displayed by the `history` command)

### human readable apparent size (Linux)
`du-sh --apparent-size`
(need to figure out MacOS equiv)

### list all files in a .zip file
`unzip -l foo.zip`

`unzip -l foo.zip > foo_files.csv`
(redirect the output to a csv)