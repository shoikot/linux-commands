### linux-commands

# File related commands

# List File:

- list all files from a folder in a file `ls [FOLDER] > [FILENAME]`
- delete a line matching a pattern `sed -i '/[PATTERN] /d' [FILENAME]`
- add string to start of each line `sed -e 's/^/[STRING_TO_ADD]/' -i [FILENAME]`

### Search
## file

find <LOCATION> <CRITERIA> <VALUE> eg:

name: `find /usr -name home`
name extension: `find /usr -name "*.sh"`
name extension `(case-insensitive): find /usr -iname "*.sh"`
execute command on result (here, copy to /result) `find /usr -iname "*.sh -exec cp {} /result \`
file content
`grep <REGEXP> <FILE> <OPTIONS>`

Eg:

list all lines which contains hello in a file, including line number: `grep hello HelloWorld.sh -n`

Other
eg:

`remove duplicates: (..) | uniq e`


