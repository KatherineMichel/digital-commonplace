# Software Lifecycle and Release Management

<!--
Probot and Such

https://github.com/gr2m/create-or-update-pull-request-action
https://twitter.com/gr2m/status/1224742792280211456
https://twitter.com/gr2m/status/1200326993838886912 | Gregor on Twitter: "This thanksgiving I'm thankful to @JasonEtco and the GitHub support team who saved my 🍑 big time https://t.co/4MIsYKAzXz" / Twitter

https://github.com/gr2m/twitter-together

https://github.com/probot/reminders

https://dev.to/gh-campus-experts/create-your-first-github-bot-with-probot-e6o

Probot
https://probot.github.io/apps/ | Featured Apps | Probot
https://probot.github.io/docs/hello-world/ | Hello world | Probot
https://probot.github.io/apps/polls/ | Polls | Probot
https://probot.github.io/apps/no-response/ | No Response | Probot
https://github.com/probot/dco | probot/dco: GitHub App that enforces the Developer Certificate of Origin (DCO) on Pull Requests

Make semantic-release compatible with GitHub Actions
https://github.com/semantic-release/semantic-release/issues/1194
Python Plugin
https://github.com/semantic-release/git/issues/172#issuecomment-557203217

https://github.com/JasonEtco/build-and-tag-action | JasonEtco/build-and-tag-action: 📦🔖 A GitHub Action for publishing JavaScript Actions
https://github.com/JasonEtco/actions-toolkit | JasonEtco/actions-toolkit: 🛠 A toolkit for building GitHub Actions in Node.js
https://github.com/probot/create-probot-app
https://github.com/probot/actions-adapter | probot/actions-adapter: An adapter that takes a Probot app and makes it compatible with GitHub Actions

https://github.com/JasonEtco/jasonet.co/pull/46/files
-->

<!--
Python- Publishing

PyPI GitHub Actions
https://twitter.com/webKnjaZ/status/1268324832736768000 | Sviatoslove.py🐍 👨‍💻🏡:🇨🇿🇪🇺 @Ansible @RedHat on Twitter: "PyPI publish GHA updates today: - built-in `twine check` - image bump to Python 3.8 - integration of warning annotations - very minor bugfixes https://t.co/2HOkYnVPV7 #PyPI #PyPA #GitHubActions #python" / Twitter

Brett Release
https://github.com/brettcannon/release-often | brettcannon/release-often: GitHub Action for releasing a Python project to PyPI after every relevant, merged PR

Important
https://github.com/marketplace/actions/pypi-publish | pypi-publish · Actions · GitHub Marketplace
https://github.com/pypa/gh-action-pypi-publish/issues/2
https://github.com/pypa/gh-action-pypi-publish | pypa/gh-action-pypi-publish: GitHub Action to publish a package to PyPI
https://discuss.python.org/t/official-github-action-for-publishing-to-pypi/1061/2 | Official GitHub Action for publishing to PyPI - Packaging - Discussions on Python.org

Publish to PyPI
https://github.com/jacobian/pinboard-to-sqlite/blob/master/.github/workflows/publish.yml
https://github.com/jacobian/lastfm-to-sqlite/blob/master/.github/workflows/test.yml | lastfm-to-sqlite/test.yml at master · jacobian/lastfm-to-sqlite
-->

<!--
https://github.com/Songmu/ghch | Songmu/ghch: Generate changelog from git history, tags and merged pull requests

Testing and Release

Conventional Commits
https://github.com/googleapis/release-please | googleapis/release-please: generate release PRs based on the conventionalcommits.org spec

https://github.com/marketplace?utf8=%E2%9C%93&type=actions&query=semantic
https://www.conventionalcommits.org/en/v1.0.0-beta.4/
https://github.com/commitizen/conventional-commit-types/
https://github.com/commitizen/conventional-commit-types/blob/master/index.json
https://github.com/probot/semantic-pull-requests | probot/semantic-pull-requests: Ensure your pull requests follow the Conventional Commits spec
https://github.com/semantic-release/npm
https://twitter.com/SemanticRelease

Semantic Release and Merge Release
https://semantic-release.gitbook.io/semantic-release/
https://github.com/semantic-release
https://github.com/semantic-release/semantic-release

https://github.com/marketplace/actions/codecov

https://probot.github.io/apps/release-drafter/

