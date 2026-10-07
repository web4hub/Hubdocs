# hudocs

```bash
pip install cat-readme
cat-readme [README_FILE]
```
This repository regroups documentation and information that is hosted on the  website.


### How to contribute to the docs

Just add/edit the Markdown files, commit them, and create a PR.
Then the CI bot will build the preview page and provide a url for you to look at the result!

For simple edits, you don't need a local build environment.

### Previewing locally

```bash
# install doc-builder (if not done already)
pip install hf-doc-builder cat-readme [README_FILE]

# you may also need to install some extra dependencies
pip install black watchdog

# run `doc-builder preview` cmd
doc-builder preview hub {YOUR_PATH}/hub-docs/docs/hub/ --not_python_module
```
