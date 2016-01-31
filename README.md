# ipython-tikzmagic

*forked from mkrphys/ipython-tikzmagic repo, I am adding features on top of the already working code*

keywords: ipython, jupyter, tikz, graphs, captions,

IPython magics for generating figures with TikZ. You can select the output format as svg, png or jpg, define the image size, specify a scale factor, load TikZ packages and Tex packages, and save to external files. The accompanying IPython notebooks shows some examples demonstrating how to use these features.

## dependencies
The package requires a working LaTeX installation, ImageMagick and pdf2svg.


## installation: 
Place the `tikzmagic.py` file in your `~/.ipython/extensions/` directory. Then within any notebook you can load the extension with `%load_ext tikzmagic`. 

## Usage

The magic function `%%tikz` can take arguments

* -sc : scale
* -s : size in pixels
* -f : format (png, svg, or jpg)
* -l : libraries to include at compile time (e.g. matrix, arrows)
* -p : packages to include (e.g tkz-berge)
* -S : flag that saves output to "filename.format"
* -c : Add comment to the figure, `-c "This is a circle."