https://github.com/mikeal/merge-release | mikeal/merge-release: Automatically release all merges to master on npm.
-->

<!--
## Release management

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

## Great Release Managers

<!--
People and Projects

Includes issues links
* [Python Packaging Key Projects](https://packaging.python.org/key_projects)
https://www.encode.io/projects/

https://twitter.com/PalletsTeam

https://github.com/orgs/pytest-dev/people
https://github.com/orgs/pypa/people
https://github.com/orgs/python/people
https://github.com/orgs/tox-dev/people
https://github.com/orgs/pallets/people
https://github.com/orgs/pre-commit/people
https://github.com/python/cpython/graphs/contributors

Encode

https://www.encode.io/projects/

https://www.encode.io/reports/july-2019/ | Encode
http://www.django-rest-framework.org/topics/kickstarter-announcement/ | Kickstarter Announcement - Django REST framework
https://discuss.encode.io/ | Encode
-->

### Projects

### Ned Batchelder

* [coverage.py GitHub](https://github.com/nedbat/coveragepy/)

<!--
https://github.com/nedbat/coveragepy/issues/
-->

### Hynek Schlawack

* [Hynek GitHub](https://github.com/hynek)
* [Hynek Talks](https://hynek.me/talks/)

<!--
https://hynek.me/talks/python-foss/
https://pyvideo.org/pygotham-2019/maintaining-a-python-project-when-its-not-your-job.html
https://speakerdeck.com/hynek/maintaining-a-python-project-when-its-not-your-job
https://www.google.com/search?q=hynek+schlawack+not+your+job&oq=hynek+schlawack+not+your+job&aqs=chrome.0.69i59j33.6804j0j7&sourceid=chrome&ie=UTF-8 | hynek schlawack not your job - Google Search

https://pyvideo.org/pycon-us-2018/how-to-write-deployment-friendly-applications.html
https://www.youtube.com/watch?v=wuCpCkrfeMs | Hynek Schlawack - How to Write Deployment-friendly Applications - PyCon 2018 - YouTube
-->

<!--
## Talks

Contributing- Important
https://github.com/python-attrs/attrs/blob/master/.github/CONTRIBUTING.rst

Not sure...
https://setuptools.readthedocs.io/en/latest/setuptools.html#declaring-extras-optional-features-with-their-own-dependencies

PyPI long description
https://github.com/python-attrs/attrs/blob/de84609505845edc0e05c2ff918a44085816e35e/tox.ini#L63-L71
http://mypy-lang.org/

Formatting and Stuff

fan of 79 characters line lengths. 
https://github.com/python-attrs/attrs/blob/de84609505845edc0e05c2ff918a44085816e35e/pyproject.toml#L6-L7
https://treyhunner.com/2017/07/craft-your-python-like-poetry/

settings
https://github.com/python-attrs/attrs/blob/6fa28b3b074a935038dd701382eb67f0e953d097/setup.cfg#L20-L31
https://prettier.io/
pre-commit config
https://github.com/python-attrs/attrs/blob/master/.pre-commit-config.yaml

Change Log
https://pypi.org/project/towncrier/

Packaging
https://hynek.me/articles/sharing-your-labor-of-love-pypi-quick-and-dirty/

Alex Grönholm - Automating testing and deployment with Github and Travis
https://www.youtube.com/watch?v=btqFjNDdTlE

credential management
https://github.com/joerick/cibuildwheel
https://github.com/explosion/wheelwright

setup.py
https://github.com/python-attrs/attrs/blob/master/setup.py
canonical package data
https://github.com/python-attrs/attrs/blob/6fa28b3b074a935038dd701382eb67f0e953d097/src/attr/__init__.py#L21-L33
rexexps
https://github.com/python-attrs/attrs/blob/6fa28b3b074a935038dd701382eb67f0e953d097/setup.py#L67-L79
https://github.com/sdispater/poetry/issues/1036

Change Log
https://github.com/hynek/structlog/blob/master/CHANGELOG.rst
https://raw.githubusercontent.com/python-attrs/attrs/master/CHANGELOG.rst

Extra change log entries
https://github.com/python-attrs/attrs/blob/6fa28b3b074a935038dd701382eb67f0e953d097/setup.py#L84-L97
Example
https://pypi.org/project/attrs/

https://github.com/hynek/structlog/commit/92f46e5ff2d014c8e7e6a11166165a3e6dc1288b
https://www.sphinx-doc.org/en/master/usage/builders/index.html#sphinx.builders.linkcheck.CheckExternalLinksBuilder
https://github.com/hynek/structlog/commit/1468a34661d2035198ff3eb925883a8b8d959919
-->

### Paul Ganssle

<!--
https://blog.ganssle.io/articles/2018/02/aware-datetime-arithmetic.html | Semantics of timezone-aware datetime arithmetic

https://twitter.com/pganssle/status/1262094764004040707 | Paul Ganssle on Twitter: "If anyone has strong feelings about how to get a list of available time zones on Python, please comment here — feature freeze is tomorrow! Issue: https://t.co/OnxWURMV1N PR: https://t.co/jOShLh47kD Bit of an oversight that this wasn't in PEP 615... #python" / Twitter

https://github.com/python/cpython/commit/b17e49e0def23238b9e7f48c8a02e2d7bbf1f653
https://twitter.com/pganssle/status/1230848453321904130 | Paul Ganssle on Twitter: "Oh boy. Standard library time zone implementation is now passing a lot of tests. Still a bunch of TODO comments and tests to write but I think the API might be close to final. Looks like it's time to start in on the documentation.😬 #python #timezones #documentation" / Twitter
https://twitter.com/pganssle/status/1213826961182744576 | Paul Ganssle on Twitter: "I soft-launched this a few weeks back, but here is my most polished (i.e. not very) @rustlang project to date: metadata-backup, a tool for backing up your file system metadata. Contributions welcome! https://t.co/dg43qKxjFR" / Twitter
-->

### Anthony Sottile

Builds lots of productivity tools, linters, and code formatters

Sponsor Bio
* [Anthony Sponsor Bio](https://github.com/sponsors/asottile)

Regular Accounts
* [Anthony Sottile GitHub](https://github.com/asottile/)
* [Anthony Sottile Archive GitHub](https://github.com/asottile-archive)

Twitch-Related
* [Twitch](https://www.twitch.tv/anthonywritescode)
* [Twitch GitHub](https://github.com/anthonywritescode)
* [Twitch YouTube](https://www.youtube.com/channel/UC46xhU1EH7aywEgvA9syS3w/videos)
* [Anthony Sottile Twitter](https://twitter.com/codewithanthony)

Advent of Code
* [Advent of Code GitHub](https://github.com/anthonywritescode/aoc2019/)

Creator
* [pre-commit](https://pre-commit.com)
* [seed-isort-config GitHub](https://github.com/asottile/seed-isort-config)

Core Developer
* [pytest](http://pytest.org) and [pytest Docs](https://docs.pytest.org/)
* [Tox Read the Docs](https://tox.readthedocs.org)

Maintainer (maintain pyflakes as a member of the @PyCQA)
* [Flake8 GitHub](https://gitlab.com/pycqa/flake8) and [Flake8 Docs](http://flake8.pycqa.org)
* [Pyflakes GitHub](https://gitlab.com/pycqa/flake8)

pycodestyle
* [pycodestyle GitHub](https://github.com/PyCQA/pycodestyle)

<!--
https://github.com/PyCQA/pycodestyle/issues/466
-->

Special Projects
* [babi](https://github.com/asottile/babi)
* [babi-editor](https://github.com/babi-editor)

<!--
Anthony
https://github.com/asottile2/demo2 | asottile2/demo2
https://github.com/asottile/setup-cfg-fmt | asottile/setup-cfg-fmt: apply a consistent format to `setup.cfg` files
https://github.com/asottile/no-manylinux/blob/master/setup.cfg | no-manylinux/setup.cfg at master · asottile/no-manylinux
https://github.com/asottile/blacken-docs | asottile/blacken-docs: Run `black` on python code blocks in documentation files

https://keeb.io/products/bdn9-3x3-9-key-macropad-rotary-encoder-support | BDN9 - 3x3 9-key Macropad - Rotary Encoder Support – Keebio

deadsnakes
https://launchpad.net/~deadsnakes/+archive/ubuntu/ppa | New Python Versions : “deadsnakes” team
https://github.com/deadsnakes-issues-bot/test | deadsnakes-issues-bot/test
https://github.com/deadsnakes/action | deadsnakes/action: a GitHub action to install (pre-release) pythons from deadsnakes
https://github.com/deadsnakes/python3.10-nightly/blob/master/.github/workflows/main.yml | python3.10-nightly/main.yml at master · deadsnakes/python3.10-nightly
-->

<!--
https://github.com/pre-commit-ci | pre-commit-ci
https://github.com/pre-commit-ci/pre-commit.ci | pre-commit-ci/pre-commit.ci: Website for https://pre-commit.ci

https://discordapp.com/invite/HxpQ3px | anthonywritescode
https://www.twitch.tv/team/livecoders | (1) Twitch

https://www.youtube.com/watch?v=gQM0s7hu-58 | Music for your relax | Chill music - YouTube
https://www.youtube.com/watch?v=C2xVBGRXiMY&list=PL44UysF4ZQ23B_ITIqM8Fqt1UXgsA9yD6&index=80 | (2) Infinity | Beautiful Chill Mix - YouTube
https://www.youtube.com/watch?v=eAD3YI354kY&list=PL44UysF4ZQ23B_ITIqM8Fqt1UXgsA9yD6&index=166 | Deeper | Beautiful Chill Mix - YouTube
https://www.youtube.com/watch?v=o6jTTZZ9EFQ&list=PL44UysF4ZQ23B_ITIqM8Fqt1UXgsA9yD6&index=67 | Triton - Borealis - YouTube
https://www.youtube.com/watch?v=eN9fGWaihZw&list=PL44UysF4ZQ23B_ITIqM8Fqt1UXgsA9yD6&index=66 | A Gon - You - YouTube

https://github.com/anthonywritescode/thumbnails/blob/master/assets/pythonk.svg | thumbnails/pythonk.svg at master · anthonywritescode/thumbnails

https://www.youtube.com/watch?v=XLRdSxlIIfc | Keep Your Code Clean Using pre-commit with Anthony Sottile - YouTube
https://testandcode.com/104

deadsnakes
https://github.com/deadsnakes/action | deadsnakes/action: a GitHub action to install (pre-release) pythons from deadsnakes

Builds backported/forwardported pythons for ubuntu with @deadsnakes
https://twitter.com/codewithanthony/status/1242245981590007808
https://github.com/deadsnakes/nightly | deadsnakes/nightly: (experimental) nightly debian packaging of pythons
https://github.com/deadsnakes
https://launchpad.net/~deadsnakes/+archive/ubuntu/ppa

https://github.com/pre-commit/mirrors-autopep8/commit/5985fb24f71421cd14f9cda5d6c7a06fc30b321c
https://github.com/anthonywritescode/cfp/blob/master/lyftvenv.md

https://github.com/asottile/babi/blob/master/requirements-dev.txt | babi/requirements-dev.txt at master · asottile/babi

all-repos
https://github.com/asottile/all-repos | asottile/all-repos: Clone all your repositories and apply sweeping changes.

https://github.com/anthonywritescode/twitch-chat-bot

https://github.com/asottile/onigurumacffi/pull/20/files
https://github.com/asottile/scratch/wiki | Home · asottile/scratch Wiki
https://github.com/asottile/add-trailing-comma
https://github.com/asottile/t
https://github.com/asottile/git-code-debt

https://github.com/asottile/hecate | asottile/hecate: A terrible way of testing terminal applications

Drop python 2 / python3.5 support in pre-commit
https://github.com/pre-commit/pre-commit/releases/tag/v2.0.0
https://github.com/pre-commit/pre-commit/issues/1260
https://github.com/pre-commit/pre-commit/pull/1277

https://pre-commit.com/#python
https://pre-commit.com/hooks.html

http://linter-runner.com
https://twitter.com/codewithanthony/status/1208048314987548673 | Anthony Sottile on Twitter: "@KatiMichel https://t.co/S6NBCRYnJj coming soon ;)" / Twitter
https://git-scm.com/book/en/v2/Customizing-Git-Git-Hooks | Git - Git Hooks

PyTest
https://twitter.com/codewithanthony/status/1195477147537657856
https://twitter.com/nicoddemus/status/1195088740118618112
https://twitter.com/blueyed/status/1222578734676484096
https://twitter.com/codewithanthony/status/1213573183879692289 | Anthony Sottile on Twitter: "#pytest 4.6.9 has been released! this marks the beginning of community supported 4.6 maintenance of python 2 / python 3.4 (core will still accept patches to 4.6 but will no longer be actively backporting to 4.6) -- long live python 2! more details here: https://t.co/6b7Ilkr8ko" / Twitter

https://github.com/asottile/pyupgrade/blob/997f4452c82848afdeda08ec3d2bef8b08d5ebe1/.travis.yml | pyupgrade/.travis.yml at 997f4452c82848afdeda08ec3d2bef8b08d5ebe1 · asottile/pyupgrade
https://github.com/asottile/pyupgrade/blob/34a269fd7650d264e4de7603157c10d0a9bb8211/azure-pipelines.yml#L23 | pyupgrade/azure-pipelines.yml at 34a269fd7650d264e4de7603157c10d0a9bb8211 · asottile/pyupgrade
https://github.com/search?l=YAML&o=desc&q=-+++env%3A+TOXENV%3Dpy36&s=indexed&type=Code | Search · - env: TOXENV=py36
https://tox.readthedocs.io/en/latest/config.html | tox configuration specification — tox 3.14.2.dev12 documentation

https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo?hl=en | Tampermonkey - Chrome Web Store
https://addons.mozilla.org/en-US/firefox/addon/greasemonkey/ | Greasemonkey – Get this Extension for 🦊 Firefox (en-US)

https://github.myshopify.com/collections/collectibles/products/ship-it-enamel-pin | Ship It Pin – GitHub
https://chriskuehl.github.io/shipit/ | https://chriskuehl.github.io/shipit/
https://github.com/chriskuehl/shipit | chriskuehl/shipit
-->

## Tool Choices

<!--
https://snarky.ca/thoughts-on-a-tooling-workflow/
https://twitter.com/brettsky/status/1260782564597366785

https://twitter.com/froidotdev/status/1248661469920714753

https://mobile.twitter.com/carltongibson/status/1243893076407603200 | Carlton Gibson 🇪🇺 on Twitter: "@zooba Clean My Mac is good. (Not sure about any particular malware but...)" / Twitter

Simon- Tools
https://twitter.com/simonw/status/1222726628314210311 | Simon Willison on Twitter: "Woohoo! Got continuous deployment of my new Django app working in GitLab CI, which builds a Docker image, runs tests in it, pushes it to the GitLab Container Registry then uses SSH to tell my server to pull the latest image and start serving it via Traefik!" / Twitter
https://simonwillison.net/2020/Feb/11/cheating-at-unit-tests-pytest-black/
This is a good starting point for getting Python, Django, Postgres running as a service, pytest, black, and pip caching rolling with GitHub Actions.
https://twitter.com/simonw/status/1248628140445855745

https://github.com/cortesi/devd
https://twitter.com/webology/status/1192623306840723456 | 🍂 Jeff Triplett 🍂 on Twitter: "Until I finish my blog post (which is about 100 items behind other priorities in life right now), this gist + screenshot are of my modd, django, python, tailwindcss, black, and pytest setup that I re-use from project-to-project." / Twitter
https://twitter.com/webology/status/1234940864687939586 | ✨ Jeff Triplett ✨ on Twitter: "I'm a coin flip on using pytest-black locally right now. I like it a lot for CI to avoid having to have an extra step, but it seems to step on my toes testing locally every so often. That said, I don't want two pytest.ini configs." / Twitter
https://mobile.twitter.com/webology/status/1195163668440334337

https://mobile.twitter.com/brettsky/status/1223731773147766784
https://twitter.com/gvanrossum/status/1227126706089021440
https://twitter.com/mariatta/status/1227286873413799936
https://twitter.com/jonasrk/status/1227028183469449216
https://twitter.com/WillingCarol/status/1227331652046770176
https://twitter.com/jacobian/status/1150072802801848320 | jacobian on Twitter: "This is my standard setup too. It's lovely, probably prevents half or more of the silly mistakes I'm prone to making.… https://t.co/ADRHdOq6A3"
https://twitter.com/hawkieowl/status/1150038262540431361 | -mtune=hawk -march=owl on Twitter: "But, anyway. The Ideal Python Development environment for me uses attrs in the code, black and isort to autoformat, flake8/pyflakes to verify, and tox and @nedbat 's Coverage to test. And pytest, if you don't have a particular affinity for xUnit like me :P"
-->

