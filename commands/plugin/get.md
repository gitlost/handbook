# wp plugin get

Get details about an installed plugin.

### OPTIONS

&lt;plugin&gt;
: The plugin to get.

[\--field=&lt;field&gt;]
: Instead of returning the whole plugin, returns the value of a single field.

[\--fields=&lt;fields&gt;]
: Limit the output to specific fields. Defaults to all fields.

[\--format=&lt;format&gt;]
: Render output in a particular format.
\---
default: table
options:
  - table
  - csv
  - json
  - yaml
\---

### EXAMPLES

    $ wp plugin get bbpress --format=json
    {"name":"bbpress","title":"bbPress","author":"The bbPress Contributors","version":"2.6-alpha","description":"bbPress is forum software with a twist from the creators of WordPress.","status":"active"}


