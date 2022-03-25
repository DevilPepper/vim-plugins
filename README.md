# vim-plugins

Vim plugins as git submodules.

1. Use `git clone --recurse-submodules` to clone this repo
2. After a `git pull` run `git submodule update --init --recursive`
3. To add a new plugin, `git submodule add <repo> <path>`, where `<path>` is be either of these:
   - _{plugins|dependencies}/start/**plugin_name**_
   - _{plugins|dependencies}/opt/**plugin_name**_
