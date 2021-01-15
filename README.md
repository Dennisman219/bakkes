# Bakkes
Bakkes is a simple command-line tool for saving and restoring files.

## Usage
`bak <option> <filename>`

Flag | Option | Description
--- | --- | ---
&nbsp; | no option | Create backup of file. Requires filename
-r | restore | Restores file from backup. Requires filename
-l | list | Lists saved files
-d | delete | Delete saved file. Requires filename
-da | delete all | Delete all saved files

### Examples
`bak file.txt`\
Creates a backup of 'file.txt'

`bak -l`\
List all saved files

`bak -r file.txt`\
Restores 'file.txt' from saved backup

`bak -d file.txt`\
Delete backup of 'file.txt'. Original file remains