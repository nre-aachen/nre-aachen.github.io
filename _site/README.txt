Information on files in our the webpage’s root
——————————————————————————————————————————————
——————————————————————————————————————————————
visit https://jekyllrb.com/docs/usage/ for a 
comprehensive documentation of Jekyll 

_config.yml
———————————
Stores configuration data. Do not use tabs in configuration files!! This will either lead to parsing errors, or Jekyll will revert to the default settings. Use spaces instead. For quick quick reference and tweaking the default settings have been explicitly added to the config-file. Please reset the environment after changing the config file. Jekyll does not monitor changes in this file during development and only sets then when the site is built.


index.html
——————————
Provided that the file has a YAML Front Matter section, it will be transformed by Jekyll into the homepage of our jekyll-generated site.

jekyll.gitignore
————————————————
Files and directories we don’t want Git to check in to GitHub.


.jekyll-metadata
————————————————
This helps Jekyll keep track of which files have not been modified since the site was last built, and which files will need to be regenerated on the next build. This file will not be included in the generated site.


_site
—————
This is where the generated site will be placed (by default) once Jekyll is done transforming it.