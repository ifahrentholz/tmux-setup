 ### Installation

```bash
$ git clone https://github.com/ifahrentholz/tmux-setup
$ ln -s ~/.tmux.conf ~/.tmux.conf
```

### Start VIM and install bundles 
```bash
BundleInstall
```

### Installing plugins

1. add a new plugin to the `@tpm_plugins` list
2. hit `prefix + I` (I as in *I*nstall) to fetch the plugin

You're good to go! The plugin was cloned to `~/.tmux/plugins/` dir and sourced.


### Uninstalling plugins

1. remove plugin from `@tpm_plugins` list
2. hit `prefix + alt + u` (u as in *u*install) to remove the plugin

All the plugins are installed to `~/.tmux/plugins/` so if you want you can just
find plugin directory there and remove it.


### Key bindings

`prefix + I`
- installs new plugins from github or any other git repo
- refreshes TMUX environment

`prefix + U`
- updates plugin(s)

`prefix + alt + u`
- uninstall unused plugin(s)


### List of plugins

For more plugins, check [here](https://github.com/tmux-plugins).


### Wiki pages

More advanced features, regular users probably do not need this:

- [installing plugins via the command line](https://github.com/tmux-plugins/tpm/wiki/Installing-plugins-via-the-command-line-only)
- [changing plugins install dir](https://github.com/tmux-plugins/tpm/wiki/Changing-plugins-install-dir)
