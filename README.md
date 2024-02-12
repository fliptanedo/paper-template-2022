# Flip's Paper Template 2022

 `paper-template-2022`
 https://github.com/fliptanedo/paper-template-2022

A LaTeX paper template that I use for papers and notes. Replaces [2021 version](https://github.com/fliptanedo/flip-paper-template-2021); and [even older version](https://github.com/fliptanedo/flip-paper-template).

By Flip Tanedo (flip.tanedo@ucr.edu)

License: CC BY-NC-SA 4.0
https://creativecommons.org/licenses/by-nc-sa/4.0/deed.en

## Other packages used

I include these files in this repository.

* [Jacques Distler's](https://golem.ph.utexas.edu/~distler/TeXstuff/)  `utcaps.bst` 
* [AAS TeX](https://ui.adsabs.harvard.edu/help/actions/journal-macros)'s  `aas_macros.sty`
* [Leo Stein's](https://ctan.org/pkg/orcidlink?lang=en)  `orcidlink.sty`

## Usage Notes

* Place figures in the `\figures` directory. 

# How to use this

1. Go to repo's [page]( https://github.com/fliptanedo/paper-template-2022) on GitHub.

2. Click on the green **Use this template** button and select **Create a new repository**. This is a nice feature of *template* repositories: you can create new repositories that are not connected to the template. This is in contrast to *forking* a repository, which has the implication of later suggesting that your edits should be merged back into the main branch.

3. Follow the directions to create a new repository. Suppose you call it `NEW-REPO-NAME`. You may want to make it private if you're writing some top secret paper. Once you have created a new repository, click on the green **Code** button and copy the GitHub CLI code. It should look something like
   ```
   gh repo clone fliptanedo/NEW-REPO-NAME
   ```

4. Navigate a terminal window to the folder in which you would like to clone the `NEW-REPO-NAME` GitHub  repository, Paste the above `gh` code and execute it. This assumes that you have the [GitHub CLI](https://cli.github.com) installed.

5. Your new paper and local git repository is all set to go. 

## How to use this (old)

For those, like me, are less competent with `git` and GitHub than we really aught to be.

1. Go to repo's [page]( https://github.com/fliptanedo/paper-template-2022) on GitHub.

2. Click on the green `Code` button just to the top-right of the list of files. 

3. Copy the GitHub Command Line Interface (CLI) code:

   ```
   gh repo clone fliptanedo/paper-template-2022
   ```

4. Locally (on your system) go to the parent directory of where you'd like to start a new LaTeX project and open a Terminal (command prompt) window there. Assuming you have `git` set up, you can simply type in

   ```
   gh repo clone fliptanedo/paper-template-2022
   ```

5. and press enter.

6. This should create a new folder `paper-template-2022`. Go ahead and rename it right away:

   ```
   mv paper-template-2022 new-folder-name
   ```

7. Go ahead and start your new project.


# Samples includes
* `paper.tex` is a standard manuscripty
* `Short.tex` is for a brief note 
* `lecturenotes.tex` is for a long set of lecture notes