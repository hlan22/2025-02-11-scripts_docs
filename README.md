# Creating Automated Scripts through Github Actions

For my Data Science 310 class on February 11th, 2025.

Today we learned about the following:
  - The bash command `Rscript` can either run an R file you give it, or you can write `-e` followed by some R code to run the code in the terminal.
  - A `.sh` file is a shell file, which you can run bash commands through. If you want to run in the bash terminal, you can write `bash <name-of-file>.sh` with the file you want to run.
  - If you write `mkdir -p <name-of-file(s)>`, the `-p` (for parent) allows you to create multiple parent/child directories without having to "step into" them before. It's more of a "quality of life" tip more than anything.
  - A reminder that github will not track empty folders. The call `ls` will ignore any files or folders that start with a `.`. This is because often the files don't end up being interesting, whether they are not useful to what you're looking for commonly. If you want to see all files, you can type in `ls -a`.
  - The folder naming of `.github/workflows/` is VERY important for github to recognize it should be looking at the folders inside for things such as github actions.
  - How to write out a `.yml` file so that it can work for github actions (see comments I wrote on the file).
  - etc.

Credit to Daniel Chen and the DSCI 310 team.
