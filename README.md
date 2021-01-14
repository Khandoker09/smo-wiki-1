# How to build

1. clone repository
2. cd into project directory
3. run `bash build.sh` This:
    1. pulls the latest markdowns from the Wiki
    2. copies/replaces them into/in the `docs/` directory
    3. processes the markdown so that it becomes digestible by jekyll
    4. pushes the changes back to the repository


# How to change website design and Layout

To change the website layout follow instructions by Theme creators (Github supported Minimal theme): https://github.com/pages-themes/minimal

The changes made to the theme so far are in:

 -  `docs/_layouts/default.html`
 -  `docs/assets/css/style.scss`