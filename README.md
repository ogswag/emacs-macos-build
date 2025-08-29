# Explanation

I really don't like building (and rebuilding) Emacs Plus on my personal Macbook and always wanted to have a simple downloadable Emacs.app for any modern
macOS version I might install.

This repo contains a single Github Workflow file - main.yml, which builds `emacs-plus@31 --with-imagemagick --with-c9rgreen-sonoma-icon` with macos-13 Github Actions runner.
To build it you have to manually run the workflow, because building on every push is A - takes too much time and is not necessary and B - I will not be pushing much into this repo, but might need building anyways.
