# RecipeWebsite

Note that to properly download the repo the submodules need to be downloaded before generating new files.
Therefore use
```
git clone --recurse-submodules ...
```
for initial cloning or
```
git submodule update --init --recursive
```
if you forgot initially.

## Make Workflow

Use
```
make html
```
to generate HTML files stored in the output folder.

Use
```
make serve
```
to test the website locally.

When finished editing, `git push` in the master branch and use
```
make github
```
to upload the website to GitHub pages.
