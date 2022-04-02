# LaTeX repository template

This is a simple repository template for a LaTeX project.
It contains a GitHub action workflow to compile a LaTeX document into a pdf file using Biber for bibliography, and a `.gitignore` file to ignore the output of transient compiles (and any temporary file).

By default, the compiled pdf file is published into the folder `compiled`. Equally by default, git will ignore a folder called `out` (to allow local compilation in a folder for easier management), but will **not** ignore pdf files in the folders `appendices/external` (to allow externally created pdf to be added to the project) nor in the folder `compiled` (for the obvious reason to not ignore the produced pdf).

It's licensed by the most open licence possible, i.e. _The Unlicense_. Unless you want to release the content of your project under the same licence, it has to be changed before (or in) the first commit containing content, even if the project is meant to be private (you never know if it will stay so forever).


:exclamation::exclamation::exclamation: **Remember to change the licence _before_ (or in) your first commit containing content, even if the project is meant to be private** :exclamation::exclamation::exclamation:
