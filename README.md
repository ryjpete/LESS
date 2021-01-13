# LESS

A group of LESS files for project start. Whether good or bad, the way this is set up is...

* All variables are within _vars.less_.
* _imports.less_ imports all resource LESS files and _vars.less_.
* Resource LESS files (everything but _imports.less_, _style.less_, and _vars.less_) contain mixins that can be used throughout. The mixins were mainly created from basic CSS options.
* _style.less_ imports imports.less, and is used as the main custom stylesheet.