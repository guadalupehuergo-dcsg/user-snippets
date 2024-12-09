# user-snippets

Improve your coding speed using these sample snippets, including debugging.

Code > File > Preference > Configure User Snippets > Select Typescript > Paste

### How to contribute?

1. Fork this repo
2. Add a new snippet
3. Open a Pull request

### Snippet structure

Place your snippets for typescript here. Each snippet is defined under a snippet name and has a prefix, body and 
description. The prefix is what is used to trigger the snippet and the body will be expanded and inserted. Possible variables are:
$1, $2 for tab stops, $0 for the final cursor position, and ${1:label}, ${2:another} for placeholders. Placeholders with the 
same ids are connected.

Example:

```json
 { 
	"Print to console": { 
	 	"prefix": "log", 
	 	"body": [ 
	 		"console.log('$1');", 
	 		"$2" 
	 	], 
	 	"description": "Log output to console" 
} 
``` 


Updated: 10/05/2023 by [Daniel Naranjo](https://github.com/danielnaranjo)

### Package.json for pdp ssr for windows

Place your snippets for json in the json.json file. Each snippet is defined under a snippet name and has a prefix, body and 
description. The prefix is what is used to trigger the snippet and the body will be expanded and inserted. Possible variables are:
$1, $2 for tab stops, $0 for the final cursor position, and ${1:label}, ${2:another} for placeholders. Placeholders with the 
same ids are connected.

To use just delete the line we are replacing and type ssrlocal + tab


