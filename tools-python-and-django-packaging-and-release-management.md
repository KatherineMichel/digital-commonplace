# Python and Django Packaging and Release Management

<!--
Packaging
https://twitter.com/webKnjaZ/status/1287690737778335744 | Sviatoslove.py🐍 👨‍💻🏡:🇨🇿🇪🇺 @Ansible @RedHat on Twitter: "@codewithanthony @codewithanthony FYI there's also `wheel unpack` for extracting whl contents" / Twitter

Pinax release docs
`python setup.py test`
https://github.com/pypa/setuptools/issues/931
https://github.com/pytest-dev/pytest/issues/5534
https://github.com/pypa/setuptools/issues/1684#issuecomment-508156856
https://github.com/pypa/setuptools/issues/1684

https://setuptools.readthedocs.io/en/latest/setuptools.html#configuring-setup-using-setup-cfg-files
https://github.com/pypa/sampleproject/blob/master/setup.cfg


<!--
https://packaging.python.org/tutorials/packaging-projects/?highlight=entry_points#entry-points | Packaging Python Projects — Python Packaging User Guide

Installation Advice

--user flag
https://twitter.com/messages/17009144-101186457
https://pip.pypa.io/en/stable/user_guide/#user-installs

pip install -e
https://twitter.com/pganssle/status/1289038733250113537
https://twitter.com/pganssle/status/1289010601415577600 | Paul Ganssle on Twitter: ""Doctor, it hurts when I invoke https://t.co/o3PGyRiVuO install." "Stop doing that then!" (Seriously, always use pip install, never https://t.co/o3PGyRiVuO install)" / Twitter

Pinning
https://twitter.com/carltongibson/status/1249033282831908870 | Carlton Gibson 🇪🇺 on Twitter: "@webology How do they not get unexpected breakages then?" / Twitter
--
-->

<!--
https://stackoverflow.com/questions/5280906/difference-between-binary-release-and-source-release | Difference between Binary release and source release? - Stack Overflow

Virtualenv
https://twitter.com/IanLee1521/status/1260437446728331268

pip Study
https://twitter.com/bernardtyers/status/1236039617222230017

Kenneth
https://docs.python-guide.org/shipping/packaging/ | Packaging Your Code — The Hitchhiker's Guide to Python
https://docs.python-guide.org/shipping/freezing/#freezing-your-code-ref | Freezing Your Code — The Hitchhiker's Guide to Python

PyPI Quick Start Guide
https://github.com/pypa/packaging.python.org/issues/688
https://twitter.com/mariatta/status/1218232806163107841
https://twitter.com/brettsky/status/1218293642877534209
https://github.com/pypa/gh-action-pypi-publish/issues/2 | Add a usage guide to packaging.python.org · Issue #2 · pypa/gh-action-pypi-publish

https://twitter.com/di_codes/status/1253166894158417926 | Dustin Ingram on Twitter: "Today we merged support on @pypi for PEP 592, adding the ability to "yank" releases, and for installers to determine which releases have been "yanked"! Nice! ...but, uh, what is a "yanked" release, you might ask? (1\11)" / Twitter

Scam
urllib3
https://twitter.com/snyksec/status/1236755073499357185
https://twitter.com/webology/status/1202238650416807936 | ❄☃ Jeff Triplett 🎄 on Twitter: "🚨 PSA: Python friends, please doublecheck if you accidentally have "python3-dateutil" (THREE) and/or "jeIlyfish" installed. They attempt to steal your GPG and SSH keys. https://t.co/OcfL165pXA" / Twitter


https://twitter.com/brettsky/status/1216051044095946752
https://twitter.com/VictorStinner/status/1216061972543868929
https://github.com/vstinner/pyperf/blob/master/setup.py

Requirements pinning
https://twitter.com/webology/status/1238674042338652161
-->

## Mission Critical :)

