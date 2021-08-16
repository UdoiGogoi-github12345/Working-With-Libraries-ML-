# NumPy tutorials

_For the rendered tutorials, see https://numpy.org/numpy-tutorials/._

The goal of this repository is to provide high-quality resources by the
NumPy project, both for self-learning and for teaching classes with. If you're
interested in adding your own content, check the [Contributing](#contributing)
section. This set of tutorials and educational materials is not a part of the
NumPy source tree.

To download a local copy of the `.ipynb` files, you can either
[clone this repository](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository)
or navigate to any of the documents listed below and download it individually.

## Content

0. [Learn to write a NumPy tutorial](content/tutorial-style-guide.md): our style guide for writing tutorials.
1. [Tutorial: Linear algebra on n-dimensional arrays](content/tutorial-svd.md)
2. [Tutorial: Determining Moore's Law with real data in NumPy](content/mooreslaw-tutorial.md)
3. [Tutorial: Saving and sharing your NumPy arrays](content/save-load-arrays.md)
4. [Tutorial: NumPy deep learning on MNIST from scratch](content/tutorial-deep-learning-on-mnist.md)
5. [Tutorial: X-ray image processing](content/tutorial-x-ray-image-processing.md)
6. [Tutorial: NumPy deep reinforcement learning with Pong from pixels](content/tutorial-deep-reinforcement-learning-with-pong-from-pixels.md)
7. [Tutorial: Masked Arrays](content/tutorial-ma.md)
8. [Tutorial: Static Equilibrium](content/tutorial-static_equilibrium.md)
9. [Tutorial: Plotting Fractals](content/tutorial-plotting-fractals.ipynb)


## Contributing

We very much welcome contributions! If you have an idea or proposal for a new
tutorial, please [open an issue](https://github.com/numpy/numpy-tutorials/issues)
with an outline.

Don’t worry if English is not your first language, or if you can only come up
with a rough draft. Open source is a community effort. Do your best – we’ll help
fix issues.

Images and real-life data make text more engaging and powerful, but be sure what
you use is appropriately licensed and available. Here again, even a rough idea
for artwork can be polished by others.

The NumPy tutorials are a curated collection of
[MyST-NB](https://myst-nb.readthedocs.io/) notebooks. These notebooks are used
to produce static websites and can be opened as notebooks in Jupyter using
[Jupytext](https://jupytext.readthedocs.io).

> __Note:__ You should use [CommonMark](https://commonmark.org) markdown
> cells. Jupyter only renders CommonMark.

### Why Jupyter Notebooks?

The choice of Jupyter Notebook in this repo instead of the usual format
([reStructuredText, through Sphinx](https://www.sphinx-doc.org/en/master/usage/restructuredtext/index.html))
used in the main NumPy documentation has two reasons:

 * Jupyter notebooks are a common format for communicating scientific
   information.
 * Jupyter notebooks can be launched in [Binder](https://www.mybinder.org), so that users can interact
   with tutorials
 * rST may present a barrier for some people who might otherwise be very
   interested in contributing tutorial material.

#### Note

You may notice our content is in markdown format (`.md` files). We review and
host notebooks in the [MyST-NB](https://myst-nb.readthedocs.io/) format. We
accept both Jupyter notebooks (`.ipynb`) and MyST-NB notebooks (`.md`). If you want
to sync your `.ipynb` to your `.md` file follow the [pairing
tutorial](content/pairing.md).

### Adding your own tutorials

If you have your own tutorial in the form of a Jupyter notebook (a `.ipynb`
file) and you'd like to add it to the repository, follow the steps below.


#### Create an issue

Go to [https://github.com/UdoiGogoi-github12345/NumPy](https://github.com/UdoiGogoi-github12345/NumPy)
and create a new issue with your proposal. Give as much detail as you can about
what kind of content you would like to write (tutorial, how-to) and what you
plan to cover. We will try to respond as quickly as possible with comments, if
applicable.

#### Check out our suggested template

You can use our [Tutorial Style Guide](content/tutorial-style-guide.md) to make
your content consistent with our existing tutorials.


## Useful links and resources

The following links may be useful:

- [NumPy Code of Conduct](https://numpy.org/doc/stable/dev/conduct/code_of_conduct.html)
- [Main NumPy documentation](https://numpy.org/doc/stable/)
- [NumPy documentation team meeting notes](https://hackmd.io/oB_boakvRqKR-_2jRV-Qjg?both)
- [NEP 44 - Restructuring the NumPy documentation](https://numpy.org/neps/nep-0044-restructuring-numpy-docs.html)
- [Blog post - Documentation as a way to build Community](https://labs.quansight.org/blog/2020/03/documentation-as-a-way-to-build-community/)

Note that regular documentation issues for NumPy can be found in the [main NumPy
repository](https://github.com/numpy/numpy/issues) (see the `Documentation`
labels there).
