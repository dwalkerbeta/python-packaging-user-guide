News
====

.. towncrier release notes start

August 2018
-----------

Page Updates
~~~~~~~~~~~~

- Update news page from December 2017 to July 2018. (:pr:`537`)
- Update Python version supported by virtualenv. (:pr:`538`)
- Clarify that the overview also covers non-Python packaging options. (:pr:`542`)
- Fix tutorials/packaging-project's setup.py example to specify classifiers as a list. (:pr:`544`)


New Pages
~~~~~~~~~

- Add outline / rough draft of new Overview page. (:pr:`519`)


Removals
~~~~~~~~

- Remove the recommendation to store passwords in clear text. (:pr:`546`)


July 2018
---------

Page Updates
~~~~~~~~~~~~

- Added scikit-build to key projects. (:pr:`530`)
- Improved binary extension docs. (:pr:`531`)


June 2018
---------

Page Updates
~~~~~~~~~~~~

- Updated Markdown descriptions explanation. (:pr:`522`)
- Fixed categories of interop PEP for pypa.io. (:pr:`527`)


May 2018
--------

Page Updates
~~~~~~~~~~~~

- Added documentation types to contributing guide. (:pr:`485`)
- Added specification-style document to contributing section. (:pr:`489`)
- Updated the license section description for completeness. (:pr:`492`)
- Updated Windows users instructions for clarity. (:pr:`493`)
- Simplified packaging tutorial. (:pr:`498`)
- Noted issues with Provides-Dist and Obsoletes-Dist. (:pr:`513`)


Removals
~~~~~~~~

- Removed outdated warning about Python version mixing with Pipenv. (:pr:`501`)


April 2018
----------

Page Updates
~~~~~~~~~~~~

- Added a guide for phasing out Python versions. (:pr:`459`)
- Made default Description-Content-Type variant GFM. (:pr:`462`)
- Added 'What’s in which Python 3.4–3.6?'. (:pr:`468`)
- Added instructions for Warehouse. (:pr:`471`)
- Updated instructions and status for PyPI launch. (:pr:`475`)


New Pages
~~~~~~~~~

- Added README guide. (:pr:`461`)


Removals
~~~~~~~~

- Removed GPG references from publishing tutorial. (:pr:`466`)


March 2018
----------

Page Updates
~~~~~~~~~~~~

- Updated Core Metadata spec to follw PEP 556. (:pr:`412`)
- Updated "installing scientific packages". (:pr:`455`)
- Clarified a long description classifier on pypi.org. (:pr:`456`)
- Added `long_description_content_type` to follow PEP 556. (:pr:`457`)


February 2018
-------------

Page Updates
~~~~~~~~~~~~

- Added explanation of "legacy" in test.pypi.org/legacy. (:pr:`426`)
- Added example of multiple emails to Core Metadata. (:pr:`429`)
- Added a warning about managing multiple versions with pipenv. (:pr:`430`)
- Updated PyPI migration info. (:pr:`439`)
- Added python3-venv and python3-pip to Debian installation instructions. (:pr:`445`)


January 2018
------------

Page Updates
~~~~~~~~~~~~

- Updated README.rst explanation. (:pr:`419`)
- Added a link to PyPI's list of classifiers. (:pr:`425`)


December 2017
-------------

Page Updates
~~~~~~~~~~~~

- Updated Requires-Python section. (:pr:`414`)
- Noted which fields can be used with environment markers. (:pr:`416`)
- Replaced `~` with `$HOME` in guides and tutorials. (:pr:`418`)


New Pages
~~~~~~~~~

- Added news page. (:pr:`404`)

November 2017
-------------

Page Updates
~~~~~~~~~~~~

- Simplified the wording for the :file:`manifest.in` section. (:pr:`395`)
- Added documentation about the ``py_modules`` argument to ``setup``. (:pr:`398`)
- Updated the *Single Sourcing Package Version* tutorial to reflect pip's current strategy. (:pr:`400`)
- Introduced a new dependency management tutorial based on Pipenv. (:pr:`402`)


