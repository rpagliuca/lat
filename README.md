lat
===

lat - [l]ist [a]ll [t]ext-files

small tool to recursively list all text-files in a folder, and search and replace on them.

usage:
lat [[-g 'string_to_grep']|[-r 'replace_pattern']|[-c]]"

Available parameters:

* no parameters -> list recursevely all text-files of a folder
* g -> grep (search)
* r -> search and replace
* c -> remove backup files generated during searching and replacing
