## Repo for CapRover One Click Apps

This repository provides **Caprover** one-click templates for the following applications:
* coturn
* openfire

For the build to work, make sure:
* workflow actions are configured for main or master - depending on the settings
* create `gh-pages` branch and configure github pages on that brunch (that's where the compiled code is published)
* create `MY_GITHUB_PERSONAL_TOKEN` secret with GitHub PAT allowing access to this repository (used to access repo within actions build)