October 2017
------------

Page Updates
~~~~~~~~~~~~

- Split the specifications page into multiple pages. (:pr:`386`)
- Added a specification for the :file:`entry_points.txt` file. (:pr:`398`)


New Pages
~~~~~~~~~

- Created a new guide for managing packages using ``pip`` and ``virtualenv``. (:pr:`385`)


September 2017
--------------

Page Updates
~~~~~~~~~~~~

- Recommended using the `--user-base` option. (:pr:`374`)
- Encouraged using ``readme_renderer`` to validate :file:`README.rst`. (:pr:`379`)


August 2017
-----------

Page Updates
~~~~~~~~~~~~

- Added :file:`pypi.org` as a term. (:pr:`365`)
- Added a new, experimental tutorial on installing packages using ``Pipenv``. (:pr:`369`)


New Pages
~~~~~~~~~

- Added a new guide on how to use ``TestPyPI``. (:pr:`366`)


July 2017
---------

Page Updates
~~~~~~~~~~~~

- Added a note about the removal of the explicit registration API. (:pr:`347`)
- Made the new ``TestPyPI`` URL more visible, adding note to homepage about pypi.org. (:pr:`354`)
- Updated this guide's ``readme`` with instructions on how to build the guide locally. (:pr:`356`)
- Added ``enscons`` to the list of key projects. (:pr:`357`)
- Added ``flit`` to the key projects list. (:pr:`358`)


June 2017
---------

Page Updates
~~~~~~~~~~~~

- Switched to the PyPA theme. (:pr:`305`)
- Re-organized the documentation into the new structure. (:pr:`318`)
- Updated to Sphinx 1.6.2. (:pr:`323`)
- Adjusted the landing page. (:pr:`327`)
- Expanded the section on the ``name`` argument. (:pr:`329`)
- Added a license section to the distributing guide. (:pr:`331`)
- Added a note that :file:`manifest.in` does not affect wheels. (:pr:`332`)
- Added a note about PyPI migration in the *Tool Recommendations* tutorial. (:pr:`335`)
- Added documentation for ``python_requires``. (:pr:`338`)
- Added a document on migrating uploads to :file:`PyPI.org`. (:pr:`339`)


May 2017
--------

Page Updates
~~~~~~~~~~~~

- Documented ``pip`` and ``easy_install``'s differences for per-project indexes. (:pr:`233`)
- Added documentation for the ``Description-Content-Type`` field. (:pr:`258`)


New Pages
~~~~~~~~~

- Added contributor and style guide. (:pr:`307`)


April 2017
----------

Page Updates
~~~~~~~~~~~~

- Updated development mode documentation to mention that order of local packages matters. (:pr:`208`)
- Added documentation explaining prominently how to install ``pip`` in ``/usr/local``. (:pr:`230`)
- Convert readthedocs link for their ``.org`` -> ``.io`` migration for hosted projects. (:pr:`239`)
- Swapped order of :file:`setup.py` arguments for the upload command, as order is significant. (:pr:`260`)
- Removed the ``twine register`` reference in the *Distributing Packages* tutorial. (:pr:`271`)
- Explained how to install from unsupported sources using a helper application. (:pr:`289`)
- Added a topic on plugin discovery. (:pr:`296`)
- Added a topic on namespace packages. (:pr:`290`)
- Mentioned the requirement of the ``wheel`` package for creating wheels. (:pr:`299`)


User Guide Development Updates
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

- Added travis configuration for testing pull requests. (:pr:`300`)


March 2017
----------

Page Updates
~~~~~~~~~~~~

- Covered ``manylinux1`` in *Platform Wheels*. (:pr:`283`)


February 2017
-------------

Page Updates
~~~~~~~~~~~~

- Added :pep:`518`. (:pr:`281`)
