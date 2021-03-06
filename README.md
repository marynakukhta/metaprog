- Pypi publishing: https://realpython.com/pypi-publish-python-package/
- Regex: https://www.programiz.com/python-programming/regex
- Regex online: https://regex101.com/
- Rules index: https://dart-lang.github.io/linter/lints/index.html

# Installation
Download command line utility:
pip3 install dart-code-convention-fixer

Then use: python3 -m dartCCF --help

# Tutorial of app

```
To verify use:
python3 -m dartCCF verify - p /..
python3 -m dartCCF verify - d /..
python3 -m dartCCF verify - f /..

-p - project
-d - directory 
-f - file 

/.. - path to project, directory or file 

To fix use:

python3 -m dartCCF fix - p /..
python3 -m dartCCF fix - d /..
python3 -m dartCCF fix - f /..

-p - project
-d - directory 
-f - file 

/.. - path to project, directory or file 
```

# Implemented:
## STYLE
- lines_longer_than_80_chars
- always_use_package_imports
- camel_case_types
- camel_case_extensions
- library_names
- file_names
- library_prefixes
- constant_identifier_names
- curly_braces_in_flow_control_structures
## DOCUMENTATION
- slash_for_doc_comments
## USAGE
- prefer_is_empty
- prefer_is_not_empty
- avoid_relative_lib_imports
- prefer_adjacent_string_concatenation
- prefer_interpolation_to_compose_strings
- unnecessary_brace_in_string_interps
- prefer_iterable_whereType
- prefer_collection_literals
- avoid_init_to_null
- avoid_catching_errors
- avoid_function_literals_in_foreach_calls # avoid
- prefer_function_declarations_over_variables
- unnecessary_new 
- unnecessary_const
- avoid_catches_without_on_clauses
 
