## Amy Gill's pagedown rendered CV

This repo contains the source-code and results of my CV built with the [pagedown package](https://pagedown.rbind.io) and a modified version of the 'resume' template. 

The main files are:

- `gill_index.Rmd`: Source template for the cv, contains a variable `PDF_EXPORT` in the header that changes styles for pdf vs html. 
- `gill_index.html`: The final output of the template when the header variable `PDF_EXPORT` is set to `FALSE`.
- `positions.csv`: A csv with columns encoding the various fields needed for a position entry in the CV. A column `section` is also available so different sections know which rows to use.
- `css/`: Directory containing the custom CSS files used to tweak the default 'resume' format from pagedown. (From `nstrayer/cv`.)
-`parsing_functions.R`: Functions used to parse and properly format position data. (From `nstrayer/cv`.)
- `strayer_template/`: Original CV and resume documents forked from `nstrayer/cv`.

## Acknowledgments

Special thanks to [Nick Strayer](http://nickstrayer.me) for providing his [pagedown CV template on GitHub](https://github.com/nstrayer/cv) and adding customization instructions.
