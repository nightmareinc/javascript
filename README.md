# JavaScript Practices

JavaScript practice repository.

Don't forget to contribute!

## Table of Content

[*brief list of contents*](./Brief.md)

[*verbose list of contents*](./List.md)

## Resources

Practices are written by inspiration of the following JavaScript references:  

1. [You Don't Know JS][1]

## Representation

Practice pages are generated automatically in **markdown** syntax by *update.sh* bash script file.  

## Contribute

Feel free to add or update any of the practice files.  
You should consider a few things before contribution:

* we have 3 directory levels here, **section/chapter/practices** , you can find practice files in third level.
* practice pages are *.md* files auto-generated by shell-script, containing the contents of *.js*, *.title.txt* and *.comment.txt* files. so, to change practice pages, you should not modify *.md* files as they won't take effect.
* in each directory, there's a **.list** hidden file, containing section directory names, chapter directory names and practice file names in order. to move a section, chapter or practice up or down, just modify the corresponding **.list** file containing that section, chapter of practice names.
* *update.sh* script will set file numbers automatically, based on orders in *.list* files, so don't bother numbering! by moving a section, chapter or practice in **.list** files, their numberings and paginations will be modified automatically after you run **update.sh** script.
* each practice should clearly explain only 1 topic
* each practice should be as minimal as possible
* practices should contain a *clean code*!
* write your comments in *filename.comment.txt* files, this goes below the code section in markdown file
* title your code in *filename.title.txt* files, this goes to markdown file header
* do not touch auto generated *md5sum.txt*, *output.txt* and *.md* files

## License

This work is licensed under a Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License.

[1]: https://github.com/getify/You-Dont-Know-JS
