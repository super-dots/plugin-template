# {{cookiecutter.project_name}}

This project is a [superdots](https://github.com/super-dots/superdots) plugin.

* [Description](#description)
* [Installing](#installing)
* [Updating](#updating)

## Description

{{cookiecutter.description}}

## Installing

After installing superdots, record this as a plugin in your ~/.bashrc:

```
source /path/to/superdots/bash_init.sh  # should already be there from installing

superdots {{cookiecutter.github_user}}/{{cookiecutter.github_project}}
```

And then run the command below to install the plugin

```
superdots-install
```

## Updating

To update your local copy of this plugin to the latest version, run the command
below:

```
superdots-upgrade
```