pip
* [pip](https://github.com/pypa/pip/)

New pip resolver; PyPA: "Starting this year, pip will be more consistent + stricter in the dependencies it installs"
* ["New pip resolver to roll out this year"](http://pyfound.blogspot.com/2020/03/new-pip-resolver-to-roll-out-this-year.html)

venv and Virtualenv
* [venv](https://docs.python.org/3/library/venv.html)
* [Virtualenv GitHub](https://github.com/pypa/virtualenv/) and [Virtualenv](https://virtualenv.pypa.io/en/latest/)
* [Bernat Gabor: "virtualenv 20.0.0 is now released, a first major release of a new better implementation for the future"](https://twitter.com/gjbernat/status/1226803593535279104)
* [Virtualenv 20.0.0 Change Log](https://virtualenv.pypa.io/en/latest/changelog.html#v20-0-0-2020-02-10)

venv versus virtualenv
* [Hynek: Virtualenv is "fast af"](https://twitter.com/hynek/status/1241381814440247299)
* ["Switch from Virtualenv to Python’s built-in `venv` module"](https://github.com/justinmayer/virtualfish/issues/158)

Pipenv
* [Pipenv Release v2020.5.28](https://github.com/pypa/pipenv/releases/tag/v2020.5.28 )
* [Next Pipenv Release - Google Groups](https://groups.google.com/forum/#!topic/pypa-dev/qLO8Pd4i_Co)

<!--
Bernat
https://ep2020.europython.eu/talks/D2SG8Vb-lessons-from-the-trenches-rewriting-and-re-releasing-virtualenv/ | Lessons from the Trenches: rewriting and re-releasing virtualenv — EuroPython 2020 Online · 23-26 July 2020
https://www.youtube.com/watch?v=l9A0a8qZgOs | (1) Bernat Gabor - Lessons from the Trenches: rewriting and re-releasing virtualenv - YouTube
https://www.youtube.com/watch?v=RVK7rsFEfpc&feature=youtu.be&t=15630
https://github.com/gaborbernat/virtualenv-rewrite-eupy20 | gaborbernat/virtualenv-rewrite-eupy20

https://modelpredict.com/python-dependency-management-tools | Overview of python dependency management tools | model.predict

https://hynek.me/articles/python-app-deps-2018/

pip/virtualenv
export PIP_REQUIRE_VIRTUALENV=true
https://github.com/pypa/pip/commit/301dc3176fa40c3f6a233fccc131f3981bfbe48b

https://twitter.com/codewithanthony/status/1310641296629874689 | Anthony Sottile on Twitter: "@jugmac00 @driscollis pip: generally shouldn't use pip to install system packages, use the system package manager venv: needs pip / ensurepip tk: pulls in a ton of deps and most people don't need it gdbm: used to be for licensing reasons distutils + lib2to3: idk, but they're going away soon" / Twitter

pipenv, pipx
https://github.com/pipxproject/pipx
https://twitter.com/ken_reitz/status/1296276149014847488 | Ken Reitz on Twitter: "@llanga how?" / Twitter

poetry
https://twitter.com/llanga/status/986645110518509568 | Łukasz Langa on Twitter: "TIL about https://t.co/BtoFQvaMlW. Compared to Pipenv, the cmdline is different, it uses the standard pyproject.toml for configuration instead of the custom Pipfile, and caret dependencies are a usability improvement. It will be very interesting to see which will win long term."


https://pyfound.blogspot.com/2020/11/pip-20-3-new-resolver.html | Python Software Foundation News: Releasing pip 20.3, featuring new dependency resolver
https://twitter.com/ThePyPA/status/1303384992165302272 | PyPA on Twitter: "https://t.co/gXi5fQtmQU pip 20.2.3 is out. Includes a beta of the new dependency resolver (hidden behind an optional --use-feature=2020-resolver flag). We encourage you to test it before next month, when pip 20.3'll default to the new behavior. https://t.co/aKqVdEcphJ #Python https://t.co/cWy1DRYkkx" / Twitter

https://pip.pypa.io/en/latest/user_guide/#changes-to-the-pip-dependency-resolver-in-20-2-2020
https://www.youtube.com/watch?time_continue=31&v=B4GQCBBsuNU&feature=emb_logo | Changes are coming to pip - YouTube
https://twitter.com/ThePSF/status/1311038036013199363 | Python Software Foundation on Twitter: "Changes are coming to pip, #Python's package installation tool, in October 2020. https://t.co/7U5nJFADDL Migration guide: https://t.co/WGwwL7Hp5D Sign up for user experience studies: https://t.co/cCRyK15lOs" / Twitter

pip
https://blog.python.org/2020/07/upgrade-pip-20-2-changes-20-3.html | Python Insider: Upgrade to pip 20.2, plus, changes coming in 20.3
https://twitter.com/ChangesetLLC/status/1291062082574704649 | Changeset Consulting on Twitter: "There is a big change coming to pip in October -- a watershed moment, a minor revolution. It'll be a great foundation for making it easier to deal with #Python packaging. This is a thread where I'll share some of the stuff @ThePyPA can build on that foundation. https://t.co/JGqVy21Dnp" / Twitter

beta pip
https://mobile.twitter.com/ThePyPA/status/1252641910679879681

pip Resolver
https://mobile.twitter.com/metalikus/status/1251497611028238336

New pip resolver
https://pyfound.blogspot.com/2019/12/moss-czi-support-pip.html
https://wiki.python.org/psf/Fundable%20Packaging%20Improvements#Finish_dependency_resolver_for_pip
https://wiki.python.org/psf/Pip2020DonorFundedRoadmap

https://github.com/pypa/pip/projects/5
https://github.com/pypa/pip/issues/988
https://gist.github.com/pradyunsg/5cf4a35b81f08b6432f280aba6f511eb
https://pradyunsg.me/blog/2019/06/23/oss-update-1/
https://twitter.com/nlhkabu/status/1263132447971172352 | Nicole Harris on Twitter: " Python people! The pip team needs your help! Do you have complex project dependencies? We want you to try to break pip's new dependency resolver... Details here: https://t.co/E1eRK7KjYl Please RT! cc @bernardtyers @simplysecureorg @ThePyPA @ThePSF" / Twitter
-->

## Environment

<!--
https://en.wikipedia.org/wiki/Env | env - Wikipedia

direnv
https://twitter.com/webology/status/1249711305851916290 | Jeff says, "wash your hands" 🧼👏 on Twitter: "@carltongibson Please use https://t.co/r85QZqhspb It will save you from having project env variables leak into another too. Five stars. Use it for a day or two and you'll thank me later." / Twitter
https://twitter.com/webology/status/1249711521070014464 | Jeff says, "wash your hands" 🧼👏 on Twitter: "PSA: Use direnv. Just use it. It'll save you frustrating and accidentally env leakage. https://t.co/r85QZqhspb https://t.co/1YzNPaNlmg" / Twitter

Django
https://twitter.com/bmispelon/status/1266337389406048260 | Baptiste Mispelon on Twitter: "What are the cool Django kids using these days to pull their settings from environment variables? A quick search is already giving me way too many options: python-dotenv django-dotenv environs django-environ envparse python-decouple ..." / Twitter
environs[django] - Google Search

https://github.com/sloria/environs#usage-with-django

https://github.com/cortesi/devd

https://github.com/cans/gitvenv

Kenneth
https://github.com/inishchith/autoenv
-->

## Governance

* [PSF Packaging Working Group](https://wiki.python.org/psf/PackagingWG)
* [PyCon US Packaging Mini-Summit 2019](https://discuss.python.org/t/pycon-us-packaging-mini-summit-2019/833)

<!--
Packaging Summit
https://mail.python.org/archives/list/distutils-sig@python.org/thread/ZEZNY2MCUN3S3JGUFF6U6OWVEOKW2UAF/
https://mobile.twitter.com/pradyunsg/status/1224789432504475649

https://www.python.org/dev/peps/pep-0566/ | PEP 566 -- Metadata for Python Software Packages 2.1 | Python.org
https://www.python.org/dev/peps/pep-0496/ | PEP 496 -- Environment Markers | Python.org
https://www.python.org/dev/peps/pep-0508/#id23 | PEP 508 -- Dependency specification for Python Software Packages | Python.org

https://www.python.org/dev/peps/pep-0427/ | PEP 427 -- The Wheel Binary Package Format 1.0 | Python.org
https://www.python.org/dev/peps/pep-0438/ | PEP 438 -- Transitioning to release-file hosting on PyPI | Python.org
https://www.python.org/dev/peps/pep-0440/ | PEP 440 -- Version Identification and Dependency Specification | Python.org
https://www.python.org/dev/peps/pep-0517/

https://www.python.org/dev/peps/pep-0394/#recommendation
-->

## Packaging- How To

Django
* [Django: How to write reusable apps](https://docs.djangoproject.com/en/3.0/intro/reusable-apps/).

Python Docs- Packaging
* [Distributing Python Modules](https://docs.python.org/3/distributing/index.html)

Python- Official Packaging Info
* [Sample Project](https://github.com/pypa/sampleproject)
* [Python Packaging User Guide](https://packaging.python.org) and [Python Packaging User Guide GitHub](https://github.com/pypa/python-packaging-user-guide) 
* [Python Packaging Tutorials](https://packaging.python.org/tutorials) 
* [Python Packaging Guides](https://packaging.python.org/guides) 
* [Python Packaging Projects Tutorial](https://packaging.python.org/tutorials/packaging-projects)  
* [Python Packaging Key Projects](https://packaging.python.org/key_projects)

<!--
https://packaging.python.org/overview/ | An Overview of Packaging for Python — Python Packaging User Guide
https://packaging.python.org/glossary/ | Glossary — Python Packaging User Guide

https://packaging.python.org/tutorials/distributing-packages/ | Packaging and distributing projects
-->

## Key Projects

<!--
https://pypi.org/project/django-utils/ | django-utils · PyPI
https://docs.python.org/3/library/distutils.html | distutils — Building and installing Python modules — Python 3.8.1 documentation


https://docs.python.org/3/tutorial/modules.html#packages | 6. Modules — Python 3.7.3rc1 documentation

https://docs.python.org/3/distutils/introduction.html | 1. An Introduction to Distutils — Python 3.6.4rc1 documentation
https://docs.python.org/3.1/distutils/uploading.html | 7. Uploading Packages to the Package Index — Python v3.1.5 documentation
https://docs.python.org/3.6/distutils/packageindex.html#package-index | 6. The Python Package Index (PyPI) — Python 3.6.4rc1 documentation
https://docs.python.org/3/distutils/sourcedist.html | 4. Creating a Source Distribution — Python 3.6.4rc1 documentation

https://docs.python.org/3/distutils/configfile.html | 3. Writing the Setup Configuration File — Python 3.8.1rc1 documentation
https://docs.python.org/3/install/index.html#inst-config-syntax | Installing Python Modules (Legacy version) — Python 3.8.1rc1 documentation

https://packaging.python.org/tutorials/distributing-packages/#project-urls
-->

<!--
setup.py
https://docs.python.org/3/distutils/setupscript.html | 2. Writing the Setup Script — Python 3.8.1 documentation

https://pypi.org/classifiers/ | Classifiers · PyPI
https://packaging.python.org/tutorials/packaging-projects/#classifiers | Packaging Python Projects — Python Packaging User Guide
https://www.python.org/dev/peps/pep-0301/#distutils-trove-classification | PEP 301 -- Package Index and Metadata for Distutils | Python.org

Setuptools
https://en.wikipedia.org/wiki/Setuptools
https://pypi.org/project/setuptools/
https://github.com/pypa/setuptools
https://setuptools.readthedocs.io/en/latest/setuptools.html | Building and Distributing Packages with Setuptools — setuptools 45.2.0 documentation

https://packaging.python.org/guides/distributing-packages-using-setuptools/ | Packaging and distributing projects — Python Packaging User Guide

https://packaging.python.org/key_projects/#setuptools | Project Summaries — Python Packaging User Guide
https://packaging.python.org/key_projects/#distutils

https://packaging.python.org/key_projects/#wheel | Project Summaries — Python Packaging User Guide
https://packaging.python.org/guides/distributing-packages-using-setuptools/#wheels
https://packaging.python.org/guides/distributing-packages-using-setuptools/#universal-wheels
-->

## Packaging- Installing Packages

<!--
https://packaging.python.org/tutorials/installing-packages/

https://packaging.python.org/glossary/#term-version-specifier

https://pip.pypa.io/en/latest/reference/pip_install/#pip-install
https://pip.pypa.io/en/latest/user_guide/#requirements-files
https://setuptools.readthedocs.io/en/latest/pkg_resources.html#requirement-objects

https://packaging.python.org/glossary/#term-requirement-specifier
https://www.python.org/dev/peps/pep-0440/
https://www.python.org/dev/peps/pep-0440/#version-specifiers

https://pypi.org/classifiers/ | Classifiers · PyPI
https://packaging.python.org/specifications/core-metadata/#description-content-type-optional | Core metadata specifications — Python Packaging User Guide
-->

## Packaging- Wheel versus Egg

Python- Wheel (versus Egg!)
* [Python Packaging Wheel vs. Egg](http://python-packaging-user-guide.readthedocs.io/discussions/wheel-vs-egg)
* [Wheel PyPI](https://pypi.org/project/wheel) and [Wheel Read the Docs](http://wheel.readthedocs.org)
* [Python Wheels](http://pythonwheels.com)

<!--
Wheels
https://github.com/pypa/wheel
https://packaging.python.org/guides/distributing-packages-using-setuptools/#wheels | Packaging and distributing projects — Python Packaging User Guide
https://packaging.python.org/tutorials/packaging-projects/#wheels | Packaging Python Projects — Python Packaging User Guide
https://pip.pypa.io/en/stable/reference/pip_wheel
-->

## Packaging- Hosting

Python- Packages/Libraries
* [Warehouse](https://pypi.org), [Warehouse GitHub](https://github.com/pypa/warehouse), and [Warehouse Read the Docs](https://warehouse.readthedocs.io)
 
TestPyPI
* [TestPyPI](https://test.pypi.org)
* [Using TestPyPI](https://packaging.python.org/guides/using-testpypi)

## Packaging- Tools

Package Helpers
* [Twine GitHub](https://github.com/pypa/twine) and [Twine PyPi](https://pypi.python.org/pypi/twine)
* [check-manifest GitHub](https://github.com/mgedmin/check-manifest)

Core Packaging Utilities
* [PyPa Core Packaging Utilities](https://github.com/pypa/packaging)  
* [PyPa Core Packaging Utilities Documents](https://packaging.pypa.io) 

<!--
Checks
https://github.com/jwodder/check-wheel-contents | jwodder/check-wheel-contents: Check your wheels have the right contents
-->

## requirements.txt, pipfile, pyproject.toml, setup.py, setup,cfg

<!--
TOML
https://en.wikipedia.org/wiki/TOML | TOML - Wikipedia
https://github.com/toml-lang/toml
https://mobile.twitter.com/brettsky/status/1246233334482489344 | Brett Cannon on Twitter: "🎉 Once TOML reaches 1.0 I will start a conversation about getting a parser into the stdlib https://t.co/B4mxWO47BU" / Twitter

pyproject.toml
https://www.python.org/dev/peps/pep-0518/ | PEP 518 -- Specifying Minimum Build System Requirements for Python Projects | Python.org
https://snarky.ca/clarifying-pep-518/ | Clarifying PEP 518 (a.k.a. pyproject.toml)
https://snarky.ca/what-the-heck-is-pyproject-toml/ | What the heck is pyproject.toml?

https://github.com/carlosperate/awesome-pyproject | carlosperate/awesome-pyproject: An Awesome List of projects using the pyproject.toml Python configuration file.
https://gitlab.com/pycqa/flake8/issues/428#note_154743215 | pyproject.toml (PEP 518) support (#428) · Issues · PyCQA / flake8 · GitLab
https://news.ycombinator.com/item?id=17110882 | pyproject.toml isn't another way to specify dependencies for Python code. The l... | Hacker News
https://github.com/psf/black/blob/master/pyproject.toml | black/pyproject.toml at master · psf/black

pyproject.toml : the future of Python packaging
https://testandcode.com/52

PEP 517 and 518 in Plain English
https://medium.com/@grassfedcode/pep-517-and-518-in-plain-english-47208ca8b7a6
https://www.python.org/dev/peps/pep-0517/
https://www.python.org/dev/peps/pep-0518/

Options
The difference between setup.py (pyproject.toml) and requirements.txt (Pipfile) #27
https://github.com/pypa/pipfile/issues/27
https://packaging.python.org/discussions/install-requires-vs-requirements/ | install_requires vs requirements files — Python Packaging User Guide
https://pip.pypa.io/en/stable/user_guide/#requirements-files
https://docs.pipenv.org/advanced/#pipfile-vs-setup-py
https://github.com/pypa/pipfile
https://github.com/pypa/pipfile#the-concept
-->

## Virtualenv, Python and Django Dependency Management

pipenv
* [pipenv as The PyPA recommended tool for installing Python packages](https://packaging.python.org/guides/tool-recommendations/) and [Python Packaging User Guide: Managing Application Dependencies](https://packaging.python.org/tutorials/managing-dependencies/#managing-dependencies)

Others
* [Poetry Docs](https://python-poetry.org/docs/) and [Poetry GitHub](https://github.com/python-poetry)
* [Flit](https://flit.readthedocs.io/en/latest/)
* [pipx](https://pipxproject.github.io/pipx/)
* [Dephell GitHub](https://github.com/dephell/dephell)

<!--
https://packaging.python.org/tutorials/installing-packages/#creating-and-using-virtual-environments

venv, virtualenv and pyenv
https://docs.python-guide.org/dev/virtualenvs/ | Pipenv & Virtual Environments — The Hitchhiker's Guide to Python

https://github.com/pyenv/pyenv-virtualenv | pyenv/pyenv-virtualenv: a pyenv plugin to manage virtualenv (a.k.a. python-virtualenv)
https://github.com/pyenv/pyenv-update

pyenv
https://twitter.com/webology/status/1206676626311917568 | ❄☃ Jeff Triplett 🎄🔔 on Twitter: "Same. If you run macOS and develop with Python, pyenv is the way to go IMO. https://t.co/9sy5GBtGIw" / Twitter
https://twitter.com/webology/status/1199446555809460231 | 🍂 Jeff Triplett 🍂 on Twitter: "🐍 This is a great resource. 🐳 I'd love to see a 4th Docker version. 🎉 If you use macOS, I highly, highly recommend using pyenv to manage your Python version of you. It's on my "just use it" list when I work with any level of dev. https://t.co/R6uPyFbJDr" / Twitter
https://www.marc-richter.info/using-pyenv-to-manage-your-python-interpreters/ | Using pyenv to manage your Python interpreters - Marc Richter's personal site

https://packaging.python.org/tutorials/managing-dependencies/ | Managing Application Dependencies — Python Packaging User Guide

pip grant
https://mobile.twitter.com/di_codes/status/1193980331004743680

pip
https://pip.pypa.io/en/stable/reference/pip_install/ | pip install — pip 19.3.1 documentation
https://pip.pypa.io/en/stable/reference/pip_install/#editable-installs | pip install — pip 18.1 documentation
https://pip.readthedocs.io/en/latest/user_guide/#user-installs | User Guide — pip 19.1.dev0 documentation
https://pypi.org/project/pip/ | pip · PyPI

Pip problem
https://github.com/pypa/pip/issues/7531#issuecomment-576686251 | Release 20.0 · Issue #7531 · pypa/pip

https://github.com/jazzband/pip-tools | jazzband/pip-tools: A set of tools to keep your pinned Python dependencies fresh.

https://github.com/pypa/pipenv/issues/4058 | If this project is dead, just tell us · Issue #4058 · pypa/pipenv
https://twitter.com/ordanisanchez/status/1242953101969104896

https://www.youtube.com/watch?v=GBQAKldqgZs | Kenneth Reitz - Pipenv: The Future of Python Dependency Management - PyCon 2018 - YouTube
http://www.kennethreitz.org/essays/a-better-pip-workflow
https://pipenv.readthedocs.io/en/latest/ | Pipenv: Python Dev Workflow for Humans — pipenv 8.3.2 documentation
https://github.com/pypa/pipenv | kennethreitz/pipenv: Python Development Workflow for Humans.

pipenv
https://twitter.com/simonw/status/1211735682135101440 | Simon Willison on Twitter: "@llanga @webology That's the main reason I use pipenv - it keeps my virtual environments outside Dropbox for me" / Twitter

Criticism of Poetry
https://mobile.twitter.com/hynek/status/1226240842429616135

https://python-poetry.org/docs/pyproject/
https://black.readthedocs.io/en/stable/pyproject_toml.html

https://pyup.io/ | Manage your Python dependencies with pyup.io
http://www.pyinstaller.org/ | Welcome to PyInstaller official website — PyInstaller
-->

## Opinions, Talks, Examples

Dustin Ingram
* ["Inside the Cheeseshop: How Python Packaging Works" (PyCon 2018)](https://dustingram.com/talks/2018/10/23/inside-the-cheeseshop)
* ["PyPI is dead. Long live PyPI!"](https://dustingram.com/articles/2018/04/16/pypi-is-dead-long-live-pypi)

<!--
DjangoCon Europe 2017 Vinta
https://www.youtube.com/watch?v=AMg4Iind90Q | (1) "Qualities of great reusable Django apps" by Flávio Juvenal da Silva Junior - YouTube
https://docs.google.com/presentation/d/1yapK1hYt8f64ztLCc7yFpCI4RG1vTMLhqwZ6cUBZIvI/edit#slide=id.p | Qualities of great reusable Django apps - DjangoCon Europe 2017 - Google Slides
https://www.vinta.com.br/blog/2017/djangocon-europe-2017-was-awesome/ | DjangoCon Europe 2017 was awesome! – Vinta Software

Sample project
https://github.com/crwilcox/my-pypi-package | crwilcox/my-pypi-package: A sample package to publish to pypi that uses circleci for CI and nox for test automation
https://github.com/crwilcox/my-pypi-package/blob/master/.circleci/config.yml | my-pypi-package/config.yml at master · crwilcox/my-pypi-package
https://speakerdeck.com/crwilcox/pycon-2019-shipping-your-first-python-package-and-automating-future-publishing?slide=14 | PyCon 2019 - Shipping your first Python package and automating future publishing - Speaker Deck
https://www.youtube.com/watch?v=P3dY3uDmnkU | Chris Wilcox - Shipping your first Python package and automating future publishing - PyCon 2019 - YouTube

https://www.youtube.com/watch?v=AQsZsgJ30AE
https://www.youtube.com/watch?v=EdD6Ifjlle4 | DjangoCon US 2018 - Packaging Django Apps for Distribution on PyPI by Laura Hampton - YouTube
https://www.youtube.com/watch?time_continue=1&v=QgZ7qv4Cd0Y | How To Publish A Package On PyPI - YouTube
-->

<!--
The Packaging Gradient
https://www.youtube.com/watch?v=iLVNWfPWAC8

https://www.bernat.tech/pep-517-and-python-packaging/ | The state of Python Packaging - package types
https://github.com/gaborbernat/pugs | gaborbernat/pugs: random pug quote provider
https://github.com/ipfs/package-managers/issues/56 | Interesting academic papers related to package management · Issue #56 · ipfs/package-managers

Epic Python packaging thread
https://twitter.com/zooba/status/1236440987054063616

https://twitter.com/di_codes/status/1137014821923241986 | Dustin Ingram on Twitter: "Ask anyone about packaging, and they'll tell you the same thing: "it sucks". Now, I don't think it sucks. I think it's challenging, hard to grasp, complicated, has some rough edges, has a lot of historical baggage. I think it was built by people, and people aren't perfect. 5/16"
-->

## Tutorials

Tutorials
* [The Sheer Joy of Packaging! Scipy 2018 Tutorial](https://python-packaging-tutorial.readthedocs.io/en/latest)

Python- Cookiecutter Creating Packages
* [PyPi Release Checklist](https://gist.github.com/audreyr/5990987) and [PyPi Release Checklist 2](https://gist.github.com/audreyr/9f1564ea049c14f682f4)
* [Cookiecutter Django Package GitHub](https://github.com/pydanny/cookiecutter-djangopackage)
* [Cookiecutter PyPackage Read the Docs](https://cookiecutter.readthedocs.org/en/latest)
* [Cookiecutter PyPackage GitHub](https://github.com/audreyr/cookiecutter-pypackage)
* [Cookiecutter via Django Rest Framework: How to create a Third Party Package](http://www.django-rest-framework.org/topics/third-party-resources)

Python- Additional Packaging Tutorials
* [Digital Ocean Tutorial "How to Package and Distribute Python Applications"](https://www.digitalocean.com/community/tutorials/how-to-package-and-distribute-python-applications) 
* [Free Code Camp "How to publish your own Python Package on PyPi"](https://medium.freecodecamp.org/how-to-publish-a-pyton-package-on-pypi-a89e9522ce24)

<!--
https://realpython.com/pypi-publish-python-package/
-->

## PyPI History

PyPI History
* ["Redesigning the Python Package Index"](http://pyfound.blogspot.com/2018/08/redesigning-python-package-index.html)
* ["A new package index for Python"](https://lwn.net/Articles/751458/)
* ["Warehouse: All New PyPI is now in beta"](http://pyfound.blogspot.com/2018/03/warehouse-all-new-pypi-is-now-in-beta.html)


<!--
https://wiki.python.org/moin/CheeseShop | CheeseShop - Python Wiki

https://wiki.python.org/moin/Distutils | Distutils - Python Wiki

Issues
https://github.com/pypa/warehouse/issues
https://github.com/pypa/packaging-problems/issues | Issues · pypa/packaging-problems
https://github.com/pypa/pypi-support

https://github.com/pypa/integration-test | pypa/integration-test: ensure core packaging tools work well with each other
-->

<!--
https://twitter.com/ncoghlan_dev/status/1146177537497714688 | Nick Coghlan on Twitter: "You won't settle that debate easily: https://t.co/62cgLT9f1w :)… "

https://twitter.com/di_codes/status/1135628015147388928 | Dustin Ingram on Twitter: "Ever wondered what is going on when you `pip install numpy` and it downloads some file with a name like `numpy-1.16.4-cp37-cp37m-manylinux1_x86_64.whl `? This is a built distribution, and @brettsky just published a great explanation of what every part of that filename means.… https://t.co/yJAXS13a2J"
https://snarky.ca/the-challenges-in-designing-a-library-for-pep-425/ | The challenges in designing a library for PEP 425 (aka wheel tags)

New- Packaging
https://pydist.com/blog/distributions-vs-releases | PyDist – Blog

https://docs.travis-ci.com/user/deployment/pypi/ | PyPI deployment - Travis CI
-->

<!--
https://twitter.com/pypi_updates2 | PyPI Recent Updates (@pypi_updates2) | Twitter

https://twitter.com/di_codes/status/1097217474603438080 | Dustin Ingram @ PyCaribbean on Twitter: "First you just have to understand all these things... 🤐… "

Tutorials
http://the-hitchhikers-guide-to-packaging.readthedocs.io/en/latest/contributing.html | Contribute Your Package to the World — The Hitchhiker's Guide to Packaging 1.0 documentation

https://pythonhosted.org/setuptools/formats.html
https://pythonhosted.org/an_example_pypi_project/setuptools.html

https://blog.jetbrains.com/pycharm/2017/05/how-to-publish-your-package-on-pypi/ | How to Publish Your Package on PyPI | PyCharm Blog
https://tom-christie.github.io/articles/pypi/ | Uploading to PyPI – Tom Christie

https://github.com/twoscoops/Creating-and-Distributing-Python-Packages | twoscoops/Creating-and-Distributing-Python-Packages
https://courses.twoscoopspress.com/courses/take/creating-and-distributing-python-packages | Two Scoops Press

Seeking a new maintainer for packaging.python.org and Twine.
https://mail.python.org/archives/list/distutils-sig@python.org/thread/M7VRNT5KP4YQ6UPVI4MN4IIWM2Z3IXCH/

PyPI
Improvements
https://pythoninsider.blogspot.com/2019/05/use-two-factor-auth-to-improve-your.html | Python Insider: Use two-factor auth to improve your PyPI account's security
https://packaging.python.org/guides/making-a-pypi-friendly-readme/ | Making a PyPI-friendly README — Python Packaging User Guide

New PyPI
https://packaging.python.org/guides/migrating-to-pypi-org/ | Migrating to PyPI.org — Python Packaging User Guide
http://pyfound.blogspot.com/2018/02/python-package-maintainers-help-test.html | Python Software Foundation News: Python package maintainers, help test the new PyPI!
https://docs.google.com/forms/d/e/1FAIpQLSczrATlexkR1_gBt727eGnc05FCt-75Mx2usMq1wvCm_cLddg/viewform | Conducting user tests on PyPI
https://gist.github.com/nlhkabu/a0b1ae0016a2641f6b79d9ace9110403 | Recruiting User Testers for PyPI
https://docs.google.com/forms/d/e/1FAIpQLSfABpsRcVYt7RDJEsbL_2CnyH-IKXRCRwaBhCm4sYnNI6yB3A/viewform | Buy a feature
http://whoisnicoleharris.com/2018/05/17/warehouse-accessibility.html

https://status.python.org/incidents/1y1f44q6srh2 | Python Infrastructure Status - Next Generation PyPI Rollout
PyPI Translations
https://twitter.com/nlhkabu/status/1176378129012727808

Package Stats
* ["How to get PyPI download statistics"](https://kirankoduru.github.io/python/pypi-stats.html)

https://bigquery.cloud.google.com/table/the-psf:pypi.downloads | Google BigQuery
https://mail.python.org/pipermail/distutils-sig/2013-June/021344.html | [Distutils] Download Counts on PyPI
-->

## Software Lifecycle and Release Management

<!--
Hynek Schlawack
https://hynek.me/talks/python-foss/
https://pyvideo.org/pygotham-2019/maintaining-a-python-project-when-its-not-your-job.html
https://speakerdeck.com/hynek/maintaining-a-python-project-when-its-not-your-job

https://pyvideo.org/pycon-us-2018/how-to-write-deployment-friendly-applications.html
https://www.youtube.com/watch?v=wuCpCkrfeMs | Hynek Schlawack - How to Write Deployment-friendly Applications - PyCon 2018 - YouTube

Kyle Knapp
Important talk
https://www.youtube.com/watch?v=iKAaNaVpJFM | Automating Code Quality: Next Level - YouTube
https://2018.pygotham.org/talks/automating-code-quality-next-level/

https://pyvideo.org/speaker/kyle-knapp.html
https://www.youtube.com/watch?v=G1lDk_WKXvY | Kyle Knapp - Automating Code Quality - PyCon 2018 - YouTube
https://speakerdeck.com/pycon2018/kyle-knapp-automating-code-quality
https://pyvideo.org/pycon-us-2018/automating-code-quality.html
PyGotham

Thea's talk
https://www.youtube.com/watch?v=-BHverY7IwU

Carl Meyer: Set your code free
https://www.youtube.com/watch?v=nHWRN5gCPSI&feature=player_embedded
https://github.com/oddbird/set-your-code-free-preso/blob/master/slides.rst
https://www.oddbird.net/talks/set-your-code-free/

https://speakerdeck.com/carljm
https://github.com/carljm/dotfiles
-->

<!--
### Release management

release-bot
https://pypi.org/project/release-bot/ | release-bot · PyPI

Shields
https://raw.githubusercontent.com/Rolstenhouse/unofficial-apis/master/README.md | https://shields.io/ | Shields.io: Quality metadata badges for open source projects

towncrier
https://twitter.com/webKnjaZ/status/1289309686060048384 | Sviatoslove.py🐍 👨‍💻🏡:🇨🇿🇪🇺 @Ansible @RedHat on Twitter: "I'm now accepting name ideas for the #Sphinx extension I completed, that provides a directive for injecting towncrier draft version changelog into Sphinx sites: .. towncrier-draft-entries:: |release| [UNRELEASED DRAFT] 🐍 #Python #Sphinx_doc" / Twitter

Important- setuptools-scm
https://twitter.com/webKnjaZ/status/1268438408025817088 | (4) Sviatoslove.py🐍 👨‍💻🏡:🇨🇿🇪🇺 @Ansible @RedHat on Twitter: "@anthonypjshaw As in generating Python distribution package versions from Git tags? I normally use setuptools-scm by @ossronny. Works like a charm." / Twitter
https://github.com/pypa/setuptools_scm | pypa/setuptools_scm: the blessed package to manage your versions by scm tags

https://github.com/eventbrite/invoke-release | eventbrite/invoke-release: A set of command line tools that help software engineers release Python projects quickly, easily, and in a consistent manner.
https://github.com/twisted/incremental#updating | twisted/incremental: A library for versioning your Python projects.

https://www.youtube.com/watch?v=-BHverY7IwU
http://www.pyinvoke.org/
https://github.com/pypa/pip/blob/master/tasks/generate.py
-->

## Continuous Integration, Continuous Deployment, and Test Matrix

Continuousness
* [Continuous Integration Wikipedia](https://en.wikipedia.org/wiki/Continuous_integration)
* [Continuous Delivery Wikipedia](https://en.wikipedia.org/wiki/Continuous_delivery)

Continuous Integration Software
* [Continuous Integration Software Wikipedia](https://en.wikipedia.org/wiki/Comparison_of_continuous_integration_software)

Automation (includes Make)
* [Build Automation Wikipedia](https://en.wikipedia.org/wiki/Build_automation)

Other Stuff
* [Code Coverage Wikipedia](https://en.wikipedia.org/wiki/Code_coverage)
* [Traceability Matrix Wikipedia](https://en.wikipedia.org/wiki/Traceability_matrix)

## GitHub- Release Tools

Tags and Releases
* [GitHub About Milestones](https://help.github.com/en/articles/about-milestones)
* [GitHub About Releases](https://help.github.com/articles/about-releases) and [GitHub Creating Releases](https://help.github.com/articles/creating-releases)
* [GitHub Working with Tags](https://help.github.com/articles/working-with-tags)

<!--
https://help.github.com/en/actions/creating-actions/publishing-actions-in-github-marketplace

https://git-scm.com/book/en/v2/Git-Basics-Tagging
https://help.github.com/en/github/administering-a-repository/managing-releases-in-a-repository | Managing releases in a repository - GitHub Help

https://developer.github.com/v3/repos/releases/#create-a-release | Releases | GitHub Developer Guide
-->

## Release Management

Release Management
* [Release Management Wikipedia](https://en.wikipedia.org/wiki/Release_management)
* [Release Engineering Wikipedia](https://en.wikipedia.org/wiki/Release_engineering)
* [Release Deployment Wikipedia](https://en.wikipedia.org/wiki/Software_deployment)

Software Release Life Cycle and Versioning
* [Software Release Life Cycle Wikipedia](https://en.wikipedia.org/wiki/Software_release_life_cycle)
* [Software Versioning Wikipedia](https://en.wikipedia.org/wiki/Software_versioning)
* [Rolling Release Wikipedia](https://en.wikipedia.org/wiki/Rolling_release)

Software Versioning and Semver (See also: npm packages)
* [Semver](http://semver.org) and [Semver GitHub](https://github.com/mojombo/semver) 
* [CalVer](https://calver.org)
* [ZeroVer](https://0ver.org)

Not what I thought
* [Application Release Automation Wikipedia](https://en.wikipedia.org/wiki/Application_release_automation)

<!--
SemVer Criticism
https://twitter.com/hynek/status/1235848177640542214
https://snarky.ca/why-i-dont-like-semver/ | Why I don't like SemVer anymore
https://twitter.com/ncoghlan_dev/status/882576856938987521

SemVer
https://words.steveklabnik.com/what-s-next-for-semver | What’s next for SemVer

https://twitter.com/_ericelliott/status/1201639694800433152 | Eric Elliott on Twitter: "): Major.Minor.Patch :) Breaking.Feature.Fix https://t.co/jDFNzOZZDu #JavaScript" / Twitter
https://medium.com/javascript-scene/software-versions-are-broken-3d2dc0da0783 | Software Versions are Broken - JavaScript Scene - Medium
-->
