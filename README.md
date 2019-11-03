# Superdots Plugin Template

This project is pretty meta - it's a [cookiecutter]() template for creating
new superdots plugins. Using this template will stub out all directory
structures required, add some best practices, and get you started on a good
README.md that comes with:

* Description
* Installation instructions
* Upgrading instructions

## Usage

### 1. Install [cookiecutter]() with:

```bash
pip install cookiecutter
```

### 2. Use cookiecutter

After pip installing cookiecutter, you should have the `cookiecutter` command
available. Use it like so:

```
$> cookiecutter https://github.com/super-dots/plugin-template
project_name [my-superdots]:
description [An awesome superdots plugin]:
github_user []: d0c-s4vage
github_project [my-superdots]:
```

This should result in a directory structure like:

```
/tmp/my-superdots/
├── bash-source-pre
├── bash-sources
├── .gitignore
├── README.md
├── tmux_init.conf
└── vim-sources
    ├── ultisnippets
    │   └── sh.snippets
    └── ultisnips.vim
```

### 3. Initialize as a git repo (recommended)

Run the commands below inside of the newly created superdots plugin folder to
initialize it as a git repository:

```
git init
git add -A
git commit -m 'initial superdots commit, yay!'
```

### 4. Push to your source code manager (optional)

If desired, set up a remote repository in a version control manager, and push
your code to it. For github, you must already have created an empty project
to push to:

```
git remote add origin git@github.com:username/my-superdots.git
git push origin master
```
