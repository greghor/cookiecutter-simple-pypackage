# Installation


## Stable release

To install {{ cookiecutter.project_name }}, run this command in your terminal:

```batch

    $ pip install {{ cookiecutter.project_slug }}
```

This is the preferred method to install {{ cookiecutter.project_name }}, as it will always
install the most recent stable release.

If you don't have [pip](https://pip.pypa.io) installed, this 
[Python installation guide](http://docs.python-guide.org/en/latest/starting/installation/) 
can guide you through the process.


## From sources

The sources for {{ cookiecutter.project_name }} can be downloaded from the 
[Github repo](https://github.com/{{ cookiecutter.github_username }}/{{ cookiecutter.project_slug }}).

You can either clone the public repository:

```batch

    $ git clone git://github.com/{{ cookiecutter.github_username }}/{{ cookiecutter.project_slug }}
```

Or download the [tarball](https://github.com/{{ cookiecutter.github_username }}/{{ cookiecutter.project_slug }}/tarball/master):

```batch

    $ curl  -OL https://github.com/{{ cookiecutter.github_username }}/{{ cookiecutter.project_slug }}/tarball/master
```

Once you have a copy of the source, you can install it with:

```batch

    $ python setup.py install
```
