# Python Tools and Release Managers

<!--
Pinax
https://en.wikipedia.org/wiki/Software_versioning#Release_train

https://twitter.com/simonw/status/1262970529746612224 | Simon Willison on Twitter: "Activity Monitor on my Mac shows Python running 438.9% CPU (SHA256 hashing 40,000 files using 5 threads) so it's definitely running across multiple cores. And the program seems to complete about 4x faster. So if, like me, you've mostly avoided threads in Python give them a go!" / Twitter

Bernat- rewrite
https://www.youtube.com/watch?v=RVK7rsFEfpc&feature=youtu.be&t=15630

Profiling
https://www.youtube.com/watch?v=ey_P64E34g0&feature=youtu.be
https://github.com/asottile/importtime-waterfall/
har http timing


https://realpython.com/python-code-quality/ | Python Code Quality: Tools & Best Practices – Real Python
https://realpython.com/lessons/python-traceback-overview/ | Getting the Most Out of a Python Traceback (Overview) – Real Python

https://hynek.me/articles/waiting-in-asyncio/ | Waiting in asyncio · Homepage of Hynek Schlawack

PyPI GitHub Actions
https://twitter.com/webKnjaZ/status/1268324832736768000 | Sviatoslove.py🐍 👨‍💻🏡:🇨🇿🇪🇺 @Ansible @RedHat on Twitter: "PyPI publish GHA updates today: - built-in `twine check` - image bump to Python 3.8 - integration of warning annotations - very minor bugfixes https://t.co/2HOkYnVPV7 #PyPI #PyPA #GitHubActions #python" / Twitter

https://github.com/TezRomacH/python-package-template | TezRomacH/python-package-template: Your next Python package needs a bleeding-edge project structure.


https://www.brennantymrak.com/articles/django-class-based-views-diagrams | Django Class Based Views

https://adamj.eu/tech/2019/04/03/django-versus-flask-with-single-file-applications/
https://adamj.eu/tech/2019/09/14/a-single-file-async-django-app/ | A Single File Asynchronous Django Application - Adam Johnson

https://twitter.com/Podcast__init__/status/1267634528740311041 | Podcast.__init__ on Twitter: "Do you wish you could extend the life of your Python 2 projects? Then check out Tauthon! In this episode Naftali Harris shares his work on the fork of Python 2 that backports fun and useful features from Python 3. https://t.co/m2kmgv8EcJ" / Twitter


pip install
https://twitter.com/pganssle/status/1289010601415577600 | Paul Ganssle on Twitter: ""Doctor, it hurts when I invoke https://t.co/o3PGyRiVuO install." "Stop doing that then!" (Seriously, always use pip install, never https://t.co/o3PGyRiVuO install)" / Twitter

https://twitter.com/llanga/status/986645110518509568 | Łukasz Langa on Twitter: "TIL about https://t.co/BtoFQvaMlW. Compared to Pipenv, the cmdline is different, it uses the standard pyproject.toml for configuration instead of the custom Pipfile, and caret dependencies are a usability improvement. It will be very interesting to see which will win long term."


Pinning
https://twitter.com/carltongibson/status/1249033282831908870 | Carlton Gibson 🇪🇺 on Twitter: "@webology How do they not get unexpected breakages then?" / Twitter

Gidgethub
https://mobile.twitter.com/mariatta/status/1251733060812369920

pathlib
https://twitter.com/wsv3000/status/1286022846939107329 | Will Vincent on Twitter: "I'm a fan of switching to pathlib in Django 3.1 but it's gonna brick A LOT of older tutorials for newbies who can't get their https://t.co/dr8oMArbJE files to work right. Not sure how to mitigate this..." / Twitter


Python Docker
https://twitter.com/brettsky/status/1146835613628293120 | Twitter
https://github.com/microsoft/vscode-dev-containers/blob/master/containers/python-3/.devcontainer/Dockerfile

Packaging
https://twitter.com/webKnjaZ/status/1287690737778335744 | Sviatoslove.py🐍 👨‍💻🏡:🇨🇿🇪🇺 @Ansible @RedHat on Twitter: "@codewithanthony @codewithanthony FYI there's also `wheel unpack` for extracting whl contents" / Twitter

https://twitter.com/avallbona/status/1270755378654064641 | underdog on Twitter: "the --devenv command option https://t.co/l0ZU3C9vtP is a game changer feature, added recently by @codewithanthony #kudos" / Twitter

https://twitter.com/pganssle/status/1270056171861401601
Release
https://twitter.com/anthonypjshaw/status/1270205981616529408 | Anthony Shaw 🐍 on Twitter: "If you use @AzureDevOps Pipelines and @pytestdotorg please can you try pytest-azurepipelines==1.0.0rc3 it has loads of changes including embedding code coverage into the Pipelines UI from https://t.co/NjlLN1tfOD I need more testers! https://t.co/Mza0ke6UiS https://t.co/0FiABgr3l5" / Twitter
-->


<!--
Tools

https://github.com/Mariatta/requirements_atoz
https://github.com/Mariatta/cookiecutter_sprint_guide
https://github.com/Mariatta/pep_cookiecutter
https://github.com/hbristow/cookiecutter-cpp/blob/master/.travis.yml
https://github.com/jambonsw/cookiecutter-static-site

https://launchpad.net/ubuntu | Ubuntu in Launchpad

pip-tools
https://twitter.com/jonafato/status/1283429696471027713 | Jon Banafato on Twitter: "Listen to Jeff. pip-tools is great." / Twitter
https://lincolnloop.com/blog/python-dependency-locking-pip-tools/ | Python Dependency Locking with pip-tools | Lincoln Loop

django-lifecycle
https://twitter.com/carltongibson/status/1279334203457523713 | Carlton Gibson 🇪🇺 on Twitter: "Folks still using django-lifecycle? What are the thoughts Some Time Later?" / Twitter

towncrier
https://twitter.com/webKnjaZ/status/1289309686060048384 | Sviatoslove.py🐍 👨‍💻🏡:🇨🇿🇪🇺 @Ansible @RedHat on Twitter: "I'm now accepting name ideas for the #Sphinx extension I completed, that provides a directive for injecting towncrier draft version changelog into Sphinx sites: .. towncrier-draft-entries:: |release| [UNRELEASED DRAFT] 🐍 #Python #Sphinx_doc" / Twitter

Important- setuptools-scm
https://twitter.com/webKnjaZ/status/1268438408025817088 | (4) Sviatoslove.py🐍 👨‍💻🏡:🇨🇿🇪🇺 @Ansible @RedHat on Twitter: "@anthonypjshaw As in generating Python distribution package versions from Git tags? I normally use setuptools-scm by @ossronny. Works like a charm." / Twitter
https://github.com/pypa/setuptools_scm | pypa/setuptools_scm: the blessed package to manage your versions by scm tags

https://github.com/asottile/all-repos | asottile/all-repos: Clone all your repositories and apply sweeping changes.	
https://adamj.eu/tech/2020/04/02/maintaining-multiple-python-projects-with-myrepos/ | Maintaining Multiple Python Projects With myrepos - Adam Johnson

Test plugins
https://github.com/pytest-dev/pytest-bdd | pytest-dev/pytest-bdd: BDD library for the py.test runner
https://pypi.python.org/pypi/pytest-xdist | pytest-xdist 1.20.1 : Python Package Index
https://talkpython.fm/episodes/show/267/15-amazing-pytest-plugins | Episode #267 15 amazing pytest plugins - [Talk Python To Me Podcast]

Sphinx/Read the Docs
https://dont-be-afraid-to-commit.readthedocs.io/en/latest/documentation.html | Documentation using Sphinx and ReadTheDocs.org — Don't be afraid to commit 0.3 documentation

Shields
https://raw.githubusercontent.com/Rolstenhouse/unofficial-apis/master/README.md | https://shields.io/ | Shields.io: Quality metadata badges for open source projects

https://pypi.org/project/keyring/ | keyring · PyPI

https://pypi.org/project/pypi-simple/ | pypi-simple · PyPI

cross linter - Google Search

https://pypi.org/project/mousebender/ | mousebender · PyPI
https://pypi.org/project/pluggy/ | pluggy · PyPI

https://github.com/moshez/txpursuedpybear/tree/draft | moshez/txpursuedpybear at draft

Python
Django self-update
https://github.com/pyupio/safety | pyupio/safety: Safety checks your installed dependencies for known security vulnerabilities
https://pyup.io/safety/

https://pyformat.info/
-->

## Companies that Use Python

Companies that Use Python
* PyCon Slide

