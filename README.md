# mkdocs-demo

Demo repository to setup mkdocs. This demo is based on [this youtube tutorial](https://www.youtube.com/watch?v=Q-YA_dA8C20). More information can be found in the [mkdocs-material documentation](https://squidfunk.github.io/mkdocs-material/).

<!-- vscode-markdown-toc -->
* 1. [Install](#Install)
* 2. [Snippets](#Snippets)
* 3. [Publishing Documentation](#PublishingDocumentation)

<!-- vscode-markdown-toc-config
	numbering=true
	autoSave=true
	/vscode-markdown-toc-config -->
<!-- /vscode-markdown-toc -->

---

##  1. <a name='Install'></a>Install

```console
# Install packages
poetry install

# Install pre-commit
pre-commit install
```

##  2. <a name='Snippets'></a>Snippets

```console
# Run server to host your documentation
mkdocs serve

# Build static content
mkdocs build
```

##  3. <a name='PublishingDocumentation'></a>Publishing Documentation

Documentation will be hosted via GitHub-Pages either by updating the documentation manually with:

```console
mkdocs gh-deploy
```

or using the GitHub CI (Actions). The published documentation can be found [here](https://schernhe.github.io/mkdocs-demo/).
When setting up, it might be necessary to adjust the settings for `Pages` to `"Deploy from a branch"`, but that was not the case when setting up this
repository.
