# cblack

> a python auto code formatter.
> more information: <https://black.readthedocs.io/en/stable/usage_and_configuration/the_basics.html>.

- auto-format a file or entire directory:

`cblack {{path/to/file_or_directory}}`

- format the code passed in as a string:

`cblack -c "{{code}}"`

- output whether a file or a directory would have changes made to them if they were to be formatted:

`cblack --check {{path/to/file_or_directory}}`

- output changes that would be made to a file or a directory without performing them (dry-run):

`cblack --diff {{path/to/file_or_directory}}`

- auto-format a file or directory, emitting exclusively error messages to `stderr`:

`cblack --quiet {{path/to/file_or_directory}}`

- auto-format a file or directory without replacing single quotes with double quotes (adoption helper, avoid using this for new projects):

`cblack --skip-string-normalization {{path/to/file_or_directory}}`
