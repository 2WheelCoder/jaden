## Installation

    $ npm install -g jaden

## Usage

    $ jaden [options]

    Options:

      -h, --help                                  output usage information
      -V, --version                               output the version number
      -t, --templates <path/to/templates/folder>  specify template folder
      -d, --destination <path/to/output/file>     specify output destination
      -p, --pattern [regex]                       file pattern to match. Only filenames matching this pattern will be included.
      -m, --minify                                classic minification using uglify-js
      -w, --watch                                 watch for changes and regenerate
      -n, --namespace [string] set the namespace. example: "window.Application.templates" defaults to "window.templates".
      -r, --requirejs                             export templates as a requirejs module (namespace required)
      -b, --browserify                            export templates for browserify