High Performance Python- Engineering Blogs
* [Bloomberg](https://www.techatbloomberg.com/)
* [Dropbox](https://blogs.dropbox.com)
* [Google](https://developers.googleblog.com)
* [Instagram](https://engineering.instagram.com)
* [Netflix](https://medium.com/netflix-techblog)
* [Quora](https://engineering.quora.com)
* [Reddit](https://redditblog.com)
* [Spotify](https://labs.spotify.com)
* [Uber](https://eng.uber.com)
* [Zapier](https://zapier.com/engineering)

## Major Organizations and Projects that Use Python or Django

<!--
* [23andMe](https://github.com/23andMe) 
* [Alexa](https://github.com/alexa) 
* [Amazon Web Services](https://github.com/amazonwebservices)  
* [Amazon](https://github.com/amzn)
* [AWS](https://github.com/aws)  
* [AWS Labs](https://github.com/awslabs)
* [Apple](https://github.com/apple)
* [Bloomberg](https://github.com/bloomberg) 
* [Box](https://github.com/box) 
* [Britecore](https://github.com/britecore) 
* [Disney](https://github.com/disney)
* [Doctor on Demand](https://github.com/doctorondemand)
* [Dropbox](https://github.com/dropbox) 
* [Elastic](https://github.com/elastic)
* [Facebook](https://github.com/facebook)  
* [Facebook Archive](https://github.com/facebookarchive)  
* [Facebook Experimental](https://github.com/facebookexperimental)
* [Facebook Go](https://github.com/facebookgo)
* [Facebook Incubator](https://github.com/facebookincubator)
* [Facebook Platform Samples](https://github.com/fbsamples) 
* [Facebook Research](https://github.com/facebookresearch)
* [Ford](https://github.com/Ford)
* [GoDaddy](https://github.com/godaddy)

* [Android](https://github.com/android) 
* [Google](https://github.com/google)  
* [Actions on Google](https://github.com/actions-on-google)
* [Google Ads](https://github.com/googleads)  
* [Google Chrome](https://github.com/GoogleChrome)  
* [Google Chrome Labs](https://github.com/GoogleChromeLabs)  
* [(Google) ChromeDevTools](https://github.com/ChromeDevTools)
* [Google Cloud Platform](https://github.com/GoogleCloudPlatform) 
* [Google Container Tools](https://github.com/GoogleContainerTools)  
* [Google Creative Lab](https://github.com/googlecreativelab) 
* [Google Developer Training](https://github.com/google-developer-training) 
* [Google Drive](https://github.com/googledrive) 
* [Google Genomics](https://github.com/googlegenomics)  
* [Google Glass](https://github.com/googleglass)  
* [Google Knowledge](https://github.com/googleknowledge)  
* [Google Maps](https://github.com/googlemaps)  
* [Google Samples](https://github.com/googlesamples) 
* [G Suite Devs](https://github.com/gsuitedevs )
* [YouTube](https://github.com/youtube)

* [Grubhub](https://github.com/grubhub) 
* [IBM](https://github.com/IBM)  
* [IBM Cloud](https://github.com/IBM-Cloud)
* [Indeed](https://github.com/indeedeng)
* [Instagram](https://github.com/Instragram)  
* [LinkedIn GitHub](https://github.com/linkedin)
lulumon
* [Lyft](https://github.com/lyft)
magic leap
* [MailChimp](https://github.com/mailchimp) 
markel corporation!
MIT
* [Mozilla](https://github.com/mozilla)
* [Mozilla Developer Network](https://github.com/mdn)
* [Mozilla Developer Outreach](https://github.com/mozdevs)
* [Mozilla devtools-html](https://github.com/devtools-html)
* [Mozilla Foundation](https://github.com/MozillaFoundation)
* [Mozilla IoT](https://github.com/mozilla-iot)
* [Mozilla Services](https://github.com/mozilla-services)
nasa
nbc universal
netapp
new relic
* [Nike Inc.](https://github.com/Nike-Inc)
* [Netflix](https://github.com/Netflix) 
o'reilly
* [Patreon](https://github.com/patreon)  
* [PayPal](https://github.com/paypal) 
* [Rackspace](https://github.com/rackspace)
* [Reddit](https://github.com/reddit) 
redhat
* [Roverdotcom](https://github.com/roverdotcom)
* [Salesforce GitHub](https://github.com/salesforce)
* [Samsung GitHub](https://github.com/Samsung)
sony 
* [Spotify](https://github.com/spotify) 
the walt disney company
thoughtworks
* [Tumblr](https://github.com/tumblr) 
* [Vox Media](https://github.com/voxmedia) 
* [Walmart Labs](https://github.com/walmartlabs) 
walt disney animations tudios
* [Wayfair](https://github.com/wayfair)
* [Yandex](https://github.com/yandex)
* [Yelp](https://github.com/Yelp) 
-->

## Django Consulting Firms

Python and Django Consulting Firm GitHub Accounts
* [Caktus Group GitHub](https://github.com/caktus) and [Caktus Group Blog](https://www.caktusgroup.com/blog)
* [Changeset Consulting](https://changeset.nyc)
* [Cuttlesoft GitHub](https://github.com/cuttlesoft) and [Cuttlesoft Blog](https://www.cuttlesoft.com/blog)
* [Divio GitHub](https://github.com/divio) and [Divio Blog](https://www.divio.com/blog)
* [Eldarion GitHub](https://github.com/eldarion) and [Eldarion Blog](http://eldarion.com/blog)
* [JamBon Software GitHub](https://github.com/jambonsw) and [JamBon Software](http://www.jambonsw.com)
* [Lincoln Loop GitHub](https://github.com/lincolnloop) and [Lincoln Loop Blog](https://lincolnloop.com/blog)
* [Pinax](https://pinaxproject.com) and [Pinax Blog](http://blog.pinaxproject.com)
* [Revolution Systems (Frank Wiles) GitHub](https://github.com/revsys), [Revolution Systems Blog](http://www.revsys.com/blog), [Revolution Systems Writings](http://www.revsys.com/writings), and [RevSys Tidbits](http://www.revsys.com/tidbits) 
* [Torchbox GitHub](https://github.com/torchbox) and [Torchbox Blog](https://torchbox.com/blog)
* [Truthful Technology GitHub](https://github.com/TruthfulTechnology) and [Truthful Technology](https://truthful.technology)
* [Vinta Software GitHub](https://github.com/vintasoftware) and [Vinta Blog](https://www.vinta.com.br/blog)

<!--
https://www.jbssolutions.com/

DjangoCon sponsors
https://2018.djangocon.us/sponsors/
-->

## Major Organizations and Projects that Use Django

* [18F GitHub](https://github.com/18F)  
* [Dallas Morning News (The)](https://github.com/DallasMorningNews)
* [Disqus](https://github.com/disqus)
* [Instagram GitHub](https://github.com/instagram)  
* [Knight Foundation](http://www.knightfoundation.org/apps)  
* [Mozilla GitHub](https://github.com/mozilla)
* [National Geographic GitHub](https://github.com/natgeo)  
* [Northwestern University Knight Lab GitHub](https://github.com/NUKnightLab)
* [PBS GitHub](https://github.com/pbs)  
* [Pinterest GitHub](https://github.com/pinterest)  
* [Rdio GitHub](https://github.com/rdio)  
* [Reddit GitHub](https://github.com/reddit)  
* [Rover GitHub](https://github.com/roverdotcom)
* [StyleSeat GitHub](https://github.com/styleseat) 
* [The Spokesman Review](http://www.spokesman.com)
* [Wharton GitHub](https://github.com/wharton)
* [Wharton Learning Lab GitHub](https://github.com/whartonlearninglab)

<!--
https://twitter.com/m_holtermann/status/1139264917008257031 | Markus Holtermann @ #LeadDevLondon on Twitter: "Do I know somebody at @eventbrite, @instagram, @NASA, @Pinterest, or @washingtonpost? Can you confirm (or deny) that you're still using (parts of) @djangoproject? #Django"

http://www.spokesman.com/staff/
http://www.spokesman.com/stories/2017/aug/14/what-the-web-a-family-owned-newspaper-and-a-silent/
-->



<!--
lyftvm

mergebot

https://engineering.linkedin.com/blog/2020/continuous-integration
https://eng.lyft.com/announcing-omnibot-a-slack-proxy-and-slack-bot-framework-d4e32dd85ee4

Carl Meyer talk
https://www.youtube.com/watch?v=lx5WQjXLlq8 | Carl Meyer about Django @ Instagram at Django: Under The Hood 2016 - YouTube
Talks

https://www.youtube.com/watch?v=ZYD9yyMh9Hk | Stephen Simmons, Neil Slinger python at massive scale - Google Search
https://www.youtube.com/watch?v=H4SS9yVWJYA | Jason Fried - Fighting the Good Fight: Python 3 in your organization - PyCon 2018 - YouTube

Python 3 at Facebook 
https://lwn.net/Articles/758159/
https://www.youtube.com/watch?v=H4SS9yVWJYA

https://engineering.linkedin.com/blog/2020/how-we-retired-python-2-and-improved-developer-happiness
https://blogs.dropbox.com/tech/2018/09/how-we-rolled-out-one-of-the-largest-python-3-migrations-ever/ | How we rolled out one of the largest Python 3 migrations ever | Dropbox Tech Blog

https://www.youtube.com/watch?v=lx5WQjXLlq8&
https://speakerdeck.com/carljm/instagram-under-the-hood
https://blog.disqus.com/scaling-django-to-8-billion-page-views
https://engineering.instagram.com/performance-usage-at-instagram-d2ba0347e442
https://medium.com/@kellan/towards-an-understanding-of-technical-debt-ae0f97cc0553#.fjosw93rm

https://opensource.googleblog.com/2018/08/how-we-brought-latest-python-to-app-engine.html | How we brought the latest version of Python to App Engine and Cloud Functions | Google Open Source Blog
-->

## General Talks

<!--
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

## Software Engineering

Software Project Management
* [Software Project Management Wikipedia](http://en.wikipedia.org/wiki/Software_project_management)

Software Engineering/Development 
* [Software Engineering Wikipedia](https://en.wikipedia.org/wiki/Software_engineering) 
* [History of Software Engineering Wikipedia](https://en.wikipedia.org/wiki/History_of_software_engineering) 
* [Outline of Software Engineering Wikipedia](https://en.wikipedia.org/wiki/Outline_of_software_engineering)
* [Guide to the Software Engineering Body of Knowledge](http://www.computer.org/web/swebok/v3) and [Guide to the Software Engineering Body of Knowledge Wikipedia](https://en.wikipedia.org/wiki/Software_Engineering_Body_of_Knowledge)
* [Software Development Wikipedia](http://en.wikipedia.org/wiki/Software_development) 

## Requirements and Planning

Requirements
* [Product Requirements Document Wikipedia](http://en.wikipedia.org/wiki/Product_requirements_document)
* [Requirement Wikipedia](https://en.wikipedia.org/wiki/Requirement)
* [Business Requirements Wikipedia](https://en.wikipedia.org/wiki/Business_requirements)
* [Functional Requirement Wikipedia](https://en.wikipedia.org/wiki/Functional_requirement)
* [Non-Functional Requirement Wikipedia](https://en.wikipedia.org/wiki/Non-functional_requirement)
* [Specification Wikipedia](https://en.wikipedia.org/wiki/Specification_(technical_standard))
* [Functional Specification Wikipedia](https://en.wikipedia.org/wiki/Functional_specification)
* [Requirement Analysis Wikipedia](https://en.wikipedia.org/wiki/Requirements_analysis)
* [Requirement Prioritization Wikipedia](https://en.wikipedia.org/wiki/Requirement_prioritization)
* [Requirement Management Wikipedia](http://en.wikipedia.org/wiki/Requirements_management)

<!--
Requirements baseline
https://en.wikipedia.org/wiki/Baseline_(configuration_management)
-->

Technical
* [Software Prototyping Wikipedia](http://en.wikipedia.org/wiki/Software_prototyping) 
* [Proof of Concept Wikipedia](https://en.wikipedia.org/wiki/Proof_of_concept)
* [Technology Roadmap Wikipedia](http://en.wikipedia.org/wiki/Technology_roadmap)
* [Solution Architecture Wikipedia](https://en.wikipedia.org/wiki/Solution_architecture)
* Objective, Assumption, Constraint

## Software Life Cycle and Release Management

Interesting!
Software Development Philosophies and Process
* [List of Software Development Philosophies Wikipedia](https://en.wikipedia.org/wiki/List_of_software_development_philosophies) 
* [Software Development Process (Series) Wikipedia](https://en.wikipedia.org/wiki/Software_development_process) 

Life Cycles
* [Product Life Cycle Management Wikipedia](https://en.wikipedia.org/wiki/Product_life-cycle_management_(marketing))
* [Systems Development Life Cycle Wikipedia](https://en.wikipedia.org/wiki/Systems_development_life_cycle)
* [Technology Adoption Life Cycle Wikipedia](https://en.wikipedia.org/wiki/Technology_adoption_life_cycle)

## General Python and Django Links

Python Official Tutorial
* [Python Official Tutorial](https://docs.python.org/3/tutorial/) 

Django Tutorials (Official, Mozilla Developer Network and SIBTC) 
* [Django Official Tutorial](https://docs.djangoproject.com/en/2.0/intro/tutorial01)

Django Install
* [Django Install](https://docs.djangoproject.com/en/dev/topics/install)

Python Style
* [PEP 0008 Style Guide for Python Code](https://www.python.org/dev/peps/pep-0008) and [PEP 0008 Style Guide for Python Code .txt](https://hg.python.org/peps/file/tip/pep-0008.txt)
* [PEP 0257 Doc String Conventions](https://www.python.org/dev/peps/pep-0257)

Django Coding Style Guide
* [Django Coding Style Guide](https://docs.djangoproject.com/en/dev/internals/contributing/writing-code/coding-style)

Django JavaScript Style Guide
* [Django JavaScript Style Guide](https://docs.djangoproject.com/en/dev/internals/contributing/writing-code/javascript)

Django Views
* [Class-Based Views](https://docs.djangoproject.com/en/dev/topics/class-based-views/)

Django ORM
* [Queries](https://docs.djangoproject.com/en/dev/topics/db/queries)

<!--
https://docs.djangoproject.com/en/2.2/ref/request-response/ | Request and response objects | Django documentation | Django
https://docs.djangoproject.com/en/2.2/_modules/django/http/request/ | django.http.request | Django documentation | Django

https://docs.djangoproject.com/en/dev/_modules/django/http/request/#HttpRequest
https://docs.djangoproject.com/en/dev/ref/request-response/#jsonresponse-objects

https://docs.djangoproject.com/en/2.1/ref/request-response/#django.http.HttpRequest.GET
https://docs.djangoproject.com/en/1.11/ref/request-response/#django.http.HttpRequest.POST
https://docs.djangoproject.com/en/1.11/ref/request-response/#django.http.QueryDict
-->

Python- Django- Rest Framework (Including Authentication and Generic Views)
* [Django Rest Framework](http://www.django-rest-framework.org) and [Django Rest Framework GitHub](https://github.com/encode/django-rest-framework) 
* [Django Rest Framework Authentication](http://www.django-rest-framework.org/api-guide/authentication)  
* [Django Rest Framework Generic Views](http://www.django-rest-framework.org/api-guide/generic-views)  

Django Architecture and Scaling
* [Shared-Nothing Architecture Wikipedia](https://en.wikipedia.org/wiki/Shared-nothing_architecture)
* [Does Django Scale?](https://docs.djangoproject.com/en/dev/faq/general/#does-django-scale)
* [Django Design Philosophies](https://docs.djangoproject.com/en/dev/misc/design-philosophies)

## Python Non-Official Styleguides and Code Formatting

Style
* [Coding Conventions Wikipedia](https://en.wikipedia.org/wiki/Coding_conventions)
* [Programming Style Wikipedia](https://en.wikipedia.org/wiki/Programming_style)

Python- Kenneth Reitz Contributor's Guide and Style Guides
* [Kenneth Reitz: The Hitchhiker’s Guide to Python! Code Style](http://docs.python-guide.org/en/latest/writing/style)

Python- Style Guides
* [Google Python Style Guide](https://google.github.io/styleguide/pyguide.html)
* [Khan Academy Python Style Guide Python](https://github.com/Khan/style-guides/blob/master/style/python.md)
* [The Chromium Project Python Style Guide](https://www.chromium.org/chromium-os/python-style-guidelines)

<!--
https://docs.python-guide.org/#writing-great-python-code
-->

Python- PEP 8
* [Kenneth Reitz: PEP 8 — the Style Guide for Python](http://pep8.org) and [Kenneth Reitz: PEP 8 — the Style Guide for Python GitHub](https://github.com/kennethreitz/pep8.org)

## To Read- Release Management

Django
* [Django: How to write reusable apps](https://docs.djangoproject.com/en/2.0/intro/reusable-apps).

Python Docs- Packaging
* [Distributing Python Modules](https://docs.python.org/3/distributing/index.html)

Python- Official Packaging Info
* [Sample Project](https://github.com/pypa/sampleproject)
* [Python Packaging User Guide](https://packaging.python.org)
* [Python Packaging Tutorials](https://packaging.python.org/tutorials) 
* [Python Packaging Guides](https://packaging.python.org/guides) 
* [Python Packaging Projects Tutorial](https://packaging.python.org/tutorials/packaging-projects)  

<!--
https://docs.djangoproject.com/en/dev/internals/contributing/

Working through
https://realpython.com/cpython-source-code-guide/ | Your Guide to the CPython Source Code – Real Python

https://www.python.org/dev/peps/pep-0602/
https://devguide.python.org/
https://devguide.python.org/#contributing | Python Developer’s Guide — Python Developer's Guide
https://devguide.python.org/devcycle/
-->

## Python Release

<!--
Python release

Python
https://lwn.net/Articles/819853/
https://www.python.org/dev/peps/pep-0596/ | PEP 596 -- Python 3.9 Release Schedule | Python.org

https://mail.python.org/archives/list/python-committers@python.org/message/JFBZ7OHPQLHBYDCGGLG554JBXWGTKT23/ | Mailman 3 [python-committers] [RELEASE] Python 3.9.0b3 is now available for testing - python-committers - python.org
https://twitter.com/pyblogsal/status/1271115432590807041 | __qualname__ on Twitter: "Ah, don't you love the sound of 11630 lines of code that disappear at the same time? The old parser is dead! Long live the new parser!! https://t.co/xU9vTdxi0r" / Twitter

https://twitter.com/gvanrossum/status/1255164435502489600 | Guido van Rossum on Twitter: "Python 3.9a6 is out! With new parser (PEP 617), dict|dict (PEP 584), list[int] (PEP 585), str.remove{prefix,suffix}() (PEP 616), and much more! Please test with your favorite packages. https://t.co/jhJ24UBGrw" / Twitter

https://docs.python.org/3.9/whatsnew/3.9.html | What’s New In Python 3.9 — Python 3.9.0a6 documentation
https://www.python.org/downloads/release/python-390a5/

https://www.python.org/download/pre-releases/

Django What’s New
https://www.youtube.com/watch?v=_BBNVFirvTY&feature=youtu.be | What's New In Django 3.0 - YouTube

Django Security
https://twitter.com/djangoproject/status/1207234611098607616 | Django on Twitter: "Django security releases issued: 3.0.1, 2.2.9, and 1.11.27 https://t.co/

https://docs.djangoproject.com/en/dev/releases/3.1/
https://www.djangoproject.com/weblog/2020/apr/01/bugfix-releases/
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

virtualenv
https://github.com/gaborbernat/virtualenv-rewrite-eupy20 | gaborbernat/virtualenv-rewrite-eupy20

pip
https://blog.python.org/2020/07/upgrade-pip-20-2-changes-20-3.html | Python Insider: Upgrade to pip 20.2, plus, changes coming in 20.3

pip
https://twitter.com/ChangesetLLC/status/1291062082574704649 | Changeset Consulting on Twitter: "There is a big change coming to pip in October -- a watershed moment, a minor revolution. It'll be a great foundation for making it easier to deal with #Python packaging. This is a thread where I'll share some of the stuff @ThePyPA can build on that foundation. https://t.co/JGqVy21Dnp" / Twitter

beta pip
https://mobile.twitter.com/ThePyPA/status/1252641910679879681

pip Resolver
https://mobile.twitter.com/metalikus/status/1251497611028238336

https://modelpredict.com/python-dependency-management-tools | Overview of python dependency management tools | model.predict

https://hynek.me/articles/python-app-deps-2018/

pip/virtualenv
export PIP_REQUIRE_VIRTUALENV=true
https://github.com/pypa/pip/commit/301dc3176fa40c3f6a233fccc131f3981bfbe48b

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


## Structuring Your Python Project

Kenneth Reitz- Sample Project Structure, Sample Module, and setup.py
* [Kenneth Reitz: Structuring Your Project](http://docs.python-guide.org/en/latest/writing/structure)
* [Sample Module for The Hitchhiker’s Guide to Python! GitHub](https://github.com/kennethreitz/samplemod) and [Sample Module Docs](https://github.com/kennethreitz/samplemod/tree/master/docs)
* [Repository Structure and Python](https://www.kennethreitz.org/essays/repository-structure-and-python)
* [A Human's Ultimate Guide to setup.py GitHub](https://github.com/kennethreitz/setup.py)

## Django Project Structure

Python- Django- Project Stucture
* [RevSys Recommended Django Project Layout](http://www.revsys.com/blog/2014/nov/21/recommended-django-project-layout)
* [SIBTC Starting a New Django 1.8 Project](http://simpleisbetterthancomplex.com/2015/11/30/starting-a-new-django-18-project.html)

## Django Classy

Django Classy
* [Classy Class-Based Views](http://ccbv.co.uk)
* [Classy Django Forms](http://cdf.9vo.lt) and [Classy Django Forms GitHub](https://github.com/ana-balica/classy-django-forms)
* [Classy Django REST Framework](http://cdrf.co) and [Classy Django REST Framework GitHub](https://github.com/vintasoftware/classy-django-rest-framework)

## Common Django Features

<!--
http://django-vanilla-views.org/ | Django Vanilla Views - Beautifully simple class based views
https://github.com/tomchristie/django-vanilla-views | tomchristie/django-vanilla-views: Beautifully simple class-based views.

http://www.discoversdk.com/blog/understanding-the-request-response-lifecycle-of-a-django-web-application | Understanding the request-response lifecycle of a Django web application | DiscoverSDK Blog

Django Request and Response Cycle
* [Django Request and Response Cycle](http://rnevius.github.io/django_request_response_cycle.png)
-->

## Django Performance, Optimization, Deployment, Architecture

<!--
https://djangobook.com/deploying-django/
-->

## Django Twelve Factor

<!--
https://12factor.net/config | The Twelve-Factor App

https://github.com/doismellburning/django12factor | doismellburning/django12factor: Making Django configuration more 12factor-y
-->


## Debugging

Debugging
* [Software Bug Wikipedia](https://en.wikipedia.org/wiki/Software_bug)
* [Debugger Wikipedia](https://en.wikipedia.org/wiki/Debugger)

## Testing Terminology

* [Test Case Wikipedia](https://en.wikipedia.org/wiki/Test_case)
* [Mock Object Wikipedia](https://en.wikipedia.org/wiki/Mock_object)
* [Test Stub Wikipedia](https://en.wikipedia.org/wiki/Test_stub)
* [Test Fixture Wikipedia](https://en.wikipedia.org/wiki/Test_fixture)

## Types of Software Testing

Software Testing
* [Test Automation Wikipedia](https://en.wikipedia.org/wiki/Test_automation)
* [Software Testing Wikipedia](https://en.wikipedia.org/wiki/Software_testing)

Functional and Unit Testing
* [Functional Testing Wikipedia](https://en.wikipedia.org/wiki/Functional_testing)
* [Unit Testing Wikipedia](https://en.wikipedia.org/wiki/Unit_testing)

Other Types of Testing- Performance/Stress
* [Software Performance Testing Wikipedia](https://en.wikipedia.org/wiki/Software_performance_testing)
* [Regression Testing Wikipedia](https://en.wikipedia.org/wiki/Regression_testing)
* [Stress Testing Wikipedia](https://en.wikipedia.org/wiki/Stress_testing_(software))
* [Load Testing Wikipedia](https://en.wikipedia.org/wiki/Load_testing)

Other Types of Testing- Acceptance
* [Acceptance Testing Wikipedia](https://en.wikipedia.org/wiki/Acceptance_testing)
* [Operational Acceptance Testing Wikipedia](https://en.wikipedia.org/wiki/Operational_acceptance_testing)

Other Types of Testing
* [Agile Testing Wikipedia](https://en.wikipedia.org/wiki/Agile_testing)
* [System Integration Testing Wikipedia](https://en.wikipedia.org/wiki/System_integration_testing)
* [System Testing Wikipedia](https://en.wikipedia.org/wiki/System_testing)
* [Integration Testing Wikipedia](https://en.wikipedia.org/wiki/Integration_testing)
* [Smoke Testing Wikipedia](https://en.wikipedia.org/wiki/Smoke_testing_(software))
* [Mutation Testing Wikipedia](https://en.wikipedia.org/wiki/Mutation_testing)

Other Types of Testing
* [Software Performance Testing Wikipedia](https://en.wikipedia.org/wiki/Software_performance_testing)

## Python Testing

Python and Django Debugging
* [bdb](https://docs.python.org/3/library/bdb.html)
* [pdb](https://docs.python.org/3/library/pdb.html)

Python Testing Built-In Tools
* [unittest](https://docs.python.org/3/library/unittest.html)
* [unittest.mock](https://docs.python.org/3/library/unittest.mock.html)
* [doctest](https://docs.python.org/3/library/doctest.html)
* [mock](https://docs.python.org/dev/library/unittest.mock.html)

### pytest and Selenium

pytest 
* [pytest](http://pytest.org) and [pytest Docs](https://docs.pytest.org/en/latest)

Selenium
* [Selenium](http://www.seleniumhq.org)
* [Selenium WebDriver](https://www.seleniumhq.org/projects/webdriver/)

<!--
Test automation
https://en.wikipedia.org/wiki/Headless_browser

https://martinfowler.com/bliki/PageObject.html
https://selenium-python.readthedocs.io/page-objects.html
https://github.com/SeleniumHQ/selenium/wiki/PageObjects
https://github.com/SeleniumHQ/selenium/wiki/Design-Patterns

https://pypi.org/project/selenium/ | selenium · PyPI
https://github.com/SeleniumHQ/selenium/tree/master/py/selenium/webdriver | selenium/py/selenium/webdriver at master · SeleniumHQ/selenium

https://pythontesting.net/framework/pytest/pytest-introduction/

https://docs.pytest.org/en/latest/ | pytest: helps you write better programs — pytest documentation

https://docs.pytest.org/en/latest/contents.html#toc | Full pytest documentation — pytest documentation
https://docs.pytest.org/en/latest/reference.html | Reference — pytest documentation

https://docs.pytest.org/en/latest/goodpractices.html | Good Integration Practices — pytest documentation

https://docs.pytest.org/en/latest/getting-started.html | Installation and Getting Started — pytest documentation
https://docs.pytest.org/en/latest/unittest.html#unittest | unittest.TestCase Support — pytest documentation

https://docs.pytest.org/en/latest/example/parametrize.html
https://docs.pytest.org/en/latest/parametrize.html

https://docs.pytest.org/en/latest/assert.html#assert
https://www.mattcrampton.com/blog/a_list_of_all_python_assert_methods/
https://twitter.com/pytestdotorg/status/1101959314116210688 | pytest.org on Twitter: "Yes, memorize 30 methods' names and exactly how to call them....... Or learn the assert statement, pytest.raises, and the methods on the data structures you're already using. 🤷… https://t.co/wllbH3vDE3"
https://twitter.com/KokkasKostas/status/1100738165571244034 | Kostas Kokkas on Twitter: "List of assertions used in Python unittesting: https://t.co/BbtOvEKXQ7 #pytest #unittest #DataScience #DataAnalytics #python"
-->

### Django Testing

Django Testing- Official
* [Django Testing Overview](https://docs.djangoproject.com/en/dev/topics/testing/overview)
* [Django Testing](https://docs.djangoproject.com/en/dev/topics/testing)
* [Django Testing Tools](https://docs.djangoproject.com/en/dev/topics/testing/tools)
* [Django Testing Advanced Topics](https://docs.djangoproject.com/en/dev/topics/testing/advanced)

<!--
https://docs.djangoproject.com/en/3.0/topics/testing/advanced/#using-different-testing-frameworks | Advanced testing topics | Django documentation | Django
https://docs.djangoproject.com/en/2.2/topics/testing/tools/#testcase | Testing tools | Django documentation | Django
https://docs.python.org/3/library/unittest.html#unittest.TestCase | unittest — Unit testing framework — Python 3.8.1 documentation

https://docs.python.org/3/library/unittest.html#assert-methods
https://docs.python.org/3/library/unittest.html#unittest.TestCase.assertEqual | unittest — Unit testing framework — Python 3.8.1 documentation
https://docs.python.org/3/library/unittest.html#unittest.TestCase.assertNotEqual
https://docs.python.org/3/library/unittest.html#unittest.TestCase.assertRaises

https://docs.djangoproject.com/en/2.2/topics/testing/tools/#django.test.TransactionTestCase | Testing tools | Django documentation | Django
https://docs.djangoproject.com/en/3.0/topics/checks/ | System check framework | Django documentation | Django


https://docs.djangoproject.com/en/dev/internals/contributing/writing-code/javascript/#javascript-tests | JavaScript | Django documentation | Django
-->

## Django- Important Topics

### Django Core Dev Security

* [Django Security](https://docs.djangoproject.com/en/dev/releases/security/)
* [How Django Discloses Security Issues](https://docs.djangoproject.com/en/dev/internals/security/#how-django-discloses-security-issues)

### Django Security

* [Clickjacking Protection](https://docs.djangoproject.com/en/dev/ref/clickjacking/)
* [HTTP Strict Transport Security](https://docs.djangoproject.com/en/dev/ref/middleware/#http-strict-transport-security)
* [Security Middleware](https://docs.djangoproject.com/en/dev/ref/middleware/#django.middleware.security.SecurityMiddleware)

### Django Performance, Optimization, Deployment

Django Performance and Optimization
* [Django Performance](https://docs.djangoproject.com/en/dev/topics/performance)
* [Django Database Access Optimization](https://docs.djangoproject.com/en/dev/topics/db/optimization)

Django Deployment
* [Deployment Checklist](https://docs.djangoproject.com/en/dev/howto/deployment/checklist)

### Security

Security- General
* [Security- Computer Security Wikipedia](https://en.wikipedia.org/wiki/Security#Computer_security)
* [Computer Security Wikipedia](https://en.wikipedia.org/wiki/Computer_security)
* [Information Security Wikipedia](https://en.wikipedia.org/wiki/Information_security)
* [Threat Model Wikipedia](https://en.wikipedia.org/wiki/Threat_model)
* [Penetration Test Wikipedia](https://en.wikipedia.org/wiki/Penetration_test)

OWASP
* [OWASP](https://www.owasp.org/index.php/Main_Page) and [OWASP GitHub](https://github.com/OWASP)
* [OWASP Cheat Sheet Series](https://www.owasp.org/index.php/OWASP_Cheat_Sheet_Series) and [OWASP Cheat Sheet Series GitHub](https://github.com/OWASP/CheatSheetSeries)

Top Ten
* [OWASP Top Ten Cheat Sheet GitHub](https://github.com/OWASP/Top10)

<!--
## Security- General
      
https://developers.google.com/web/fundamentals/security/

https://www.owasp.org/index.php/Category:OWASP_Top_Ten_Project | Category:OWASP Top Ten Project - OWASP

Application Security Verification Standard
https://github.com/OWASP/ASVS/tree/master/4.0/en | ASVS/4.0/en at master · OWASP/ASVS

https://www.owasp.org/index.php/OWASP_Testing_Guide_v4_Table_of_Contents | OWASP Testing Guide v4 Table of Contents - OWASP

https://www.owasp.org/index.php/Application_Threat_Modeling | Application Threat Modeling - OWASP
-->

<!--
https://www.owasp.org/index.php/Category:Attack
   
https://www.owasp.org/index.php/Top_10-2017_Top_10 | Top 10-2017 Top 10 - OWASP
https://www.owasp.org/images/7/72/OWASP_Top_10-2017_%28en%29.pdf.pdf | OWASP Top 10 - 2017

https://www.owasp.org/index.php/OWASP_Serverless_Top_10_Project | OWASP Serverless Top 10 Project - OWASP
https://github.com/OWASP/DVSA | OWASP/DVSA: a Damn Vulnerable Serverless Application

https://teamtreehouse.com/library/owasp-top-10-vulnerabilities | OWASP Top 10 Vulnerabilities Course

[Using CORS](https://www.html5rocks.com/en/tutorials/cors/)

https://www.owasp.org/index.php/OWASP_SAMM_Project | OWASP SAMM Project - OWASP
-->

### Security Model

Computer Security Model
* [Computer Security Model Wikipedia](https://en.wikipedia.org/wiki/Computer_security_model)

Types
* [Same Origin Policy Wikipedia](https://en.wikipedia.org/wiki/Same-origin_policy)
* [Content Security Policy Wikipedia](https://en.wikipedia.org/wiki/Content_Security_Policy)

Same Origin
* [Same-Origin Policy](https://developer.mozilla.org/en-US/docs/Web/Security/Same-origin_policy)
* [Google HTTP Access Control (CORS)](https://developer.mozilla.org/en-US/docs/Web/HTTP/Access_control_CORS)

Content Security Policy (CSP)
* [Google Content Security Policy (CSP)](https://developers.google.com/web/fundamentals/security/csp) and [Mozilla Content Security Policy (CSP)](https://developer.mozilla.org/en-US/docs/Web/HTTP/CSP)

Mixed Content
* [Google What Is Mixed Content?](https://developers.google.com/web/fundamentals/security/prevent-mixed-content/what-is-mixed-content) and [Google Preventing Mixed Content](https://developers.google.com/web/fundamentals/security/prevent-mixed-content/fixing-mixed-content)

### Security Risk

High
* [Arbitrary Code Execution Wikipedia](https://en.wikipedia.org/wiki/Arbitrary_code_execution)
* [SQL Injection Wikipedia](https://en.wikipedia.org/wiki/SQL_injection)

Medium
* [Cross-Site Scripting Wikipedia](https://en.wikipedia.org/wiki/Cross-site_scripting)
* [Cross-Site Request Forgery Wikipedia](https://en.wikipedia.org/wiki/Cross-site_request_forgery)
* [Denial of Service Attack Wikipedia](https://en.wikipedia.org/wiki/Denial-of-service_attack)

<!--
Medium
Broken authentication

Low
Sensitive data exposure
Broken session management
Unvalidated redirects/forwards
Issues requiring an uncommon configuration option

https://en.wikipedia.org/wiki/Clickjacking
https://en.wikipedia.org/wiki/Code_injection

https://en.wikipedia.org/wiki/Fully_qualified_domain_name | Fully qualified domain name - Wikipedia

https://www.owasp.org/index.php/SQL_Injection
https://www.owasp.org/index.php/Cross-site_Scripting_(XSS)
https://www.owasp.org/index.php/Cross-Site_Request_Forgery_(CSRF) | Cross-Site Request Forgery (CSRF) - OWASP
https://www.owasp.org/index.php/Denial_of_Service
https://www.owasp.org/index.php/HttpOnly | HttpOnly - OWASP

Prevention
https://www.owasp.org/index.php/Injection_Prevention_Cheat_Sheet | Injection Prevention Cheat Sheet - OWASP
https://www.owasp.org/index.php/Cross-Site_Request_Forgery_(CSRF)_Prevention_Cheat_Sheet | Cross-Site Request Forgery (CSRF) Prevention Cheat Sheet - OWASP

JavaScript
https://www.owasp.org/index.php/3rd_Party_Javascript_Management_Cheat_Sheet
https://www.owasp.org/index.php/AJAX_Security_Cheat_Sheet
-->

## Performance

Python Time Complexity, Performance
* [Python Time Complexity](https://wiki.python.org/moin/TimeComplexity)
* [Python Speed](https://wiki.python.org/moin/PythonSpeed)
* [Python Performance Tips](https://wiki.python.org/moin/PythonSpeed/PerformanceTips)

Python Benchmarking and Profiling
* [profile](https://docs.python.org/3/library/profile.html)
* [timeit](https://docs.python.org/3/library/timeit.html)

Diagnostic tools
* hotshot module?
* cProfile module

<!--
http://scipy.github.io/old-wiki/pages/PerformancePython

27.4. The Python Profilers
https://docs.python.org/3/library/profile.html#module-pstats

https://docs.python.org/3/library/profile.html#introduction-to-the-profilers
https://docs.python.org/3/library/profile.html#instant-user-s-manual
https://docs.python.org/3/library/profile.html#what-is-deterministic-profiling
https://docs.python.org/3/library/profile.html#limitations
https://docs.python.org/3/library/profile.html#calibration
https://docs.python.org/3/library/profile.html#using-a-custom-timer

27.5. timeit — Measure execution time of small code snippets
https://docs.python.org/3/library/timeit.html#basic-examples
https://docs.python.org/3/library/timeit.html#python-interface
https://docs.python.org/3/library/timeit.html#command-line-interface
https://docs.python.org/3/library/timeit.html#examples

https://wiki.python.org/moin/PythonSpeed/Profiling
http://web.archive.org/web/20060506162444/http://wingware.com/doc/howtos/performance-profiling-python-code

10.10. Performance Measurement
https://docs.python.org/3/tutorial/stdlib.html#performance-measurement
10.11. Quality Control
https://docs.python.org/3/tutorial/stdlib.html#quality-control

https://numba.pydata.org/

https://en.wikipedia.org/wiki/Schwartzian_transform
https://wiki.python.org/moin/DecorateSortUndecorate

https://wiki.python.org/moin/ConcatenationTestCode

https://docs.python.org/3/library/sys.html#sys.setcheckinterval
-->

## Python Profiling

<!--
https://knasmueller.net/measure-code-execution-time-accurately-in-python

Python Profiling 

Third Party Testing and Profiling

https://pypi.org/project/memory-profiler/ | memory-profiler · PyPI

https://engineering.instagram.com/profiling-cpython-at-instagram-89d4cbeeb898 | Profiling CPython at Instagram – Instagram Engineering

https://github.com/uber/pyflame | uber/pyflame: 🔥 Pyflame: A Ptracing Profiler For Python
https://zapier.com/engineering/profiling-python-boss/ | Profiling Python Like a Boss - The Zapier Engineering Blog | Zapier
https://www.pluralsight.com/guides/python/quick-profiling-in-python | Quick profiling in Python (Example) | hack.guides()
https://jvns.ca/blog/2017/12/17/how-do-ruby---python-profilers-work-/ | How do Ruby & Python profilers work? - Julia Evans
http://www.integralist.co.uk/posts/profiling-python/ | Profiling Python ⋆ Mark McDonnell
-->

<!--
https://medium.freecodecamp.org/django-performance-optimization-looking-for-the-bottlenecks-8583789e341b | Django Performance Optimization: The Search for Bottlenecks
-->


<!--
Python security
https://github.com/guardrailsio/awesome-python-security | guardrailsio/awesome-python-security: Awesome Python Security resources 🕶🐍🔐

https://hynek.me/articles/document-your-tests/

https://jvns.ca/perf-cheat-sheet.pdf | perf-cheat-sheet.pdf

https://en.wikipedia.org/wiki/Benchmark_(computing) | Benchmark (computing) - Wikipedia
https://en.wikipedia.org/wiki/Comparison_of_instruction_set_architectures | Comparison of instruction set architectures - Wikipedia

https://blogs.msdn.microsoft.com/ie/2010/09/14/performance-what-common-benchmarks-measure/ | Performance: What Common Benchmarks Measure – IEBlog

Telemetry
https://en.wikipedia.org/wiki/Telemetry


Testing

https://testdriven.io/blog/deploying-django-to-digitalocean-with-docker-and-github-actions/

https://www.atlassian.com/continuous-delivery/software-testing/types-of-software-testing | The different types of testing in Software | Atlassian

https://www.blog.pythonlibrary.org/2020/04/14/an-overview-of-profiling-tools-for-python/


brian okken - Google Search

Test Anything Protocol

PyTest
https://twitter.com/mblayman/status/1222200715570970624 | Matt Layman on Twitter: "I released a new version of pytest-tap today that let's you use the Test Anything Protocol (TAP) for #pytest. This version drops support for Python 2. https://t.co/Mm7fKz0Gfg" / Twitter

https://medium.com/javascript-scene/what-every-unit-test-needs-f6cd34d9836d | 5 Questions Every Unit Test Must Answer - JavaScript Scene - Medium
https://medium.com/javascript-scene/testing-software-what-is-tdd-459b2145405c | Testing Software: What is TDD? - JavaScript Scene - Medium

https://testdriven.io/ | Test Driven Development Courses

https://testautomationu.applitools.com/ | Test Automation University | Applitools
https://testautomationu.applitools.com/python-tutorial/
https://testautomationu.applitools.com/selenium-webdriver-python-tutorial/ | Selenium WebDriver with Python

https://automationpanda.com/2018/08/02/egad-how-do-we-start-writing-better-tests/
https://automationpanda.com/2018/05/21/the-pandas-dozen-top-pycon-2018-talks/
https://speakerdeck.com/pycon2018?page=2
https://automationpanda.com/speaking/
https://twitter.com/AutomationPanda/status/1226591212632596480
https://automationpanda.com/tag/development/

https://www.b-list.org/weblog/2017/apr/03/testing-django-apps/ | Let's talk about testing Django apps
https://lincolnloop.com/blog/using-setuppy-your-django-project/ | Using setup.py in Your (Django) Project | Lincoln Loop
https://www.ericholscher.com/blog/2009/jun/29/enable-setuppy-test-your-django-apps/ | Enable setup.py test in your Django apps — Eric Holscher - Surfing in Kansas
-->


## Testing

<!--
TestPyramid

"Write integration tests for all pieces of code where you either serialize or deserialize data. This happens more often than you might think. Think about:

Calls to your services' REST API
Reading from and writing to databases
Calling other application's APIs
Reading from and writing to queues
Writing to the filesystem"

Debugging
https://twitter.com/b0rk/status/1144011000208863239 | 🔎Julia Evans🔍 on Twitter: "amazing debugger features… "
https://twitter.com/b0rk/status/1145350304583622656 | 🔎Julia Evans🔍 on Twitter: "how I got better at debugging… "
https://jvns.ca/blog/2019/06/23/a-few-debugging-resources/ | What does debugging a program look like? - Julia Evans
https://twitter.com/b0rk/status/1143509975492374528 | 🔎Julia Evans🔍 on Twitter: "more assumptions to check while debugging (see https://t.co/nhLOmiVkJJ for more like this)… "
https://twitter.com/andrewgodwin/status/1147272951118483457

https://pythontesting.net/agile/test-first-programming/
http://www.extremeprogramming.org/rules/testfirst.html
https://martinfowler.com/bliki/SelfTestingCode.html
https://martinfowler.com/bliki/TestDrivenDevelopment.html
https://learntdd.in/concepts.html

https://en.wikipedia.org/wiki/Scenario_testing
https://martinfowler.com/articles/mocksArentStubs.html
https://thoughtbot.com/blog/i-mock-your-fixtures-too

state behavior versus behavior verification
https://en.wikipedia.org/wiki/Mock_object#Use_in_test-driven_development
-->

## Python and Django Testing and Debugging Tools- Most Relevant Third Party Testing Tools (Besides pytest and Selenium)

Django
* [pytest-django PyPi](https://pypi.python.org/pypi/pytest-django) and [pytest-django Read the Docs](http://pytest-django.readthedocs.org)

PyLint
* [Pylint](https://www.pylint.org) and [Pylint GitHub](https://github.com/PyCQA/pylint)

Pylint Django
* [Pylint Django GitHub](https://github.com/PyCQA/pylint-django)

Django Test Plus
* [Django Test Plus](http://django-test-plus.readthedocs.io) and [Django Test Plus GitHub](https://github.com/revsys/django-test-plus)

Python- Django- Debug Toolbar an dPanel
* [Django Debug Toolbar PyPi](https://pypi.python.org/pypi/django-debug-toolbar) 
* [Django Debug Panel GitHub](https://github.com/recamshak/django-debug-panel) and [Django Debug Panel Chrome Web Store](https://chrome.google.com/webstore/detail/django-debug-panel/nbiajhhibgfgkjegbnflpdccejocmbbn)
* [Django Debug Toolbar Read the Docs](http://django-debug-toolbar.readthedocs.org) and [Django Debug Toolbar GitHub](https://github.com/jazzband/django-debug-toolbar)

<!--
https://pypi.org/project/pytest-freezegun/ | pytest-freezegun · PyPI
https://github.com/spulec/freezegun | spulec/freezegun: Let your Python tests travel through time

https://github.com/behave/behave | behave/behave: BDD, Python style.
https://hypothesis.readthedocs.io/en/latest/
https://github.com/HypothesisWorks/hypothesis| HypothesisWorks/hypothesis: Hypothesis is a powerful, flexible, and easy to use library for property-based testing.
https://cucumber.io/ | Cucumber
https://github.com/cucumber/gherkin-python

https://www.revsys.com/tidbits/pytest-support-django-test-plus/ | pytest support for django-test-plus

https://django-test-plus.readthedocs.io/en/latest/usage.html | Usage — django-test-plus 1.0.9 documentation

https://testautomationu.applitools.com/
https://testautomationu.applitools.com/unit-testing/ | Overview
https://testautomationu.applitools.com/learningpaths.html?id=web-ui-python-path

Testing pyramid
https://automationpanda.com/2018/08/01/the-testing-pyramid/
https://automationpanda.com/bdd/
https://automationpanda.com/python/

https://www.packtpub.com/web-development/pytest-quick-start-guide
https://pragprog.com/book/bopytest/python-testing-with-pytest | Python Testing with pytest: Simple, Rapid, Effective, and Scalable by Brian Okken | The Pragmatic Bookshelf

https://github.com/augustogoulart/awesome-pytest | augustogoulart/awesome-pytest: A curated list of awesome pytest resources

http://pythontesting.net/start-here/
https://pythontesting.net/framework/pytest/pytest-introduction/
http://docs.python-guide.org/en/latest/writing/tests/ | Testing Your Code — The Hitchhiker's Guide to Python
-->

<!--
Beyond Unit Tests
https://www.youtube.com/watch?v=Z9ghRBEgnps&t=257s
https://github.com/AndyLPK247/djangocon-2019-web-ui-testing

https://automationpanda.com/2018/10/29/pygotham-2018-reflections/ | PyGotham 2018 Reflections | Automation Panda
https://2018.pygotham.org/talks/egad-how-do-we-start-writing-better-tests/ | Egad! How Do We Start Writing (Better) Tests? - PyGotham 2018
https://automationpanda.com/2018/08/02/egad-how-do-we-start-writing-better-tests/ | EGAD! How Do We Start Writing (Better) Tests? | Automation Panda
https://www.youtube.com/watch?v=z0XC0tGGFXI | Egad! How Do We Start Writing Better Tests? - YouTube

https://twitter.com/AutomationPanda/status/1141585091908575232 | “Pandy” Knight on Twitter: "Cool! Thanks. Let me know if you have questions.… "

* [Automation Panda](https://automationpanda.com)
https://automationpanda.com/2018/09/17/book-review-python-testing-with-pytest/ | Book Review: Python Testing with pytest | Automation Panda
https://github.com/AndyLPK247/python-testing-101 | AndyLPK247/python-testing-101: Example projects for the Python Testing 101 series from Automation Panda
https://automationpanda.com/2017/02/04/bdd-101-frameworks/ | BDD 101: Frameworks | Automation Panda

https://twitter.com/AutomationPanda | Automation Panda (@AutomationPanda) | Twitter

https://twitter.com/AutomationPanda/status/1097140065577431041
https://twitter.com/AutomationPanda/status/1048275359303708673
https://twitter.com/AutomationPanda/status/1023346925771345920
https://twitter.com/AutomationPanda/status/1061393338165837825

DjangoCon Keynote by Ana

https://pyvideo.org/pyohio-2019/adopt-a-pytest.html

https://www.hillelwayne.com/talks/beyond-unit-tests/
https://www.youtube.com/watch?v=MYucYon2-lk
-->

## Python and Django Testing and Debugging Tools- Less Relevant Third Party Testing Tools

Nose (Unit Test Extension)
* [Nose 2 Docs](https://docs.nose2.io) and [Nose 2 GitHub](https://github.com/nose-devs/nose2)

Django Nose
* [Django Nose GitHub](https://github.com/django-nose/django-nose)

## Python and Django Debugging and Testing

Testing
* [Test-Driven Development with Python Chapter 8- Testing Deployment Using a Staging Site](http://chimera.labs.oreilly.com/books/1234000000754/ch08.html#_tdd_and_the_danger_areas_of_deployment) 
* [Obey the Testing Goat! (Harry J.W. Percival)](https://www.obeythetestinggoat.com)

Django Testing
* [Obey the Testing Goat: Django Class-Based Views (CBVs)](https://www.obeythetestinggoat.com/book/appendix_Django_Class-Based_Views.html)

<!--
Python- Books- O'Reilly Test-Driven Development with Python and Selenium

https://www.obeythetestinggoat.com/book/appendix_bdd.html | Behaviour-Driven Development (BDD)
https://www.obeythetestinggoat.com/book/chapter_unit_test_first_view.html | Testing a Simple Home Page with Unit Tests

https://www.obeythetestinggoat.com/using-the-built-in-views-and-forms-for-new-user-registration-in-django.html | Obey the Testing Goat!
-->

## Django Rest Framework

* [Django Rest Framework Swagger](https://github.com/marcgibbons/django-rest-swagger) 

Python- Django- Alternative Rest Framework
* [django-tastypie Read the Docs](http://django-tastypie.readthedocs.org)

<!--
https://github.com/encode/django-rest-framework/issues
https://github.com/encode/django-rest-framework/projects

https://github.com/encode/rest-framework-tutorial | encode/rest-framework-tutorial
http://www.tomchristie.com/rest-framework-2-docs/api-guide
https://www.django-rest-framework.org/tutorial/1-serialization/ | 1 - Serialization - Django REST framework

https://github.com/carltongibson/rest-framework-tutorial | carltongibson/rest-framework-tutorial
https://github.com/carltongibson/rest-framework-tutorial/blob/master/docs/azure/1-vscode.md | rest-framework-tutorial/1-vscode.md at master · carltongibson/rest-framework-tutorial
https://github.com/carltongibson/rest-framework-tutorial/blob/master/docs/azure/2-appservice.md | rest-framework-tutorial/2-appservice.md at master · carltongibson/rest-framework-tutorial

https://twitter.com/carltongibson/status/1072951282502172678 | Carlton Gibson on Twitter: "Been having fun with @code for about a year and a half. I got together with @nnja to talk about using it with Django and DRF…… https://t.co/XmFcENotrc"
https://www.youtube.com/watch?list=PLlrxD0HtieHjQMK-jWHRy3aHGLhbAFqbR&time_continue=10&v=0Bk0dw2Ktbg | Python on Azure: Part 1—Building Django apps with Visual Studio Code | Azure Friday - YouTube
https://www.youtube.com/watch?list=PLlrxD0HtieHjQMK-jWHRy3aHGLhbAFqbR&v=FHJvsvbD_cQ | Python on Azure: Part 2—Deploying Django services to Azure Web Apps | Azure Friday - YouTube

https://github.com/caktus/drf-sample | caktus/drf-sample: Django REST Framework Sample

https://wsvincent.com/django-rest-framework-tutorial/ | Django Rest Framework - Blog API - William S. Vincent
https://github.com/wsvincent/rest-framework-tutorial

https://github.com/philipn/django-rest-framework-filters | philipn/django-rest-framework-filters: Better filtering for Django REST Framework
-->

## Serialization

Python- Django- Rest Framework (Serialization/Deserialization)
* [Django Rest Framework: Tutorial 1: Serialization](http://www.django-rest-framework.org/tutorial/1-serialization)
* [Serializing Django objects](https://docs.djangoproject.com/en/dev/topics/serialization)
* [JSON](https://docs.djangoproject.com/en/dev/topics/serialization/#serialization-formats-json)

## Python and Django Geo

Python- Django- Rest Framework GIS
* [Django Rest Framework GIS API Guide Fields](http://www.django-rest-framework.org/api-guide/fields/#django-rest-framework-gis)  
* [Django Rest Framework GIS GitHub](https://github.com/djangonauts/django-rest-framework-gis)  
* [Django Rest Framework GIS PyPi](https://pypi.python.org/pypi/djangorestframework-gis)  
* [Django Rest Framework GIS Forum](https://groups.google.com/forum/#!forum/django-rest-framework-gis)  

Python- Python/Django- Internationalization and Localization, Translation
* [Django i18n Forum](https://groups.google.com/forum/#!forum/django-i18n)  
* [Python Gettext Multilingual Internationalization Services](https://docs.python.org/2/library/gettext.html)  
* [Django Local Flavor](https://docs.djangoproject.com/en/dev/topics/localflavor)  
* [Django Local Flavor Read the Docs](https://django-localflavor.readthedocs.org/en/latest)  
* [Django Local Flavor GitHub](https://github.com/django/django-localflavor)  
* [Django Local Flavor PyPi](https://pypi.python.org/pypi/django-localflavor)  
* [Django Internationalization and Localization](https://docs.djangoproject.com/en/dev/topics/i18n)  
* [Django Internationalization and Localization, Translation](https://docs.djangoproject.com/en/dev/topics/i18n/translation) 

<!--
https://github.com/django/django-formtools
https://github.com/django/django-contrib-comments
-->

GeoDjango
* [GeoDjango](http://geodjango.org)  
* [GeoDjango Installation Postgresapp](https://docs.djangoproject.com/en/1.9/ref/contrib/gis/install/#postgresapp)

PostGIS (Spatial Database Extender for PostgreSQL)
* [PostGIS](http://postgis.net)  
* [PostGIS Wikipedia](http://en.wikipedia.org/wiki/PostGIS)  
* [UbuntuGIS](https://wiki.ubuntu.com/UbuntuGIS)  
* [UbuntuGIS Wiki](http://trac.osgeo.org/ubuntugis/wiki)  
* [Heroku PostGIS Wiki](https://devcenter.heroku.com/articles/postgis)  

SpatiaLite (Spatial Database Extender for SQLite)
* [SpatiaLite](https://www.gaia-gis.it/fossil/libspatialite/index)  
* [SpatiaLite Downloads Page](http://www.gaia-gis.it/gaia-sins/libspatialite-sources)  
* [SpatiaLite Wikipedia](http://en.wikipedia.org/wiki/SpatiaLite)  




## Website and Blog Resources

GitHub Pages Showcase (Jekyll)
* [GitHub Pages Showcase](https://github.com/showcases/github-pages-examples)

Jekyll Themes
* [Jekyll Themes](http://jekyllthemes.org) and [Jekyll Themes GitHub](https://github.com/mattvh/jekyllthemes)
* [Dr. Jekyll Themes](http://drjekyllthemes.github.io) and [Dr. Jekyll Themes GitHub](https://github.com/drjekyllthemes/themes)
* [Jekyll Sites Wiki GitHub](https://github.com/jekyll/jekyll/wiki/Sites)
* [Jekyll Themes Wiki GitHub](https://github.com/jekyll/jekyll/wiki/Themes)

<!--
https://github.com/wowthemesnet/mundana-theme-jekyll

https://github.com/marketplace/actions/jekyll-builder-for-github-pages | Jekyll Builder for GitHub Pages · Actions · GitHub Marketplace

https://ghost.org/docs/ | Ghost Docs
https://demo.ghost.io/
https://github.com/TryGhost/Casper | TryGhost/Casper: The default personal blogging theme for Ghost
https://gatsby.ghost.org/
https://github.com/TryGhost/gatsby-starter-ghost
https://tribeca.ghost.io/ | Tribeca
https://eleventy.ghost.org/ | Posts – Eleventy & Ghost
https://lyra.ghost.io/ | Lyra
https://argon.ghost.io/ | Argon
https://eleventy.ghost.org/
https://github.com/TryGhost/London | TryGhost/London: A free, open source theme for Ghost
https://massively.ghost.io/ | This is Massively
https://editorial.ghost.io/ | Editorial for Ghost

https://sindresorhus.com/apps | Sindre Sorhus
https://github.com/sindresorhus/sindresorhus.github.com | KatherineMichel/sindresorhus.github.com: Personal website of Sindre Sorhus
https://twitter.com/johnmaeda/status/1200551971737997312 | John Maeda on Twitter: "The software that @sindresorhus makes is always so useful and beautiful. https://t.co/SonMu4ibg9" / Twitter

https://github.com/fastai/fast_template
https://twitter.com/jeremyphoward/status/1218662038752202753
http://fast-template.fast.ai/2020/01/14/welcome.html
https://twitter.com/jeremyphoward/status/1217909027973124096
https://twitter.com/jeremyphoward/status/1218028267057246211 | Jeremy Howard on Twitter: "I've now added optional LaTeX equation support to this template. https://t.co/Z56HQbpyoa https://t.co/wOaAmas61x" / Twitter
-->

## Shortcuts

<!--
https://code.visualstudio.com/docs/editor/command-line | The Visual Studio Code command-line options
https://code.visualstudio.com/docs/getstarted/tips-and-tricks | Visual Studio Code Tips and Tricks


https://developers.google.com/web/tools/chrome-devtools/shortcuts | Chrome DevTools Keyboard Shortcuts  |  Tools for Web Developers

Snippets
https://twitter.com/EmmaWedekind/status/1076180368351469569 | Emma Wedekind ✨ on Twitter: "Seriously, @hackerrank is the GREATEST platform for practicing problem solving skills and algorithmic coding. Highly recommend. And if you aren't already using Chrome snippets to run & debug your JS code, check it out now => https://t.co/ts3GlEaD6k"
https://developers.google.com/web/tools/chrome-devtools/snippets | Run Snippets Of Code From Any Page  |  Tools for Web Developers  |  Google Developers


Mac
https://support.apple.com/guide/terminal/keyboard-shortcuts-trmlshtcts/mac | Keyboard shortcuts in Terminal on Mac - Apple Support

Twitter
https://winaero.com/blog/twitter-hotkeys-web-site-shortcuts/

VS Code Mac
https://code.visualstudio.com/shortcuts/keyboard-shortcuts-macos.pdf

GitHub
https://help.github.com/en/github/getting-started-with-github/keyboard-shortcuts | Keyboard shortcuts - GitHub Help
https://help.github.com/en/github/managing-files-in-a-repository/navigating-code-on-github

GitHub Hotkeys
https://twitter.com/shl/status/1146205870293835778 | Sahil Lavingia on Twitter: "apple+Q… "
https://twitter.com/_ericelliott/status/1163240418806575105 | Eric Elliott on Twitter: "GitHub has useful hotkeys. To see them, type `?` on any GitHub page. #code #JavaScript" / Twitter
-->

## Visual Studio Code

* [Visual Studio Code](https://code.visualstudio.com) and [Visual Studio GitHub](https://github.com/Microsoft/vscode)
* [Visual Studio Code Docs](https://code.visualstudio.com/docs)
* [Visual Studio Code Languages](https://code.visualstudio.com/Docs/languages/overview)

<!--
https://marketplace.visualstudio.com/search?term=javascript&target=VSCode&category=All%20categories&sortBy=Relevance
https://marketplace.visualstudio.com/search?term=python&target=VSCode&category=All%20categories&sortBy=Relevance

https://gist.github.com/paltman/6d99cc0ffdb4cc28eb5226b52f7c8dd7 | My VSCode settings for Django + Vue development

node.js
https://code.visualstudio.com/docs/nodejs/nodejs-tutorial

C++
https://code.visualstudio.com/docs/cpp/launch-json-reference

tasks.json
https://code.visualstudio.com/docs/editor/tasks
settings
https://code.visualstudio.com/docs/getstarted/settings

https://code.visualstudio.com/docs/editor/versioncontrol | Version Control in Visual Studio Code

https://github.com/microsoft/vscode
https://github.com/Microsoft/vscode-python
https://github.com/DonJayamanne/pythonVSCode | DonJayamanne/pythonVSCode: This extension is now maintained in the Microsoft fork.

https://code.visualstudio.com/docs/languages/python#_other-popular-python-extensions | Python in Visual Studio Code

Installed
https://github.com/Microsoft/vscode-pull-request-github | Microsoft/vscode-pull-request-github: VS Code Pull Request Provider for GitHub

https://code.visualstudio.com/docs/editor/codebasics#_save-auto-save | Basic Editing in Visual Studio Code

https://marketplace.visualstudio.com/vscode

https://code.visualstudio.com/docs/python/environments
https://code.visualstudio.com/docs/python/tutorial-django
https://code.visualstudio.com/docs/python/python-tutorial | Get Started Tutorial for Python in Visual Studio Code
https://code.visualstudio.com/docs/languages/python
https://code.visualstudio.com/docs/python/python-tutorial#_prerequisites
https://code.visualstudio.com/docs/python/editing#_autocomplete-and-intellisense
https://code.visualstudio.com/docs/python/editing#_formatting
https://pypi.org/project/autopep8/
https://github.com/psf/black
https://code.visualstudio.com/docs/python/linting
https://code.visualstudio.com/docs/python/linting#_specific-linters
https://code.visualstudio.com/docs/python/debugging
https://code.visualstudio.com/docs/python/python-tutorial#_configure-and-run-the-debugger
https://code.visualstudio.com/docs/python/debugging#_debugging-specific-app-types
https://code.visualstudio.com/docs/python/testing
https://code.visualstudio.com/docs/python/testing#_enable-a-test-framework | Testing Python in Visual Studio Code
https://docs.python.org/3/library/unittest.html
https://docs.pytest.org/en/latest/
https://code.visualstudio.com/docs/python/editing#_refactoring
https://code.visualstudio.com/docs/python/data-science-tutorial | Python and Data Science Tutorial in Visual Studio Code

https://github.com/github/VisualStudio/blob/master/docs/using/publishing-an-existing-project-to-github.md
-->

## Visual Studio Code

Python and Visual Studio Code
* [Dan Taylor: "Get Productive with Python in Visual Studio Code" )EuroPython 2018)](https://ep2018.europython.eu/conference/talks/get-productive-with-python-in-visual-studio-code) and ["Get Productive with Python in Visual Studio Code" GitHub](https://github.com/qubitron/pydemo)

<!--
https://realpython.com/python-development-visual-studio-code/ | Python Development in Visual Studio Code – Real Python

https://developers.google.com/web/updates/2017/04/headless-chrome
https://github.com/auchenberg/vscode-browser-preview | auchenberg/vscode-browser-preview: A real browser preview inside your editor that you can debug.
https://medium.com/@auchenberg/introducing-simultaneous-nirvana-javascript-debugging-for-node-js-and-chrome-in-vs-code-d898a4011ab1

https://code.visualstudio.com/docs/editor/userdefinedsnippets | Creating your own snippets in Visual Studio Code

https://www.kennethreitz.org/essays/why-you-should-use-vs-code-if-youre-a-python-developer
https://github.com/viatsko/awesome-vscode | viatsko/awesome-vscode: A curated list of delightful VS Code packages and resources.

VC Studio Code
https://blogs.msdn.microsoft.com/visualstudio/2018/06/14/getting-started-with-microsofts-python-developer-tools/ | The Visual Studio Blog
https://blogs.msdn.microsoft.com/visualstudio/2018/08/30/improving-your-productivity-in-the-visual-studio-editor/ | Improving your productivity in the Visual Studio Editor | The Visual Studio Blog
https://blogs.msdn.microsoft.com/visualstudio/2018/07/24/visual-studio-intellicode-expands-ai-assisted-coding-to-python-in-visual-studio-code/

https://blog.github.com/2019-01-07-create-pull-requests-in-vscode/ | VS Code: Now creating pull requests | The GitHub Blog
https://code.visualstudio.com/blogs/2018/09/10/introducing-github-pullrequests

https://devblogs.microsoft.com/devops/introducing-the-new-pull-request-experience-for-azure-repos/
-->

## Useful Files

Shells
* [Comparison of Command Shells Wikipedia](https://en.wikipedia.org/wiki/Comparison_of_command_shells)
* [Unix Shell Wikipedia](http://en.wikipedia.org/wiki/Unix_shell)  
* [Bash (Unix Shell) Wikipedia](http://en.wikipedia.org/wiki/Bash_(Unix_shell))  

Permissions
* [File System Permissions](https://en.wikipedia.org/wiki/File_system_permissions)

Rake and Make
* [Ruby Rake File GitHub](https://github.com/ruby/rake)
* [Make Wikipedia](https://en.wikipedia.org/wiki/Make_(software))
* [GNU Makefile](https://www.gnu.org/software/make) and [Makefile Wikipedia](https://en.wikipedia.org/wiki/Makefile)

Files
* [Manifest File Wikipedia](https://en.wikipedia.org/wiki/Manifest_file)

EditorConfig (tabs versus spaces, ect) .editorconfig
* [EditorConfig](http://editorconfig.org)
* [EditorConfig Plugins](http://editorconfig.org/#download)

Maintenance
* [Cron Wikipedia](https://en.wikipedia.org/wiki/Cron)
* [Lint](https://en.wikipedia.org/wiki/Lint_(software))

Markdown
* [GitHub Flavored Markdown](https://help.github.com/articles/github-flavored-markdown) 

YAML
* [YAML](http://yaml.org) and [YAML Wikipedia](https://en.wikipedia.org/wiki/YAML)

Shebang File
* [Shebang File Wikipedia](https://en.wikipedia.org/wiki/Shebang_(Unix))

<!--
https://www.techopedia.com/definition/5585/cgi-bin#:~:text=A%20CGI%2Dbin%20is%20a,of%20scripts%20in%20Web%20design. | What is a CGI-Bin? - Definition from Techopedia

https://www.linux.com/training-tutorials/writing-simple-bash-script/ | Writing a Simple Bash Script - Linux.com

https://www.tutorialspoint.com/unix/if-fi-statement.htm | Unix / Linux Shell - The if...fi statement - Tutorialspoint
https://www.google.com/search?q=unix+performance+tools&sxsrf=ALeKk021JuhlObGl10CxPDYsznM8JOo0Yw:1591168225245&source=lnms&tbm=isch&sa=X&ved=2ahUKEwiost_Gi-XpAhVPHc0KHXTbBSEQ_AUoAnoECBMQBA&biw=1432&bih=705#imgrc=yDrlKsz_HrH-XM | unix performance tools - Google Search


Apple

https://github.com/drduh/macOS-Security-and-Privacy-Guide | drduh/macOS-Security-and-Privacy-Guide: A practical guide to securing macOS.

Mac keyboard shortcuts
https://support.apple.com/en-us/HT201236

pyenv?
command line tools for xcode - Google Search

ZSH	
https://ohmyz.sh/ | Oh My Zsh - a delightful & open source framework for Zsh
https://github.com/ohmyzsh/ohmyzsh/wiki | Home · ohmyzsh/ohmyzsh Wiki
https://github.com/hmml/awesome-zsh
http://zsh.sourceforge.net/Doc/Release/Shell-Builtin-Commands.html | zsh: 17 Shell Builtin Commands
https://dev.to/glasnt/oh-my-glob-alias-expansion-in-zsh-243e

https://www.iterm2.com/
https://kapeli.com/dash_guide

Brew script

Homebrew
https://github.com/Linuxbrew/homebrew-core
https://github.com/Homebrew/homebrew-cask | Homebrew/homebrew-cask: 🍻 A CLI workflow for the administration of macOS applications distributed as binaries
https://docs.brew.sh/Homebrew-and-Python | Python — Homebrew Documentation

https://twitter.com/ShaneAParrish/status/1258574825091739649 | Shane Parrish on Twitter: "What's the best piece of software you use on a mac that few people have ever heard of?" / Twitter
https://c-command.com/toothfairy/ | ToothFairy: AirPods and Bluetooth utility for Mac
https://twitter.com/Jonsamp/status/1258578441370247169 | Jon Samp on Twitter: "@ShaneAParrish Pastebot! Search copied things, and sequential copy/paste 🙀😍 https://t.co/4evMNoTafX" / Twitter
-->

<!--
aliases, dotfiles, Regex

https://stackoverflow.com/questions/1587846/how-do-i-show-the-changes-which-have-been-staged | git - How do I show the changes which have been staged? - Stack Overflow

https://git-scm.com/docs/git-whatchanged | Git - git-whatchanged Documentation
https://www.atlassian.com/git/tutorials/saving-changes/git-stash | git stash - Saving Changes | Atlassian Git Tutorial

https://dev.to/ben/what-do-you-google-every-single-time-and-never-just-memorize-ajj | What do you Google EVERY. SINGLE. TIME. and never just memorize? - DEV Community 👩‍💻👨‍💻

http://www.linfo.org/usr_sbin.html

https://realpython.com/effective-python-environment/ | An Effective Python Environment: Making Yourself at Home – Real Python
https://realpython.com/what-is-pip/ | What Is Pip? A Guide for New Pythonistas – Real Python
https://www.freecodecamp.org/news/manage-multiple-python-versions-and-virtual-environments-venv-pyenv-pyvenv-a29fb00c296f/ | How to manage multiple Python versions and virtual environments

https://en.wikipedia.org/wiki/Shell_script

Aliases
https://opensource.com/article/20/1/bash-scripts-aliases | My favorite Bash hacks | Opensource.com

https://twitter.com/varcharr/status/1258795317102735361 | casey on Twitter: "What are your favorite and/or the most useful bash commands?" / Twitter

Bash
https://www.gnu.org/software/bash/manual/
https://www.gnu.org/software/bash/manual/bash.html | Bash Reference Manual
https://www.gnu.org/software/bash/manual/bashref.html
http://tldp.org/LDP/Bash-Beginners-Guide/html/sect_02_01.html
http://tldp.org/HOWTO/Bash-Prog-Intro-HOWTO.html
Advanced Bash-Scripting Guide
http://tldp.org/LDP/abs/html/
http://www.tldp.org/LDP/abs/html/why-shell.html
File security
http://www.tldp.org/LDP/intro-linux/html/sect_03_04.html

https://developers.redhat.com/promotions/linux-cheatsheet/ | Linux Commands Cheat Sheet | Red Hat Developer
https://tldp.org/LDP/GNU-Linux-Tools-Summary/html/x11655.htm

https://github.com/topics/bash | Topic: bash
https://hellowebbooks.com/learn-command-line/ | Really Friendly Command Line 
Intro - Hello Web Books

Bash versus Python
https://opensource.com/article/19/4/bash-vs-python
https://stackoverflow.com/questions/6908143/should-i-put-shebang-in-python-scripts-and-what-form-should-it-take

https://www.linuxjournal.com/content/understanding-bash-elements-programming

https://www.gnu.org/software/make/manual/make.html
https://www.gnu.org/software/make/manual/html_node/Phony-Targets.html | GNU make: Phony Targets

https://learnxinyminutes.com/docs/yaml/
https://en.m.wikipedia.org/wiki/YAML
http://www.yaml.org/refcard.html
https://yaml.org/spec/1.2/spec.html | YAML Ain’t Markup Language (YAML™) Version 1.2

Dotfiles
https://github.com/paulirish/dotfiles | paulirish/dotfiles: paul's shell, git, etc config files. also homebrew, migration setup. good stuff.
https://github.com/Miserlou/dotfiles-osx | Miserlou/dotfiles-osx: Updated dotfiles. For me not you.
https://github.com/kennethreitz/dotfiles | kennethreitz/dotfiles: My personal dotfiles.
https://github.com/nnja/new-computer/blob/master/setup.sh#L253 | new-computer/setup.sh at master · nnja/new-computer
https://twitter.com/andrewgodwin/status/1180286950344818689 | Andrew Godwin on Twitter: "@simonw This is exactly what I do for my dotfiles. Recommend also having a script in the repo that makes the links for you." / Twitter
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

## Package Tools and Testing

<!--
attrs, pre-commit, tox, nox, flake8, check-manifest, twine, isort, seed-isort-config, black, pytest-cov, codecov action, flake8-black

Not used- but could be?
* [attrs GitHub](https://github.com/python-attrs/attrs)
* [pytest-cov Read the Docs](https://pytest-cov.readthedocs.io)

https://github.com/codecov/codecov-action | codecov/codecov-action: GitHub Action that uploads coverage to Codecov

https://github.com/pytest-dev/pytest-cov | pytest-dev/pytest-cov: Coverage plugin for pytest.
https://github.com/pytest-dev/pytest-flask | pytest-dev/pytest-flask: A set of pytest fixtures to test Flask applications
https://pypi.org/project/flake8-black/ | flake8-black · PyPI
-->

## Eldarion

Package Tools
* [django-appconf Read the Docs](https://django-appconf.readthedocs.io) and [django-appconf PyPI](https://pypi.org/project/django-appconf)

<!--
https://github.com/django-compressor/django-appconf | django-compressor/django-appconf: An app to handle configuration defaults of packaged Django apps gracefully
-->

Continuous Integration and Delivery
* [CircleCI](https://circleci.com)

Coverage
* [Codecov](https://codecov.io)
* [Coverage Read the Docs](http://coverage.readthedocs.org) and [Coverage Bitbucket](https://bitbucket.org/ned/coveragepy)

Testing Tools
* [Tox Read the Docs](https://tox.readthedocs.org)
* [Tox Parallel Mode](https://tox.readthedocs.io/en/latest/example/basic.html#parallel-mode)
* [Detox GitHub (Archived)](https://github.com/tox-dev/detox) and [Detox PyPi](https://pypi.python.org/pypi/detox)

<!--
Tox GitHub Action
https://github.com/tox-dev/action | tox-dev/action: A Github Action to run tox environments within Github

https://docs.codecov.io/docs/python
https://codecov.io/#features | Codecov

"[Integration with coverage.py](https://docs.djangoproject.com/en/dev/topics/testing/advanced/#topics-testing-code-coverage)."
"[Running tests using tox](https://docs.djangoproject.com/en/dev/internals/contributing/writing-code/unit-tests/#running-tests-using-tox)"

https://github.com/marketplace?utf8=%E2%9C%93&query=tox | GitHub Marketplace · Tools to improve your workflow
https://tox.readthedocs.io/en/latest/example/basic.html#a-simple-tox-ini-default-environments | Basic usage — tox 3.14.6.dev2 documentation

https://github.com/codecov/example-python#testing-with-tox | codecov/example-python: Python coverage example
https://github.com/pallets/flask/blob/master/tox.ini
https://github.com/pganssle/tox-examples | pganssle/tox-examples

https://stackoverflow.com/questions/21991765/how-to-generate-coverage-from-setup-py | python - How to generate coverage from setup.py - Stack Overflow
https://github.com/codecov/example-python#how-to-generate-coverage-reports
"coverage.py is required to collect coverage metrics."
-->

tox Alternative (not used)
* [Nox](http://nox.thea.codes) and [Nox GitHub](https://github.com/theacodes/nox)

Import Sorting
* [isort](http://isort.readthedocs.io) and [isort GitHub](https://github.com/timothycrosley/isort)

Formatting
* [Flake8 GitHub](https://gitlab.com/pycqa/flake8) and [Flake8 Docs](http://flake8.pycqa.org)
* [doc8 GitHub](https://github.com/openstack/doc8)
* [pydocstyle GitHub](https://github.com/PyCQA/pydocstyle)
* [mccabe GitHub](https://github.com/PyCQA/mccabe)
* [Flake8 Quotes GitHub](https://github.com/zheller/flake8-quotes)

<!--
https://github.com/timothycrosley/isort/issues/694

?
https://pypi.org/project/pyflakes/
https://github.com/PyCQA/pyflakes
-->

Not used?
* [Factory Boy GitHub](https://github.com/FactoryBoy/factory_boy) and [Factory Boy PyPI](https://pypi.python.org/pypi/factory_boy)

Kubernetes
* [Kubernetes](https://kubernetes.io)

Webpack Versus Browserify
* [Vue](https://vuejs.org/)
* [Webpack](https://webpack.js.org)
* [Copy Webpack Plugin GitHub](https://github.com/webpack-contrib/copy-webpack-plugin)
* [Browserify](http://browserify.org)
* [Browsersync](https://www.browsersync.io/)

<!--
http://fontawesome.io/ | Font Awesome, the iconic font and CSS toolkit
https://fontawesome.com | Font Awesome 5 | Font Awesome

Black and single quotes
https://github.com/peterjc/flake8-black | peterjc/flake8-black: flake8 plugin to run black for checking Python coding style
https://github.com/python/black/issues/118 | Single quotes option · Issue #118 · python/black

https://circleci.com/blog/setting-up-continuous-integration-with-github/ | GitHub Continuous Integration - GitHub CI | CircleCI

https://github.com/CircleCI-Public/circleci-cli | CircleCI-Public/circleci-cli: Use CircleCI from the command line
https://github.com/CircleCI-Public/circleci-demo-python-django | CircleCI-Public/circleci-demo-python-django: Example Django application running on CircleCI

https://circleci.com/docs/2.0/ | Welcome to CircleCI Documentation - CircleCI
https://circleci.com/docs/2.0/example-configs/ | Example Public Repos - CircleCI
https://circleci.com/docs/2.0/caching/ | Caching Dependencies - CircleCI
https://circleci.com/docs/2.0/env-vars/ | Using Environment Variables - CircleCI
https://circleci.com/docs/2.0/language-python/ | Configuring a Python Application on CircleCI - CircleCI
https://github.com/CircleCI-Public/circleci-demo-python-django | CircleCI-Public/circleci-demo-python-django: Example Django application running on CircleCI

https://coverage.readthedocs.io/en/coverage-5.0/config.html | Configuration files — Coverage.py 4.4.2 documentation

http://flake8.pycqa.org/en/3.1.1/user/ignoring-errors.html | Ignoring Errors with Flake8 — flake8 3.1.1 documentation

flake8 
noqa: E501
https://pypi.org/project/flake8-confusables/ | flake8-confusables · Warehouse (PyPI)
-->

## Code Formatting Tools

Code Formatting
* [Black GitHub](https://github.com/psf/black)
* [Black Online (Playground) GitHub](https://github.com/jpadilla/black-online)
* [Black Out GitHub](https://github.com/mariatta/black_out)
* [White GitHub](https://github.com/kennethreitz/white)
* [Google YAPF](https://github.com/google/yapf)

<!--
https://github.com/bots-for-humanity/black-out

https://black.now.sh/ | Black Playground

https://github.com/eventbrite/invoke-release | eventbrite/invoke-release: A set of command line tools that help software engineers release Python projects quickly, easily, and in a consistent manner.
https://github.com/twisted/incremental#updating | twisted/incremental: A library for versioning your Python projects.

https://www.youtube.com/watch?v=-BHverY7IwU
http://www.pyinvoke.org/
https://github.com/pypa/pip/blob/master/tasks/generate.py
-->

## Command Line

* [Click GitHub](https://github.com/pallets/click)
* [Chalk GitHub](https://github.com/chalk/chalk)

<!--
Typer
https://typer.tiangolo.com/ | Typer

https://github.com/google/python-fire/releases/tag/v0.2.0 | Release v0.2.0 · google/python-fire
https://github.com/google/python-fire

http://click.pocoo.org/5/contrib/
https://github.com/click-contrib | click-contrib
http://click.pocoo.org/5/ | Welcome to the Click Documentation — Click Documentation (5.0)
https://github.com/kennethreitz/crayons/blob/master/crayons.py | crayons/crayons.py at master · kennethreitz/crayons
https://pypi.python.org/pypi/django-click | django-click 2.0.0 : Python Package Index
-->

## Azure

<!--
https://tonybaloney.github.io/posts/django-on-azure-beyond-hello-world.html | Django on Azure - beyond "hello world"

Hynek- Azure Pipelines
Publish Python packages in Azure Pipelines
https://docs.microsoft.com/en-us/azure/devops/pipelines/artifacts/pypi?view=azure-devops&tabs=yaml&viewFallbackFrom=vsts
https://docs.microsoft.com/en-us/azure/devops/pipelines/artifacts/pypi?view=azure-devops&tabs=yaml
https://hynek.me/articles/simple-python-azure-pipelines/ | Python in Azure Pipelines, Step by Step · Homepage of Hynek Schlawack
https://docs.microsoft.com/en-us/azure/devops/pipelines/process/container-phases?view=azure-devops&tabs=yaml | Container Jobs in Azure Pipelines and TFS - Azure Pipelines | Microsoft Docs

Azure Piplines
https://azure.microsoft.com/en-us/services/devops/pipelines/
https://docs.microsoft.com/en-us/azure/devops/pipelines/migrate/from-travis?view=azure-devops
https://medium.com/@anthonypjshaw/azure-pipelines-with-python-by-example-aa65f4070634
https://github.com/asottile/azure-pipeline-templates

https://github.com/Azure/azure-quickstart-templates

https://github.com/trallard/pycon2020-azure-functions | trallard/pycon2020-azure-functions: ⚡️ 🏻‍♀️ Sponsored tutorial content for PyCon 2020
-->

## Hosts, Containers, Serverless, Functions, Pipelines

Containers
* [Kubernetes](http://kubernetes.io) and [Kubernetes Docs](https://kubernetes.io/docs/home)
* [Docker](https://www.docker.com) and [Docker Docs](https://docs.docker.com)
* ["Getting Started with Docker for Mac"](https://docs.docker.com/docker-for-mac)

AWS- Lambda
* [AWS Lambda](http://aws.amazon.com/lambda) and [AWS Lambda Documentation](http://docs.aws.amazon.com/lambda/latest/dg/welcome.html) 
* [AWS API Gateway](https://aws.amazon.com/api-gateway/)
* [Serverless GitHub](https://github.com/serverless/serverless) 
* [Zappa GitHub](https://github.com/Miserlou/Zappa)

Additional Serverless
* [Google Cloud Functions](https://cloud.google.com/functions/docs)
* [Firebase Functions](https://firebase.google.com/features/functions)
* [Azure Functions](https://azure.microsoft.com/en-us/services/functions) and [Azure Functions GitHub](https://github.com/Azure/Azure-Functions)

<!--
https://boto3.readthedocs.io/en/latest/index.html

https://developers.google.com/actions/templates/first-app | Templates  |  Actions on Google  |  Google Developers

Google Cloud

https://twitter.com/di_codes/status/1215368211211923456 | Dustin Ingram on Twitter: "Happy to announce the release of a Function Framework for Python via @GoogleOSS. 🎉 It lets you run a Cloud Function locally for development or deploy it to other services (like Cloud Run)... without having to change your function at all. More details: https://t.co/87xrnAdvg3" / Twitter
https://dev.to/googlecloud/portable-cloud-functions-with-the-python-functions-framework-a6a | Portable Cloud Functions with the Python Functions Framework - DEV Community 👩‍💻👨‍💻

Google Cloud Django/Python
https://github.com/GoogleCloudPlatform/django-cloud-deploy | GoogleCloudPlatform/django-cloud-deploy: Easier deployment of Django applications in the cloud.
https://github.com/GoogleCloudPlatform/python-docs-samples | GoogleCloudPlatform/python-docs-samples: Code samples used on cloud.google.com

https://twitter.com/glasnt/status/1208096663887216641 | Katie McLaughlin ✨ on Twitter: "@jacobian Yes, just to avoid raw secrets. Berglas is a helper/wrapper for Cloud KMS" / Twitter

https://github.com/Miserlou/lambda-packages | Miserlou/lambda-packages: Various popular python libraries, pre-compiled to be compatible with AWS Lambda
https://github.com/Miserlou/zappa-django-utils | Miserlou/zappa-django-utils: A handy Django application to supercharge your Zappa deployments.

https://blog.zappa.io/posts/s3sqlite-a-serverless-relational-database

https://serverless.com
https://github.com/serverless/site
https://github.com/serverless/examples | serverless/examples: Serverless Examples – A collection of boilerplates and examples of serverless architectures built with the Serverless Framework and AWS Lambda

https://aws.amazon.com/step-functions/ | AWS Step Functions – Coordinate Microservices using Visual Workflows
http://docs.aws.amazon.com/lambda/latest/dg/concurrent-executions.html | Lambda Function Concurrent Executions - AWS Lambda
https://cloud.google.com/functions/docs/ | Google Cloud Functions Documentation  |  Cloud Functions  |  Google Cloud Platform
    
https://github.com/awslabs/chalice
https://github.com/apex/apex
https://github.com/apex/up | apex/up: Deploy infinitely scalable serverless apps, apis, and sites in seconds.
-->

## Automation

Terraform
* [Terraform](https://www.terraform.io) and [Terraform Module Registry](https://registry.terraform.io)

Python- Fabric
* [Fabric](http://www.fabfile.org), [Fabric PyPi](https://pypi.python.org/pypi/Fabric), and [Fabric GitHub](https://github.com/fabric/fabric) 

<!--
salt, ansible

http://docs.fabfile.org/en/1.13/api/contrib/django.html

https://www.digitalocean.com/community/tutorials/how-to-use-fabric-to-automate-administration-tasks-and-deployments
-->

## Docs

### Python Docs Themes

Sphinx and Django-Sphinx
* [Sphinx](http://sphinx-doc.org) and [Sphinx GitHub](https://github.com/sphinx-doc/sphinx)  
* [Sphinx Alabaster Theme (Default now) GitHub](https://github.com/bitprophet/alabaster)
* [Example of Sphinx Alabaster Theme (Python Guide)](https://docs.python-guide.org) and [Example of Sphinx Alabaster Theme (Python Guide) GitHub](https://github.com/realpython/python-guide)
* [Django-Sphinxdoc PyPi](https://pypi.python.org/pypi/django-sphinxdoc) 
* [Python Docs Theme (Sphinx)](https://github.com/python/python-docs-theme)
* [Read the Docs Sphinx Theme GitHub](https://github.com/snide/sphinx_rtd_theme) 

<!--
https://simonwillison.net/2018/Jul/28/documentation-unit-tests/ | Documentation unit tests
https://pypi.org/project/codegen/ | codegen · PyPI
https://aws-amplify.github.io/docs/cli/codegen?sdk=js | Codegen
https://github.com/swagger-api/swagger-codegen | swagger-api/swagger-codegen: swagger-codegen contains a template-driven engine to generate documentation, API clients and server stubs in different languages by parsing your OpenAPI / Swagger definition.
-->

<!--
Hynek- Docs
https://www.sphinx-doc.org/en/master/
https://www.ericholscher.com/blog/2016/mar/15/dont-use-markdown-for-technical-docs/
https://readthedocs.org/
https://docs.readthedocs.io/en/stable/intro/getting-started-with-sphinx.html
https://readthedocs.org/accounts/login/?next=/accounts/gold/
https://github.com/python-attrs/attrs/blob/6fa28b3b074a935038dd701382eb67f0e953d097/docs/conf.py#L37-L42
https://www.sphinx-doc.org/en/master/usage/extensions/autodoc.html
https://raw.githubusercontent.com/python-attrs/attrs/master/docs/api.rst
https://www.sphinx-doc.org/en/master/usage/extensions/doctest.html
https://docs.python.org/3/library/doctest.html
https://www.sphinx-doc.org/en/master/usage/extensions/intersphinx.html
https://github.com/python-attrs/attrs/blob/6fa28b3b074a935038dd701382eb67f0e953d097/docs/conf.py#L157
https://docs.python.org/3/library/logging.html#logging.getLogger
https://github.com/python-attrs/attrs/blob/de84609505845edc0e05c2ff918a44085816e35e/tox.ini#L47-L53
https://jml.io/pages/test-docstrings.html
-->

<!--
https://twitter.com/pganssle/status/1167147863899561984 | Paul Ganssle on Twitter: "Yessssss. We set up netlify hooks for setuptools and it is so great to see the built documentation as part of the PR, hopefully this will be simpler to set up and more accurate! https://t.co/PiouhPzDXl" / Twitter

https://docutils.sourceforge.io/rst.html | reStructuredText
https://pandoc.org/ | Pandoc - About pandoc

https://realpython.com/lessons/python-project-documentation-overview/ | Python Project Documentation Overview – Real Python
https://realpython.com/courses/documenting-python-code/ | Documenting Python Code: A Complete Guide – Real Python
https://realpython.com/courses/documenting-python-projects-sphinx-read-the-docs/ | Documenting Python Projects With Sphinx and Read The Docs – Real Python

Mason Egger
https://www.youtube.com/watch?v=wEt_8twQctQ&feature=youtu.be
https://masonegger.com/talks/
https://masonegger.com/talks/ci-docs/
https://twitter.com/masonegger | Mason Egger @ #PyGotham (@masonegger) / Twitter

https://www.amazon.com/dp/0134689321/ref=cm_sw_su_dp | Living Documentation: Continuous Knowledge Sharing by Design: Cyrille Martraire: 9780134689326: Amazon.com: Books
https://www.amazon.com/dp/B0784ZJWSR/ref=dp-kindle-redirect?_encoding=UTF8&btkr=1 | Amazon.com: Docs Like Code eBook: Anne Gentle: Kindle Store

Runbook
https://github.com/Financial-Times/runbook.md | Financial-Times/runbook.md: tools for parsing, validating and importing runbooks from repos
https://twitter.com/simonw/status/1149641317690953730 | Simon Willison on Twitter: "There's so much smart thinking in here. I'm a huge proponent of docs living in the same repo as code. At the FT they extend that to their runbooks, which document the system for the ops team but also double as high-level "what the heck is this thing" descriptions.… https://t.co/LGG9i3vkN9"
https://raw.githubusercontent.com/Financial-Times/runbook.md/master/docs/example.md
https://medium.com/ft-product-technology/documentation-day-how-the-ft-com-team-improved-our-documentation-to-95-usefulness-in-7-hours-b73d1a7e6f30 | Documentation Day: How the FT.com team improved our documentation to 95% usefulness in 7 hours*
https://simonwillison.net/2018/Jul/28/documentation-unit-tests/ | Documentation unit tests
https://simonwillison.net/2017/Jul/7/doc-of-docs/ | Doc of docs

Docs
https://labs.spotify.com/2019/10/01/solving-documentation-for-monoliths-and-monorepos/

https://github.com/tomchristie/mkautodoc | tomchristie/mkautodoc: Auto documentation for MkDocs 📘

MkDocs
https://docs.readthedocs.io/en/stable/intro/getting-started-with-sphinx.html
https://www.mkdocs.org/user-guide/writing-your-docs/
https://www.mkdocs.org/user-guide/deploying-your-docs/
https://github.com/mkdocs/mkdocs/wiki/MkDocs-Themes
https://squidfunk.github.io/mkdocs-material/getting-started/
https://github.com/mkdocs/mkdocs/wiki/MkDocs-Plugins
-->

<!--
## Docs

https://www.mkdocs.org/ | MkDocs
https://www.mkdocs.org/#theming-our-documentation | MkDocs
https://github.com/mkdocs/mkdocs/wiki/MkDocs-Themes | MkDocs Themes · mkdocs/mkdocs Wiki

https://github.com/mkdocs/mkdocs/wiki/MkDocs-Themes#gitbook-theme | MkDocs Themes · mkdocs/mkdocs Wiki
https://pypi.org/project/mkdocs-gitbook/ | mkdocs-gitbook · PyPI
https://github.com/connerxyz/common-utils/blob/master/docs/mkdocs.yml | common-utils/mkdocs.yml at master · connerxyz/common-utils
https://github.com/mkdocs/mkdocs/issue/1452 | Clarify documentation · Issue #1452 · mkdocs/mkdocs
https://github.com/connerxyz/common-utils/blob/master/docs/mkdocs.yml | common-utils/mkdocs.yml at master · connerxyz/common-utils
https://github.com/pallets/flask/tree/master/docs | flask/docs at master · pallets/flask
https://www.mkdocs.org/user-guide/custom-themes/ | Custom Themes - MkDocs

Alabaster
https://github.com/notpushkin/mkdocs-alabaster | notpushkin/mkdocs-alabaster: Alabaster port for MkDocs
https://alabaster.readthedocs.io/en/latest/installation.html | Installation — Alabaster documentation
https://github.com/bitprophet/alabaster | bitprophet/alabaster: Lightweight, configurable Sphinx theme. Now the Sphinx default!

Bootstrap Theme
https://mkdocs.github.io/mkdocs-bootstrap/ | MkDocs Bootstrap Theme
https://github.com/mkdocs/mkdocs-bootstrap | mkdocs/mkdocs-bootstrap: MkDocs Bootstrap Theme

GitBook
https://gitlab.com/lramage/mkdocs-gitbook-theme | Lucas Ramage / Mkdocs - GitBook Theme · GitLab
https://lramage.gitlab.io/mkdocs-gitbook-theme/ | Home - Mkdocs - GitBook Theme
https://pypi.org/project/mkdocs-gitbook/ | mkdocs-gitbook · PyPI

Sphinx
https://github.com/sphinx-doc/sphinx | sphinx-doc/sphinx: Main repository for the Sphinx documentation builder
http://www.sphinx-doc.org/en/master/usage/quickstart.html | Getting Started — Sphinx 3.0.0+/17d907d4e documentation
https://www.sphinx-doc.org/en/1.6/markdown.html | Markdown support — Sphinx 1.6.7 documentation
https://www.sphinx-doc.org/en/master/usage/markdown.html | Markdown — Sphinx 3.0.0+/17d907d4e documentation

http://www.sphinx-doc.org/en/master/contents.html | Sphinx documentation contents — Sphinx 1.8.0+ documentation
http://www.sphinx-doc.org/en/master/usage/markdown.html#configuration | Markdown — Sphinx 1.8.0+ documentation
https://github.com/kennethreitz/python-guide/blob/master/requirements.txt | python-guide/requirements.txt at master · kennethreitz/python-guide
https://sphinx-rtd-theme.readthedocs.io/en/latest/installing.html | Installation — Read the Docs Sphinx Theme 0.3.1 documentation

https://github.com/kennethreitz-archive/kr-sphinx-themes | kennethreitz-archive/kr-sphinx-themes: Sphinx theme I use for most projects. Derivative of Mitsuhiko's Flask theme.

https://docusaurus.io/en/users | Users · Docusaurus
-->

## Anthony Advice

<!--
https://www.youtube.com/watch?v=O390_abzo08&feature=emb_logo | why not global pip / virtualenv? (intermediate) anthony explains #079 - YouTube

https://twitter.com/codewithanthony/status/1285974757750353920 | Anthony Sottile on Twitter: "@chaitan94 you may be interested to learn there's other ways of postmortem debugging as well! https://t.co/wbz8AyhmLP" / Twitter

Anthony Advice
https://www.youtube.com/watch?time_continue=2&v=bfyIrX4_yL8&feature=emb_logo | python packaging: data files (intermediate) anthony explains #071 - YouTube
https://www.youtube.com/watch?v=GaWs-LenLYE&t=471s | (1) python packaging: basic setup.py and declarative metadata (intermediate) anthony explains #057 - YouTube
https://www.youtube.com/watch?v=ZpOoRSkm-dQ&feature=emb_logo | what is PATH? (beginner - intermediate) anthony explains #070 - YouTube


typing
https://www.youtube.com/watch?v=HESA7oukEqE | (1) typing __getitem__ (python / mypy) (intermediate) anthony explains #045 - YouTube

https://www.youtube.com/watch?v=s8Nx2frW4ps | (2) postmortem debugging in python (beginner - intermediate) anthony explains #018 - YouTube

flake8 Plugin
https://www.youtube.com/watch?v=ot5Z4KQPBL8&feature=emb_logo | (3) a flake8 plugin from scratch (intermediate) anthony explains #025 - YouTube
https://github.com/asottile/flake8-2020 | asottile/flake8-2020: flake8 plugin which checks for misuse of `sys.version` or `sys.version_info`

https://www.youtube.com/watch?v=sW1qUZ_nSXk&feature=emb_logo | python packaging: src layout (intermediate) anthony explains #048 - YouTube

intro to tox
https://www.youtube.com/watch?v=75WBE_qbpGk&feature=emb_logo
https://www.youtube.com/watch?v=Gre2W5z4iLE | releasing a python package to pypi (beginner - intermediate) anthony explains #039 - YouTube
tox -e py - Google Search
https://www.youtube.com/watch?v=KKJL8bM4cis | python github actions w/ tox and pre-commit (intermediate) anthony explains #038 - YouTube

https://www.youtube.com/watch?v=-Sgw-6a1HjU | python argparse tutorial (beginner - intermediate) anthony explains #044 - YouTube
https://www.youtube.com/watch?v=sv46294LoP8 | python cli tested with pytest - (beginner to intermediate) anthony explains #001 - YouTube

https://www.youtube.com/watch?v=MGTX5qI2Jts | virtualenv vs. venv (beginner - intermediate) anthony explains #040 - YouTube
https://www.youtube.com/watch?v=dTrW8YktDnE | string formatting in python (beginner - intermediate) anthony explains #042 - YouTube

https://www.youtube.com/watch?time_continue=304&v=ObWh1AYClI0&feature=emb_logo | (3) python variable unpackings (beginner - intermediate) anthony explains #031 - YouTube
https://www.youtube.com/watch?v=2em6MiOpHWk | (2) python curses "hello world" (beginner - intermediate) anthony explains #028 - YouTube
https://www.youtube.com/watch?v=bItxrNqJ5UQ&feature=youtu.be | git: useful trick for pushing branches (beginner - intermediate) anthony explains #037 - YouTube
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

<!--
Tool Choices

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
