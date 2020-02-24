# RadioAstronomySoftwareGroup.github.io
The RASG organization github pages site.

## Supported Packages

[pyuvdata](https://github.com/RadioAstronomySoftwareGroup/pyuvdata):
A pythonic interface for radio astronomy interferometry data (uvfits, miriad, others)

[pyuvsim](https://github.com/RadioAstronomySoftwareGroup/pyuvsim):
A comprehensive simulation package for radio interferometers in python.

[pyradiosky](https://github.com/RadioAstronomySoftwareGroup/pyradiosky):
Python objects and interfaces for representing diffuse, extended and compact astrophysical radio sources

[pygitversion](https://github.com/RadioAstronomySoftwareGroup/pygitversion):
Robust git-based versioning for your Python package

## Affiliate Organization
The [RASG-Affiliates](https://github.com/rasg-affiliates) organization supports
development of projects that are their way to meeting the standards of RASG. RASG-Affiliates is a different organization from RASG, and is meant to be a collection of scientific software generally useful to the field of Radio Astronomy. This particular organization encourages good software practices, including using unit tests and comments to provide high-quality software. Below we delineate what the loose requirements are for membership as a RASG-Affiliated repo versus a RASG core repo.

RASG-Affiliated Repos, in general, should have:

- Continuous integration (CI) set up to run tests & report coverage with badges on the README.
- A method for installing the repo using `pip install .` (even if the package is not on PyPI).
- A descriptive README.
- Code documentation, including but not limited to docstrings (we prefer the numpy docstring style, as described [here](https://numpydoc.readthedocs.io/en/latest/format.html)).
- Meet pep8 code format standards (`flake8` or `pycodestyle` can be used to enforce this).
- Permissive open source license (e.g., BSD or MIT, _NOT_ a copyleft license such as the GPL). For some reading on the concerns around copyleft licenses see [this](https://www.technologyreview.com/s/405089/copyleft-hits-a-snag/), [this](http://sennoma.net/?p=622) and [this](https://opencontent.org/blog/archives/4818).
- Signoff from the RASG managers. We will consider all of the above requirements and a plan for long-term support as criteria for support.


In contrast, RASG core repos represent a higher bar for support. In particular, the core RASG developers have agreed to maintain these repos and ensure a higher level of code quality and community engagement. Additional requirements for consideration as a RASG core repo are:

- Partnership with multiple RASG core developers and/or managers who commit to developing and maintaining the repo over the long term.
- Deep community support and development. It is often easiest to achieve this by developing code as a community from the beginning, but it can be met with revision based on deep community input.
- Better than 95% code coverage.
- A Code of Conduct and a Contributing guide.
- Meet all the above criteria for RASG-affiliates.

### RASG-Affiliated Repos

[healvis](https://github.com/rasg-affiliates/healvis):
Visibility simulation of the sky on HEALPix maps.

[simpleDS](https://github.com/rasg-affiliates/simpleDS):
Simple delay-space power spectrum estimator using proper cosmological normalization.

## Documents
Contributors to the RASG Organization documents on these pages are subject to the Code of Conduct and Contributing Guide below. We encourage RASG-Affiliated repos to adopt their own Codes of Conduct and Contributing Guides. These documents in the pyuvdata repo ([pyuvdata Code of Conduct](https://github.com/RadioAstronomySoftwareGroup/pyuvdata/blob/master/CODE_OF_CONDUCT.md) and [pyuvdata Contributing Guide](https://github.com/RadioAstronomySoftwareGroup/pyuvdata/blob/master/.github/CONTRIBUTING.md)) are good examples.

[RASG Code of Conduct](CODE_OF_CONDUCT.md)

[RASG Contributing Guide](CONTRIBUTING.md)

[License](LICENSE.md)
